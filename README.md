# Luigi’s Mansion UE5.4 — Fan Remake

This is a personal fan project built in **Unreal Engine 5.4**, aiming to recreate the core gameplay loop of *Luigi’s Mansion 2* in a top-down format.

---

## Gameplay Features

- **Top-down fixed camera**
- **Separated movement and aiming**:
  - Move with keyboard (ZQSD)
  - Aim flashlight with mouse
- **Flash mechanic (Shift)**:
  - Only works if the ghost is inside the light cone
- **Capture mechanic (F)**:
  - Player becomes stationary
  - Flashlight transforms into a vacuum beam
  - Fill a capture gauge by aiming correctly at the ghost
  - Gauge decreases if misaligned

---

## Ghost AI Behavior

- Moves around the player in a **circular orbit**
- When in capture mode:
  - Tries to move **away from the flashlight's direction**
- Can be **stunned** only if the flash is well aligned
- Uses a dynamic system to **flip direction** every few seconds, influenced by the player's aiming

---

## Controls (Mouse + Keyboard)

| Action         | Input              |
|----------------|--------------------|
| Move           | `ZQSD` (AZERTY) or `WASD` (QWERTY) |
| Aim flashlight | Mouse movement     |
| Flash          | `Shift`            |
| Capture        | `F`                |

- Flashlight clamp on angle on player's forward.
- Free aiming resumes when stationary on clamp angle.
- Capture locks movement but allows and inverse aiming.

---
## VFX 
 - UI for the capture gauge
 - Visual VFX for vacuum beam and flash
## To-Do / Roadmap

- [ ] Improve ghost dissolve/death effects

---

## Requirements

- Unreal Engine 5.4
- Desktop PC (tested on Windows)



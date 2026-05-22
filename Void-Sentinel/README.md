<p align="center">
  <img src="https://github.com/user-attachments/assets/5b6b67b5-ee01-4b44-bafb-eb2bd68c24c7" width="250" height="250" alt="Void Sentinel">
</p>

# Void-Sentinel

> Version: 0.1

A simple but effective anticheat system, designed to be easy to install and use, while still providing strong protection against common exploit methods.

---

# Installation

1. Download the `Void-Sentinel.rbxmx` file.
2. Drag and drop it into your Roblox game.
3. Move the `Void-Sentinel` folder into `ServerScriptService`.
4. Read the included `README` LocalScript.
5. Customize the `Settings` module to fit your game.

---

# Features

### Detection System
- Anti-Backdoor (detects suspicious script injection/control attempts)
- Anti-Remote Spam (prevents RemoteEvent flooding)
- Anti-Fly (detects unauthorized flight)
- Anti-Noclip (prevents wall clipping)
- Anti-Speed (detects abnormal movement speed)
- Anti-Teleport (detects instant position changes)
- Anti-Reach (detects unrealistic hit distances)
- Anti-GodMode (detects invincibility behavior)

---

### Punishment System
- Kick or Warn players on detection
- Configurable detection threshold system
- Adjustable detection cooldown
- Prevents instant false-positive punishment stacking

```lua
MaxDetections = 3
DetectionCooldown = 5

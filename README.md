# Open Source - Freecam

Created by Stuyk (Trevor Wessel)

❤️ Please support my open source work by donating. I'm here to provide general context for complicated procedures for you new developers. ❤️

https://github.com/sponsors/Stuyk/

❤️ Want direct support for my scripts and tutoring? Check out my Patreon.

https://patreon.com/stuyk

⭐ This repository if you found it useful!

---

![](https://thumbs.gfycat.com/TightGorgeousCaimanlizard-size_restricted.gif)

# Description

This repository provides an easy to use freecam that can be controlled with your mouse, controller, or anything else.
Use bananas if you want I don't care. 🍌

-   Acceleration for Speed
-   Speed Controls
-   Mouse Movement
-   Restore Position on Toggle
-   No Data Stream In Issues
-   Moves Player to Camera Position
-   Makes Player Invisible to Others

# Quick Install

```sh
# Install alt:V Installer
npm install -g altv-pkg
```

```sh
# Install with alt:V Installer
altv-pkg i stuyk/altv-os-freecam
```

# Installing Dependencies / Installation

**I cannot stress this enough. Ensure you have NodeJS 13+ or you will have problems.**

-   [NodeJS 13+](https://nodejs.org/en/download/current/)
-   An Existing or New Gamemode
-   General Scripting Knowledge

Clone this repository or use the quick install instructions.

Add this resource to your `server.cfg`.

## Toggling the Freecam

Simply create a command, keybind, etc. that toggles this event server-side.
That's all.

**Server-Side**

```js
alt.emit('freecam:Toggle', player);
```

# Controls

| Control                            | Description     |
| ---------------------------------- | --------------- |
| `WASD` or `Left Stick`             | Movement        |
| `Mouse` or `Right Stick`           | Camera Movement |
| `]` or `DPad Up`                   | Toggle HUD      |
| `Mouse Wheel Down` or `DPad Right` | Increase Speed  |
| `Mouse Wheel Up` or `DPad Left`    | Decrease Speed  |
| `Q` or `Right Bumper`              | Decrease Height |
| `E` or `Left Bumper`               | Increase Height |

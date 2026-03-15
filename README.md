# 🔥 VIOLENCE DISTRICT - Complete Script

<div align="center">

![Version](https://img.shields.io/badge/version-1.0-blue.svg)
![Status](https://img.shields.io/badge/status-active-success.svg)
![License](https://img.shields.io/badge/license-MIT-green.svg)

**The ultimate script for Violence District with premium Rayfield UI**

[Features](#-features) • [Installation](#-installation) • [Usage](#-usage) • [Screenshots](#-screenshots) • [Credits](#-credits)

</div>

---

## 📋 Table of Contents

- [Features](#-features)
- [Installation](#-installation)
- [Usage](#-usage)
- [Configuration](#-configuration)
- [Screenshots](#-screenshots)
- [FAQ](#-faq)
- [Contributing](#-contributing)
- [Credits](#-credits)
- [License](#-license)

---

## ✨ Features

### 👤 **Player ESP (Auto-Detect)**
- ✅ Boxes - Visual box around players
- ✅ Names - Display player names
- ✅ Distance - Show distance in meters
- ✅ Health - Health bar with color gradient
- ✅ Tracers - Lines from screen center to players
- ✅ **Team Check** - Hide teammates (Green/Red colors)
- ✅ **Auto-Detect** - Automatically detects new players joining!
- ✅ Max Distance slider (500-5000m)

### ✨ **Highlight System**
- ✅ Character highlights through walls
- ✅ **Auto Team Colors**
  - 🟢 Green = Teammates
  - 🔴 Red = Enemies
- ✅ Toggle show/hide teammates
- ✅ FillTransparency & OutlineTransparency controls

### ⚡ **Generator ESP**
- ✅ Shows all generators on map
- ✅ **Progress % display**
- ✅ **Color-coded status:**
  - 🔵 Cyan = In Progress
  - 🟢 Green = Complete (100%)
- ✅ Auto-scan every 3 seconds
- ✅ Highlight through walls

### ⚡ **Anti-Fail Generator**
- ✅ **Auto-pass skill checks**
- ✅ Hold left click to repair
- ✅ Blocks fail events
- ✅ Stable hookmetamethod implementation
- ✅ Toggle ON/OFF

### ❤️ **Anti-Fail Healing**
- ✅ **Never fail healing skill checks**
- ✅ Auto-success on skill checks
- ✅ Blocks fail events
- ✅ Stable hookmetamethod implementation
- ✅ Toggle ON/OFF

### ☀️ **Visual Enhancements**
- ✅ **Fullbright** - Make the map bright
  - Toggle ON/OFF
  - Saves original lighting settings
  - Returns to dark when disabled
- ✅ **Hide Skill Check UI** - Clean screen mode
  - Hides SkillCheckPromptGui
  - Hides SkillCheckPromptGui-con
  - Uses RenderStepped for instant hide
  - Toggle ON/OFF

### 🏃 **Movement Hacks**
- ✅ **Speed Hack** (16-200)
  - Adjustable speed slider
  - Returns to normal when disabled
- ✅ **Jump Hack** (50-300)
  - Adjustable jump power slider
  - Returns to normal when disabled
- ✅ **Infinite Jump** 🚀
  - Jump unlimited times in air
- ✅ **Noclip** 👻
  - Walk through walls
  - Stable implementation
  - Proper collision restoration

### 🎨 **Premium UI (Rayfield)**
- ✅ Modern & clean interface
- ✅ 7 organized tabs
- ✅ Auto-save configuration
- ✅ Smooth animations
- ✅ Mobile-friendly
- ✅ Easy to use

---

## 📥 Installation

### Method 1: Loadstring (Recommended)

Copy and execute this in your executor:

```lua
loadstring(game:HttpGet('https://raw.githubusercontent.com/RanZx999/ViolenceDistrict/main/ViolenceDistrict.lua'))()
```


## 🎮 Usage

### Controls

- **Right CTRL** - Toggle UI
- **All settings auto-save** - Your preferences are remembered!

### Quick Start

1. Execute the script
2. Press **Right CTRL** to open the UI
3. Navigate through tabs:
   - 👤 **Player ESP** - ESP settings
   - ✨ **Highlight** - Highlight settings
   - ⚡ **Generator** - Generator ESP + Anti-Fail
   - ❤️ **Healing** - Anti-Fail Healing
   - ☀️ **Visual** - Fullbright + Hide UI
   - 🏃 **Movement** - Speed/Jump/Noclip
   - ⚙️ **Settings** - Info & Destroy script
4. Toggle features ON/OFF as needed
5. Enjoy! 🎉

---

## ⚙️ Configuration

### Player ESP Settings

```lua
Config.ESP = {
    Enabled = false,        -- Master toggle
    Boxes = false,          -- Show boxes
    Names = false,          -- Show names
    Distance = false,       -- Show distance
    Health = false,         -- Show health bars
    Tracers = false,        -- Show tracers
    TeamCheck = true,       -- Hide teammates
    MaxDistance = 2000      -- Max render distance
}
```

### Highlight Settings

```lua
Config.Highlight = {
    Enabled = false,        -- Master toggle
    TeamCheck = true,       -- Team color mode
    ShowTeam = false        -- Show teammate highlights
}
```

### Generator Settings

```lua
Config.Generator = {
    ESPEnabled = false,     -- Generator ESP
    AntiFailEnabled = false -- Anti-fail generator
}
```

### Movement Settings

```lua
Config.Movement = {
    SpeedEnabled = false,   -- Speed hack
    SpeedValue = 16,        -- Speed value
    JumpEnabled = false,    -- Jump hack
    JumpValue = 50,         -- Jump power
    InfiniteJump = false,   -- Infinite jump
    Noclip = false          -- Noclip
}
```

---

## 📸 Screenshots

### Main UI
![Main UI](https://via.placeholder.com/800x400?text=Main+UI+Screenshot)

### Player ESP in Action
![Player ESP](https://via.placeholder.com/800x400?text=Player+ESP+Screenshot)

### Generator ESP
![Generator ESP](https://via.placeholder.com/800x400?text=Generator+ESP+Screenshot)

---

## ❓ FAQ

### Q: Does this work on mobile?
**A:** Yes! The Rayfield UI is fully mobile-friendly.

### Q: Will I get banned?
**A:** Use at your own risk. We recommend using alt accounts and being cautious with obvious features like speed/noclip.

### Q: ESP not showing players?
**A:** Make sure:
- ESP is toggled ON
- Individual features (Boxes, Names, etc.) are enabled
- Players are within Max Distance range
- Team Check is configured correctly

### Q: Anti-Fail not working?
**A:** Make sure:
- Anti-Fail is toggled ON
- You're holding left click when repairing/healing
- The game's remote structure hasn't changed

### Q: How do I unload the script?
**A:** Go to Settings tab and click "Destroy Script" button.

---

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

---

## 🌟 Credits

### Developer
- **RanZx999** - *Main Developer* - [GitHub](https://github.com/RanZx999)

### UI Library
- **Rayfield** - Premium UI Library - [Rayfield](https://sirius.menu/rayfield)

### Special Thanks
- Violence District community
- All contributors and testers

---

## 📜 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

## ⚠️ Disclaimer

This script is for **educational purposes only**. 

- Use at your own risk
- The developers are not responsible for any consequences
- This may violate the game's Terms of Service
- We recommend using on alt accounts

---

## 📞 Support

### Issues
If you encounter any bugs or issues, please [open an issue](https://github.com/RanZx999/violence-district/issues).

### Updates
Check [Releases](https://github.com/RanZx999/violence-district/releases) for the latest updates.

---

<div align="center">

### ⭐ If you like this project, please give it a star!

**Made with ❤️ by RanZx999**

[⬆ Back to Top](#-violence-district---complete-script)

</div>

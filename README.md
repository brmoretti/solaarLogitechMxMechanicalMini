# 🖥️ Logitech MX Mechanical Mini Configuration for Solaar

**Custom key mappings and Solaar configuration files**
*Tested on PopOS! · Wayland*

[![Solaar Required](https://img.shields.io/badge/Requires-Solaar%201.1.9+-blue)](https://github.com/pwr-Solaar/Solaar)

## 📦 Features
- **Smart Key Bindings**:
  - `Dictation` ➔ ChatGPT (Firefox)
  - `Emoji Key` ➔ GNOME Characters picker
  - `Screen Capture` ➔ Screenshot
  - `Mute Microphone` ➔ Audio Mute
  - `MultiPlatform Search` ➔ Google Search (Firefox)


## ⚡ Quick Start

### Prerequisites
- [Solaar](https://github.com/pwr-Solaar/Solaar)
- Firefox (`firefox`) - You can change the browser on the `rules.yaml` or solaar GUI
- GNOME Characters (`gnome-characters`) - Can be modified either

### 🛠️ Installation

1. Open Solaar and verify your Logitech MX Mechanical Mini keyboard is detected

2. Backup existing config (if any)
```bash
mv ~/.config/solaar ~/.config/solaar.bak
```

3. Clone this configuration
```bash
git clone https://github.com/brmoretti/solaarLogitechMxMechanicalMini.git ~/.config/solaar
```

4. Restart Solaar

5. **(Required for Wayland) Wayland Setup**

  On Wayland sessions, configure udev permissions by running:
  ```bash
  sudo curl -o /etc/udev/rules.d/42-logitech-unify-permissions.rules \
  https://raw.githubusercontent.com/pwr-Solaar/Solaar/master/rules.d-uinput/42-logitech-unify-permissions.rules
  ```

  Reboot your system for the changes to take effect.

  For more details, see the [Solaar udev rules documentation](https://pwr-solaar.github.io/Solaar/rules/).

## 📄 License
This configuration is released under MIT License.
*Not affiliated with Logitech or Solaar development team.*

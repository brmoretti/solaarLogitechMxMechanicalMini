# 🖥️ Logitech MX Mechanical Mini Configuration for Solaar

**Custom key mappings and Solaar configuration files optimized for Linux workflows**  
*Tested on Linux Mint · Chrome/Flux AI Integration · Emoji Support · Multi-Device Management*

[![Linux Compatible](https://img.shields.io/badge/Linux-Compatible-brightgreen)](https://github.com/pwr-Solaar/Solaar)
[![Tested on Mint](https://img.shields.io/badge/Tested%20on-Linux%20Mint%2021.3-9cf)](https://linuxmint.com)
[![Solaar Required](https://img.shields.io/badge/Requires-Solaar%201.1.9+-blue)](https://github.com/pwr-Solaar/Solaar)

## 📦 Features
- **Smart Key Bindings**:
  - `Voice Dictation Button` ➔ DeepSeek
  - `Emoji Key` ➔ GNOME Characters picker
  - `Screnshot` ➔ Working
  - `Mute Micropho` ➔ Working
  - `Browse Key` ➔ Google Search on Google Chrome


## ⚡ Quick Start

### Prerequisites
- [Solaar](https://github.com/pwr-Solaar/Solaar)
- Git
- Google Chrome (`google-chrome-stable`) - You can change the browser on the `rules.yaml` or solaar GUI
- GNOME Characters (`gnome-characters`)

```bash
# 1. Backup existing config (if any)
mv ~/.config/solaar ~/.config/solaar.bak

# 2. Clone this configuration
git clone https://github.com/brmoretti/solaarLogitechMxMechanicalMini.git ~/.config/solaar

# 3. Restart Solaar

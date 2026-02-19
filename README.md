OS: Arch Linux (Omarchy)

WM: Hyprland

Font: JetBrainsMono Nerd Font



# 🌸 Omarchy Waybar Rice

A modern, highly-customized Waybar configuration for Hyprland, inspired by the **end4** aesthetic. This setup focuses on a "Floating Pill" design with a deep glass-morphism effect.

## 🛠 Features
* **Floating Pill Design**: Modular layout with centered elements for a clean, symmetrical look.
* **Glass-morphism Aesthetic**: Uses semi-transparent backgrounds (`rgba(30, 30, 46, 0.7)`) with subtle borders and no text shadows.
* **Dynamic Weather**: Integrated `wttr.in` module for Burnsville, MN, including a custom "on-click" weather app terminal popup.
* **Exclusive Layering**: Configured with `"exclusive": true` to ensure applications never overlap the bar.

## 🎨 Visual Preferences
* **Color Palette**: 
    * **Accent**: Sakura Pink (`#f5c2e7`)
    * **Secondary**: Moon Blue (`#89b4fa`)
* **Typography**: 'JetBrainsMono Nerd Font' set to Extra Bold (800) for high readability.
* **Theme**: Deeply inspired by Demon Slayer motifs, syncing with a custom `hyprlock` screen.

## 📦 Dependencies
To replicate this look exactly, ensure you have the following installed on Arch Linux:
* `waybar`
* `ttf-jetbrains-mono-nerd`
* `kitty` (for the weather popup)
* `curl` (for weather data)
* `oterm` or `omarchy` shell tools

## 🚀 Installation
1. Copy the `waybar` folder to `~/.config/`:
   ```bash
   cp -r .config/waybar ~/.config/

2. Reload Waybar:
      ```bash
   killall waybar; waybar &

---

### Why this fits your "End4" style:
* **Modularity**: Like end4, your config uses separate CSS variables for easy theme swapping.
* **Cleanliness**: It avoids the "cluttered" look of traditional bars by using centered modules and spacing.
* **Performance**: It relies on native Waybar modules and lightweight scripts rather than heavy external applications.

**Would you like me to help you take a high-quality screenshot of your desktop using `grim` and `slurp` so you can add it to the top of this README?**


<img width="2560" height="1439" alt="image" src="https://github.com/user-attachments/assets/68b3e862-c395-4841-b991-2aaae3f23f80" />

<img width="2560" height="1440" alt="image" src="https://github.com/user-attachments/assets/cc9348f6-e30e-460c-96ec-d96f9bcae168" />

# Complete Labwc Setup

A ready to use configuration for **Labwc** wayland compositor with 20 preconfigured color schemes + dynamic wallpaper-based color generation using matugen.

---

## ✨ Features

- **Preconfigured Themes** -  preconfigured color schemes for labwc, GTK3, GTK4, Rofi and waybar.
- **Wallpaper-Based Color Generation** - Generate themes from wallpapers using Matugen
- **Rofi Applets** - Utility applets (wallpaper picker, WiFi, now playing, etc.)

---

## 🎨 Preconfigured Themes (20 Total)

Tokyo Night, Onedark, Dracula, Catppuccin, Gruvbox, Nord, Everforest, Everforest Light, Solarized Dark, Solarized, Lavender Pastel, Arc, Adapta, Black, Navy, Lovelace, Paper, Cyberpunk, Yousai, and Wallpaper-based.

---
## Rofi Applets

- **Wallpaper Picker** - Browse, select wallpapers with live preview generates wallpaper 

  <details>
  <summary><b><code>Click to previes</code></b></summary>
  
  | | |
  |-|-|
  |![wallselect](https://github.com/user-attachments/assets/16c61848-88e1-49f6-bad9-cf69a048f0bc)|![wallselect](https://github.com/user-attachments/assets/99052231-6865-4e05-b5cd-bc62d01ef06a)|

</details>
  
- **WiFi Manager** - Connect to WiFi networks directly from Rofi

  <details>
  <summary><b><code>Click to previes</code></b></summary>

  [wifi](https://github.com/user-attachments/assets/779cb6fa-7909-4df0-9d58-5d9d525d3b18)

  </details>

- **Now Playing** - Display currently playing media

  <details>
  <summary><b><code>Click to previes</code></b></summary>

  [nowplaying](https://github.com/user-attachments/assets/9426fdae-8a95-4335-972e-11dd9aaa1762)

  </details>
 


- **Screen Tool** -

  <details>
  <summary><b><code>Click to previes</code></b></summary>
    
  | | | |
  |-|-|-|
  |![Screenrecord-thumbnail](https://github.com/user-attachments/assets/66757cca-3feb-4080-b832-9972bc87d675)|![Screenshot-save](https://github.com/user-attachments/assets/b55b5e35-360d-4c1f-aab0-13e88de17074)|![Screenshot-copied](https://github.com/user-attachments/assets/cb97e7fd-4218-48ef-897f-bad77e97939a)|

  [screentool](https://github.com/user-attachments/assets/3ea9bfa6-5348-4d1e-a7a1-1ed885b7a2c6)
  </details>



- **Clipboard Manager** - Access clipboard history with images support

  <details>
  <summary><b><code>Click to previes</code></b></summary>

  [clipboard](https://github.com/user-attachments/assets/bc4f54b8-6bb6-4a74-96db-2ca61d81e915)

  </details>

- **Nightlight** - Quick access to blue light filter controls

  <details>
  <summary><b><code>Click to previes</code></b></summary>

  [nightlight](https://github.com/user-attachments/assets/11784326-a632-456d-a01c-0ad04f59d83b)

  </details>

---

## Rofi Launchers

<details>
<summary><b><code>Click to previes</code></b></summary>

![launcher10](https://github.com/user-attachments/assets/2bf01b16-5133-41f9-b02c-1898ad59fef3)

![launcher9](https://github.com/user-attachments/assets/6a4b8384-5bb5-4a31-aeb0-497a372ff6d1)

![<launcher8](https://github.com/user-attachments/assets/12dd4fa5-3081-4d50-a526-153c2445c998)

![launcher7](https://github.com/user-attachments/assets/bb6053bc-64d6-446b-a812-119b60d70809)

![launcher6](https://github.com/user-attachments/assets/10a1db31-4672-4125-969d-e2a8e9611c11)

![launcher5](https://github.com/user-attachments/assets/6e4bafe4-b262-490b-92e2-9578899a41bc)

![launcher4](https://github.com/user-attachments/assets/356e4410-9c0c-4e9b-b215-2cc399b9ab80)

![launcher3](https://github.com/user-attachments/assets/e6aa844e-d9ad-48cd-8abe-add5221bd291)

![launcher2](https://github.com/user-attachments/assets/dae41bc2-db4e-42cf-834e-7c901230dc2f)

![launcher1](https://github.com/user-attachments/assets/813b093f-0638-40ca-883b-bfd615dbc815)

</details>

## Rofi Powermenu
<details>
<summary><b><code>Click to previes</code></summary>

![powermenu1](https://github.com/user-attachments/assets/63ef714b-339a-4f24-910f-39063ca9901d)
![powermenu2](https://github.com/user-attachments/assets/34ac5343-d1e8-4dda-bdde-02d18860ed31)
![powermenu3](https://github.com/user-attachments/assets/8d234137-a551-4b79-af26-25aa4ab5994f)
![powermenu4](https://github.com/user-attachments/assets/e208c391-66ae-493b-a4b4-00c7b833b0ab)
![powermenu5](https://github.com/user-attachments/assets/6fa0ef70-9857-47ef-adc7-459a801e5bfb)
![powermenu6](https://github.com/user-attachments/assets/81155fec-a7a5-4e71-b697-39b0a3f4df45)
![powermenu7](https://github.com/user-attachments/assets/e47197f3-04be-43bd-afeb-6eeba9570435)
![powermenu8](https://github.com/user-attachments/assets/36122913-484f-4e04-bad0-1a1a7c7dd98a)

</details>

## Waybar

<details>
<summary><b><code>Click to previes</code></b></summary>

![theme-change](https://github.com/user-attachments/assets/f5dc93d5-157f-4104-95fb-100fd733ca00)

</details>

---

## Installation

**Arch Linux Users:**
```bash
git clone https://github.com/Harsh-bin/labwc-setup
cd labwc-setup
chmod +x setup.sh
./setup.sh
```
**Other Distributions:**
1. Install dependencies manually 
2. Copy config files to `~/.config/` matching the directory structure
3. Copy fonts if needed to `~/.local/share/`
4. Copy `matugen-labwc` theme folder to `~/.themes`

---

## Dependencies

**For Arch Linux**: Run `setup.sh` to automatically install all dependencies.

**For Other Distributions**: Install these packages manually:


- `labwc`
- `waybar`
- `rofi`
- `matugen`
- `adw-gtk-theme`
- `dunst`
- `swww`
- `polkit-gnome`
- `gnome-keyring`
- `wl-clipboard`
- `cliphist`
- `wl-clip-persist`
- `swayidle`
- `hyprlock`
- `foot`
- `imagemagick`
- `ffmpegthumbnailer`
- `ffmpeg`
- `otf-font-awesome`
- `inter-font`
- `ttf-roboto`
- `papirus-icon-theme`
- `qt5-wayland`
- `qt6-wayland`
- `nm-connection-editor`
- `gammastep`
- `wf-recorder`
- `grim`
- `slurp`
- `playerctl`

---

**Enjoy your beautifully themed Labwc desktop!** 

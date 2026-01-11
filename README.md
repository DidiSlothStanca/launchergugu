# 🎮 GuguOS Launcher (Gamepad-Friendly Linux Launcher)

GuguOS Launcher is a **fullscreen launcher built with Python (Tkinter)**, designed to be fully usable with **keyboard and gamepad**. It is ideal for lightweight Linux distributions (AntiX, Void, Arch, etc.) as a console-style application and game launcher.

---

## ✨ Key Features

- 🎮 Full navigation using **Gamepad / Keyboard**
- 🖥️ Fullscreen interface with smooth animations
- 🗂️ Launcher based on **`.sh` shortcut scripts**
- 🎨 Multiple themes (Default, Dark, Pinky)
- 🖼️ Wallpaper support with multiple modes (Fill, Stretch, Fit, etc.)
- 🌐 Multi-language support (Indonesian & English)
- ⌨️ Virtual Keyboard (for gamepad text input)
- 🔌 Power menu (Shutdown, Reboot, Logout)
- 📦 Detects OS applications from `.desktop` files
- 🖼️ Custom application icons and covers
- 🎮 Automatic gamepad detection + manual rescan

---

## 📦 Dependencies & Installation

### 🟦 Arch Linux
```bash
sudo pacman -S python python-pillow python-pygame tk
```

### 🟥 Debian / AntiX / Ubuntu
```bash
sudo apt install python3 python3-tk python3-pil python3-pil.imagetk python3-pygame
```

### 🟨 Fedora
```bash
sudo dnf install python3 python3-tkinter python3-pillow python3-pygame
```

### 🟩 Void Linux
```bash
sudo xbps-install python3 python3-tkinter python3-Pillow python3-pygame
```

---

## 📂 Extracting & Running

```bash
git clone https://github.com/username/guguos-launcher.git
cd guguos-launcher
python3 launcher_pad.py
```

---

## ⌨️ Keyboard Shortcuts

| Key | Function |
|----|---------|
| Arrow Keys | Navigate |
| Enter | Select / Confirm |
| Backspace | Back |
| Esc | Power Menu |
| **S / Shift + S** | Rescan Gamepad |

---

## 🎮 Gamepad Controls

| Button | Function |
|------|---------|
| D-Pad / Analog Stick | Navigate |
| Button 0 | Select |
| Button 1 | Back |
| Start / Options | Menu |

---

## 📜 License

Free to use, modify, and distribute.

# 🎬 Complete Kdenlive Guide for Linux (Ubuntu, Fedora, Arch) 🐧

Kdenlive is a **powerful open-source** video editor built for creators who want pro tools without the price tag. Let’s set it up and make cinematic edits across all major Linux distros!

---

## 🛠 Installation on Different Distros

### Ubuntu/Debian 🐳
```bash
sudo apt update
sudo apt install kdenlive
```

### Fedora/RHEL 🎩
```bash
sudo dnf install kdenlive
```

### Arch Linux/Manjaro 🏗️
```bash
sudo pacman -S kdenlive
```

### OpenSUSE 🦎
```bash
sudo zypper install kdenlive
```

Or use the **official AppImage**:
```bash
# Download from:
https://kdenlive.org/en/download/
# Make it executable
chmod +x Kdenlive-*.AppImage
./Kdenlive-*.AppImage
```

---

## 🏁 Basic Workflow
1. **Import your footage** via drag and drop.
2. Add clips to the **Timeline** (Video Track 1, Video Track 2, etc).
3. Use **Effects**, **Transitions**, and **Keyframes** to edit.
4. Export using **Render** → choose H.264 MP4 or YouTube preset.

---

## 🪞 How to Overlay Video with Transparency

### 🔹 Example: Desktop video over a base clip
1. Add base video to **Video Track 1**.
2. Add desktop recording to **Video Track 2**.
3. Click on the top clip → go to **Effects**.
4. Search for `Opacity` → drag to the clip.
5. In the **Effect Stack**, adjust Opacity to `0.3–0.7` for semi-transparency.

✅ Optional: Use **“Composite and Transform”** effect for position, scale, and blend mode.

---

## 🎮 Essential Keyboard Shortcuts

| Key           | Action           | Emoji |
|---------------|------------------|--------|
| Space         | Play/Pause       | ▶️     |
| Ctrl + Z      | Undo             | ↩️     |
| Ctrl + Shift + R | Render Project | 🧪     |
| M             | Add Marker       | 📍     |
| Shift + G     | Group Clips      | 🧩     |
| Del           | Remove Clip      | 🗑️     |

---

## ⚡ Recommended Effects

```text
● Transform → Resize, position clips
● Rotoscoping → Mask out areas
● Color Grading → LUTs, contrast, gamma
● Speed → Slow motion or fast-forward
● Title Editor → Add dynamic text
```

---

## 🛠 Config & Project Settings

All user settings stored at:
```bash
~/.config/kdenlive/
```

Project settings:  
→ **Project > Project Settings** → choose resolution (e.g. 1920x1080), framerate (e.g. 30 fps), aspect ratio.

---

## 🚀 Performance Tips

```bash
# Use proxy clips for faster editing
Settings > Configure Kdenlive > Proxy Clips → Enable

# Use GPU acceleration if supported
Settings > Configure Kdenlive > Playback > Renderer: OpenGL

# Clear cache if needed
rm -rf ~/.cache/kdenlive
```

---

## ✅ Why Kdenlive Rocks

- Full-featured NLE with multi-track timeline  
- Works 100% natively on Linux  
- GPU preview rendering  
- Dozens of effects, filters & transitions  
- Great for YouTube, film, tutorials, and more  

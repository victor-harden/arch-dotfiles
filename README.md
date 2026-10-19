<div align="center">

# 🐧 Arch Dotfiles

**Personal Arch Linux + Hyprland configuration**  
Focused on productivity, minimalism and security.

</div>

---

## Stack

- **WM**: Hyprland (Wayland)
- **Bar**: Waybar
- **Launcher**: Rofi / Walker
- **Terminal**: Kitty / Foot
- **Shell**: Zsh + plugins
- **Theme**: Dark, low distraction

## Structure

```text
.config/
├── hypr/
├── waybar/
├── kitty/
├── zsh/
└── rofi/
```

## Installation

```bash
# Backup first
cp -r ~/.config ~/.config.bak

# Clone and copy
git clone https://github.com/blackhat264/arch-dotfiles.git
cd arch-dotfiles
cp -r .config/* ~/.config/
```

## Notes

These configs are tailored to my workflow. Review before applying.

## License

MIT

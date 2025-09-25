# i3WM-my-config

<div align="center">
  <img src="https://raw.githubusercontent.com/wobbbler/my-i3wm-config/main/rice.png" alt="My i3 Desktop" width="800">
  
  # 🖥️ My i3WM Configuration

  ![i3wm](https://img.shields.io/badge/i3wm-Config-blueviolet?style=for-the-badge&logo=i3)
  ![Linux](https://img.shields.io/badge/Linux-WM-1793D1?style=for-the-badge&logo=linux)
  ![License](https://img.shields.io/badge/License-MIT-green?style=for-the-badge)

  > My personalized i3 window manager config with beautiful effects and convenient utilities

</div>

### 📦 Clone Repository
```bash
git clone https://github.com/wobbbler/my-i3wm-config.git ~/all-configs
cd ~/all-configs
```

### ⚡ Apply Configuration
```bash
# Create config directories
mkdir -p ~/.config/{alacritty,fastfetch,picom,polybar,ranger,i3, dunst}

# Copy config files
cp ~/all-configs/alacritty.toml ~/.config/alacritty/
cp ~/all-configs/config.jsonc ~/.config/fastfetch/
cp ~/all-configs/picom.conf ~/.config/picom/
cp ~/all-configs/config.ini ~/.config/polybar/
cp ~/all-configs/rc.conf ~/.config/ranger/
cp ~/all-configs/config ~/.config/i3/config

# Edit i3 config (optional)
nvim ~/.config/i3/config

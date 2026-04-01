# ArchCosta Cinnamon Edition Settings

Desktop environment configuration package for the ArchCosta Cinnamon edition.

## What's Included

- **Desktop:** Cinnamon with Arc-Dark theme
- **Display Manager:** LightDM with Slick Greeter (separate from XFCE's LightDM config)
- **Panel:** Bottom panel with menu, grouped window list, system tray, calendar
- **File Manager:** Nemo with list view, location bar, tree sidebar
- **Icons:** Papirus-Dark
- **Fonts:** Noto Sans 11pt, JetBrainsMono Nerd Font for terminal
- **Touchpad:** Tap-to-click, natural scrolling
- **Power:** Sensible defaults for AC/battery sleep timers

## Display Manager

This edition uses **LightDM** with `lightdm-slick-greeter` (NOT the GTK greeter used by XFCE). Each edition's LightDM configuration is completely independent.

## dconf Defaults

System-wide defaults are set via `/etc/dconf/db/local.d/01-archcosta-cinnamon`. Users can override any setting through Cinnamon Settings.

## Dependencies

```
cinnamon nemo xed xreader
lightdm lightdm-slick-greeter lightdm-settings
arc-gtk-theme papirus-icon-theme
noto-fonts ttf-jetbrains-mono-nerd
```

## License

GPL-3.0

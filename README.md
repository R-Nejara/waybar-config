# Waybar Config

Custom configuration for [Waybar](https://github.com/Alexays/Waybar), a highly customizable status bar for Linux.

## Showcase
<br/>

![waybar screenshot 1](https://raw.githubusercontent.com/R-Nejara/waybar-config/refs/heads/main/waybar.png)

## Features

- Minimal CSS appearance
- Custom Lua and shell modules
- Integration with external utilities

## Dependencies

Make sure these are installed for full functionality:

- [Waybar](https://github.com/Alexays/Waybar)
- `impala` (available via `pacman` on Arch Linux)
- `wiremix` (available via `pacman` on Arch Linux)
- Lua
- Common shell utilities (bash, etc.)

### Install on Arch Linux

```sh
sudo pacman -S waybar lua impala wiremix
```

### Install on Debian/Ubuntu

> See your distribution’s documentation for details.

## Usage

1. Clone this repository:
   ```sh
   git clone https://github.com/R-Nejara/waybar-config.git
   ```
2. Copy configs to your Waybar config directory (`~/.config/waybar/`).
3. Restart Waybar.

## License

MIT

---

_Results for dependencies are based on a limited code search. [See more results in the GitHub UI.](https://github.com/R-Nejara/waybar-config/search?q=impala+OR+wiremix)_

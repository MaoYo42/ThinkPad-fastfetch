# ThinkPad-fastfetch

A ThinkPad-inspired fastfetch configuration with the classic V-shaped logo and TrackPoint red dot.

## Preview

```
████████████████                  ╭───────────────╮
   █▙▄▄▄▄▄▄▄▄▄▟█               │ 󰮯 fastfetch   │ ...
    ▀▀▀▀▀▀▀▀▀▀▀                  ├───────────────┤
   ▄████████████                  │  whoami      │ ...
   █▙▄▄ █▙▄▄▄▄▟█               │ 󰇅 hostname    │ ...
    ▀▀▀  ▀▀▀▀▀▀                  │  machine     │ ThinkPad T480s
▄███████▄                         │ 󰣇 distro      │ Arch Linux
█▙▄▄▄▄▄▟█▄▄▄▄▄▄▄               ├───────────────┤
▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀               │ 󰾍 window mgr  │ niri
   █████▄ ▄█████                  │  terminal    │ hermes
▄▄▄▄▄▄▄▄▟█▙▄▄▄▄▄               │  shell       │ bash
▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀               ├───────────────┤
   ▄████████████                  │ 󰍹 display     │ 1920x1080
   █▙▄▄▄▄▄▄▄▄▄▄▄               │ 󰍛 cpu         │ i7-8650U (8)
   ▀▀▀▀▀▀▀▀▀▀▀▀▀               │ 󰢮 gpu         │ UHD Graphics 620
██ █████████████                  │  memory      │ 5.69 GiB / 23.34 GiB
    ▄▄▄▄▄▄▄▄▄▄▄▄               │ 󰉉 disk        │ 56.49 GiB / 237.47 GiB
   █▛▀▀▀▀▀▀▀▀▀▀▀               ╰───────────────╯
████████████████
▄▄
██▄▄▄▄▄▄▄▄▄▄▄▄▄▄
██▀▀▀▀▀▀▀▀▀▀▀▀▀▀
▀▀
```

## Installation

1. Copy the files to `~/.config/fastfetch/`:
   ```bash
   cp config.jsonc ~/.config/fastfetch/
   cp thinkpad-v.txt ~/.config/fastfetch/
   ```
2. Run `fastfetch` to see the result.

## Credits

- Original ThinkPad V logo design by `trekkie-dev` on Codeberg
- Adapted with white body + red TrackPoint dot color scheme

## License

MIT

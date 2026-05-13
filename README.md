# ThinkPad-fastfetch

A ThinkPad-inspired fastfetch configuration by [MaoYo42](https://github.com/MaoYo42), based on the original design by [trekkie-dev](https://codeberg.org/trekkie-dev/fastfetch).

Classic V-shaped logo with TrackPoint red dot, in a framed terminal info panel.

## Preview

```
████████████████                  ╭───────────────╮
   █▙▄▄▄▄▄▄▄▄▄▟█               │ 󰮯 fastfetch   │ 󰮯 󰊠 󰊠 󰊠 󰊠 󰊠 󰊠 󰊠
    ▀▀▀▀▀▀▀▀▀▀▀                  ├───────────────┤
   ▄████████████                  │  whoami      │ maoyo
   █▙▄▄ █▙▄▄▄▄▟█               │ 󰇅 hostname    │ arch
    ▀▀▀  ▀▀▀▀▀▀                  │  machine     │ ThinkPad T480s
▄███████▄                         │ 󰣇 distro      │ Arch Linux
█▙▄▄▄▄▄▟█▄▄▄▄▄▄▄               │  kernel      │ Linux 6.x
▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀               │ 󰃭 os age      │ 55 days
   █████▄ ▄█████                  │ 󰥔 uptime      │ 16 mins
▄▄▄▄▄▄▄▄▟█▙▄▄▄▄▄               ├───────────────┤
▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀               │ 󰾍 window mgr  │ niri
   ▄████████████                  │  terminal    │ kitty
   █▙▄▄▄▄▄▄▄▄▄▄▄               │  shell       │ fish
   ▀▀▀▀▀▀▀▀▀▀▀▀▀               │ 󰛖 term font   │ JetBrainsMono
██ █████████████                  │  system font │ Source Han Sans
    ▄▄▄▄▄▄▄▄▄▄▄▄               │ 󰏔 packages    │ 1330 (pacman)
   █▛▀▀▀▀▀▀▀▀▀▀▀               ├───────────────┤
████████████████                  │ 󰍹 display     │ 1920x1080 @ 60 Hz
▄▄                               │ 󰍛 cpu         │ i7-8650U (8) @ 4.20 GHz
██▄▄▄▄▄▄▄▄▄▄▄▄▄▄               │ 󰢮 gpu         │ UHD Graphics 620
██▀▀▀▀▀▀▀▀▀▀▀▀▀▀               │  memory      │ 23.34 GiB
▀▀                               │ 󰉉 disk        │ 237.47 GiB - btrfs
                                  ╰───────────────╯
```

## Installation

1. Copy the files to `~/.config/fastfetch/`:
   ```bash
   cp config.jsonc ~/.config/fastfetch/
   cp thinkpad-v.txt ~/.config/fastfetch/
   ```
2. Run `fastfetch` to see the result.

## Features

- ThinkPad V-shaped ASCII logo with red TrackPoint dot
- Framed info panel with ThinkPad red accents
- System info: OS, kernel, uptime, OS age, Window Manager, terminal, shell, fonts, packages, display, CPU, GPU, memory, disk
- Rainbow-colored title decoration

## Credits

- Original ThinkPad V logo design by [trekkie-dev](https://codeberg.org/trekkie-dev/fastfetch) on Codeberg
- Red-framed layout inspired by the same design

## License

MIT

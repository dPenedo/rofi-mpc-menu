# Rofi MPC Menu

A simple menu for controlling MPD via `mpc`, using `rofi` as the interface and Nerd Font icons for visual clarity.

Originally inspired by [rofi-mpc](https://github.com/Marco98/rofi-mpc), this version evolved into something different, using a different structure and some new behaviors, like playlist handling and icon display.

## Features

- Play / Pause
- Next
- Previous
- Toggle Random Mode
- Select Source (Local or Playlists)

## Requirements

- Python 3
- [MPD](https://www.musicpd.org/)
- [MPC](https://www.musicpd.org/clients/mpc/)
- [Rofi](https://github.com/davatorium/rofi)
- A [Nerd Font](https://www.nerdfonts.com/) (for icon support)

## Installation

Make the script executable:

```sh
chmod +x rofi_mpc_menu.py
```

(Optional) Move it to a directory in your PATH:

```sh
mv rofi_mpc_menu.py ~/.local/bin/rofi_mpc_menu
```

Run it from a terminal, a keybinding, or via Rofi itself:

```sh
rofi_mpc_menu
```

### Font configuration

To display icons correctly, configure Rofi to use a Nerd Font, for example:

```sh
configuration {
    font: "JetBrainsMono Nerd Font 12";
}
```

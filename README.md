# Svorak

Based on the forked repo. Forked it to keep track of my own changes, since it tends to be overwritten by updates.

## Installation

1. Edit `/usr/share/X11/xkb/symbols/se`
2. Overwrite the keybinds in an existing layout that you don't need. Keep the layout name (change `xkb_symbols "svorak"` in this repo to whatever the existing layout was called).
3. Save as sudo.
4. Add the edited layout to keyboard layouts.

## Why?
Some applications like terminal and password prompts seem to use the first keyboard layout in the list in Settings. I couldn't find a way to make `setxkbmap` work with the terminal.
Also, adding new layouts is more complicated than just overwriting an old one. It's not like we need more than one.

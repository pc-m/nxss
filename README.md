# nxss
A wrapper script to disable and enable xscreensaver before and after executing a process.

Usage:

nxss <command> [command arguments...]

Example:

```
[Desktop Entry]
Name=higan
Comment=Emulator
Exec=/home/pcm/bin/nxss higan
Icon=higan
Terminal=false
Type=Application
Categories=Game;Emulator;
Keywords=emulator;Nintendo;SNES;NES;Gameboy;Famicom;Super;
```

This .desktop will stop xscreensaver, start higan, and start xscreensaver

# CS2-Hammer-Hotkey-Editor
GUI Editor for CS2 Hammer

This is written entirely in PowerShell since that is what I do a lot of my day job in. You can download a compile (PS2EXE) binary from releases.

Alternatively download the .ps1 file and run it with Powershell. The UI should open.

It will automatically open the Hammer 5 CS2 keybind file if it finds it in the default install on your C:\ drive, otherwise use File -> Open. Other hotkey files are supported, such as the ModelDoc hotkeys. However at the time of writing the unbound keys are not added to the list.

The 3 text fields at the bottom are a .Contains search for each of the respective columns.
![image](https://github.com/tophattwaffle/CS2-Hammer-Hotkey-Editor/assets/6774125/4991beef-cdd3-41eb-8356-4cf11e1d3389)

Hammer 5 ships with many unbound keys. I have manually added these and you can find them at the bottom of the list where you can assign them to a keybind.

Every time you save a file, 2 copies will be saved - this is to serve as a backup for your settings. The first copy with the desired filename, the 2nd with the save date/time. This cannot be disabled unless you edit the PS1 file.

I am not a UI/UX person - the UI sucks but is usable imo.

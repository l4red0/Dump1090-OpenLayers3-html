# Dump1090 Dark

This is fork of [alkissack's Dump1090-OpenLayers3-html](https://github.com/alkissack/Dump1090-OpenLayers3-html). For the full picture, please take a look at the documentation and repository from [alkissack's](https://github.com/alkissack/Dump1090-OpenLayers3-html), as I tend to clean up some files and comments that are unnecessary in my opinion.

### This project provides default dark scheme for the dump1090 web interface. Also includes some new, ui-driven features.
#### Please keep in mind that this is bug heavy, pre-release project with experimental features. Currently developed (and compatible) with stock pi24 dump1090-mutabily with plan to support other dump1090 versions with broader `aircraft.json` data.

### Changelog
**15.03.22 - 0.13**
- new style for map controls
- migration to new `layerSwitcher` module
- layers moved to layers.js and refactored
- minor UI changes

**14.03.22 - 0.12a**
- range rings rewritten to OL6
- added historical max distance

**11.03.22 - 0.12**
- redesigned aircraft detailed data window, added icons for clarity
- initial migration to openlayers 6 for webgl goodies. For now working but buggy and with regression to some features.
- added lots of minor UI changes

**09.03.22 - Initial release**
- added basic dark theme to css
- added dark/light mode switch (the light mode currently is buggy)
- added openstreetmap dark layer to map canvas
- lots of UI changes and fixes to sidebar panel
- added some graphic indicators instead of numeric to aircraft table (age, rssi)
- removed floating aircraft info window
- aircraft info window is now binded to bottom of screen
- added photo preview from planespotters.net
- jquery upgraded to latest version
- added lucide icon library

![UI printscreen - initial release](https://github.com/l4red0/Dump1090-Dark-UI/blob/master/screen.png?raw=true)
![UI printscreen - initial release](https://github.com/l4red0/Dump1090-Dark-UI/blob/master/screen2.webp?raw=true)
> Initial release UI.

**Quote from original project description**
> Modifications to the OL3 html files (part of the dump1090-fa branch). The contents of public_html are a complete replacement to the webserver root directory on your dump1090-fa, or compatible, installation. Better to rename your existing html folder, and copy this one in (calling it as per the orignal). Set your options at the bottom of config.js, clear your browser cache and re-load your dump1090-fa page.

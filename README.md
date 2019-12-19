XHSW Crosshair switcher
=====

XHSW is a crosshair switcher for Team Fortress 2.
It supports different weapon settings, such as no primary, no secondary, and demoknight modes,
It also features a quick toggle for viewmodels (defaults to F).

Settings
-----
Edit the files xhsw_settings.cfg, xhsw_settings_spy.cfg, xhsw_settings_noprimary, xhsw_settings_nosecondary.cfg, xhsw_settings_demoknight.cfg, and xhsw_settings_engineer.cfg

The file xhsw_settings is executed first, anything you put in the other settings files will overwrite the defaults,
 you can use those files to make some specific colourschemes for whatever class you like.

The other files are made to be as hands-off as possible, You are not required to touch them.

- Spy appends "lastdisguise" to mwheel clicks, as personally I use mouse4/5 for weapon switching. this way you can quickchange your weapon while disguised. This can be changed in xhsw_settings_spy.cfg
- Spy reverses the melee and secondary (sapper) order, I don't play spy who I don't know what works best. Email me some feedback.
- Demoknight completely disables anything but melee (DeGroot mode)
- Engineer and Spy profiles exist, although I'd suggest you hotkey your spykit and build/destroy keys anyway.

Binds
-----
- 7 : toggles mannpower mode (claw)

Commands
-----
- xhsw_clear - Clears xhsw from the game session.
- xhsw_start - Starts xhsw at the
- xhsw_standard : standard 3-weapon profile
- xhsw_noprimary : disables primary weapon
- xhsw_nosecondary : disables secondary weapon
- xhsw_demoknight : disables primary and secondary weapon
- xhsw_engineer : enables the engineer profile
- xhsw_spy : enables the spy profile
- xhsw_next_setting : switches to the next profile (not a part of spy/engineer)
- xhsw_this_setting : reloads the current profile

Installation
-----
To install, copy all cfg files (prepended with xhsw_*) to the tf/cfg/ folder.
You can either edit your class config file and add "exec xhsw_start" or go into console in game and type "exec xhsw_start"


TODO
-----
- Add a Spy profile for switching the weapon order

Author
=====
Nattajerk

Support contact: nattakorps@gmail.com

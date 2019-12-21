XHSW Crosshair switcher
=====

XHSW is a crosshair switcher for Team Fortress 2.
It supports different weapon settings, such as no primary, no secondary, and demoknight modes.
Engineer and Spy modes are supported, as well as Mannpower.

Feature
-----
XHSW will change your crosshair based on what weapon you use. This makes it easier to tell what weapon you are using when using no viewmodels. XHSW is also a weapon switcher and adds a few features to your weapon set

- Spy has a secondary quick weapon switch bind. This way you can quickchange your weapon while disguised. This can be changed in xhsw_settings_spy.cfg
- Spy reverses the melee and secondary (sapper) order.
- Demoknight completely disables anything but melee (DeGroot mode)
- Spy and Engineer's extra weapons have profiles as well

Settings
-----
The user settings are in the files:
- xhsw_settings.cfg
- xhsw_settings_spy.cfg
- xhsw_settings_noprimary
- xhsw_settings_nosecondary.cfg
- xhsw_settings_demoknight.cfg
- xhsw_settings_engineer.cfg
- xhsw_settings_mannpower.cfg

The file xhsw_settings is executed first, anything you put in the other settings files files will take precedence. You can use those files to make some specific colourschemes for whatever class you like.

The other files are made to be as hands-off as possible, You are not required to touch them.

Binds
-----
- 7 : toggles mannpower mode (claw)
- 8 : enables the standard 3-weapon profile
- 9 : enables the demoknight profile
- 0 : enables the nosecondary profile
- \- : enables the noprimary profile
- = : enables the spy/engineer profile

Commands
-----
- xhsw_start - Starts xhsw
- xhsw_start_engineer - Starts xhsw with engineer profile
- xhsw_start_spy - Starts xhsw with spy profile
- xhsw_standard : standard 3-weapon profile
- xhsw_noprimary : disables primary weapon
- xhsw_nosecondary : disables secondary weapon
- xhsw_demoknight : disables primary and secondary weapon
- xhsw_engineer : enables the engineer profile
- xhsw_spy : enables the spy profile
- xhsw_mannpower : toggles mannpower mode
- xhsw_this_setting : reloads the current profile

Making your own profiles
-----
- Copy `xhsw_standard` to a new file
- initialize with `exec xhsw_init` in the class file or start file.
- make your own settings file and execute it xhsw


Installation
-----
To install, copy all cfg files (prepended with xhsw_*) to the steamapps\common\Team Fortress 2\tf\cfg folder.

In your class files, or autoexec.cfg, add the line
```
  exec xhsw_start
```

For engineer and spy profiles to start by default, in their class file (spy.cfg, engineer.cfg, or their analogues) add
```
  exec xhsw_start_engineer
```
or
```
  exec xhsw_start_spy
```
respective to that class, if desired.

Author
-----
Nattajerk

Steam URL: https://steamcommunity.com/id/nattajerk/

Support contact: nattakorps@gmail.com

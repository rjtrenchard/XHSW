# XHSW Crosshair switcher

XHSW is a crosshair and weapon switcher for Team Fortress 2.
It supports different weapon settings, such as no primary, no secondary, and demoknight modes. Profiles are available at the press of a button - or a console command if you like.


## Feature

XHSW will change your crosshair based on what weaponslot you have selected. This makes it easier to tell what weapon you are using when using no viewmodels. XHSW also adds a few features to your weapon set:

- Spy and Engineer's extra weapons have profiles
- Spy has a secondary quick weapon switch bind. This way you can quickchange your weapon naturally while disguised. This can be enabled or changed in xhsw_settings_spy.cfg and setting xhsw_upbind_disguise/downbind to a key.
- Spy reverses the melee and secondary (sapper) order. It will go Primary > Melee > Sapper > Disguise Kit
- Demoknight completely disables anything but melee (DeGroot mode), except with mannpower enabled.

## Installation

To install, copy all `*.cfg` files (prepended with xhsw_*) to the `...\steamapps\common\Team Fortress 2\tf\cfg` folder.

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

## Settings

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

## Binds

- 7 : toggles mannpower mode (claw)
- 8 : enables the standard 3-weapon profile
- 9 : enables the demoknight profile
- 0 : enables the nosecondary profile
- \- : enables the noprimary profile
- = : enables the spy/engineer profile (if xhsw_start_engineer and xhsw_start_spy are in the class cfg files)

## Commands

##### Starting XHSW
- xhsw_start - Starts xhsw
- xhsw_start_engineer - Starts xhsw with engineer profile
- xhsw_start_spy - Starts xhsw with spy profile
- xhsw_restart : reloads XHSW

##### Choosing a profile
- xhsw_standard : standard 3-weapon profile
- xhsw_noprimary : disables primary weapon
- xhsw_nosecondary : disables secondary weapon
- xhsw_demoknight : disables primary and secondary weapon
- xhsw_engineer : enables the engineer profile
- xhsw_spy : enables the spy profile
- xhsw_this_setting : reloads the current profile

##### Enabling Mannpower
- xhsw_mannpower : toggles mannpower mode

##### Weapon Commands
- xhsw_upbind : scrolls up one weapon
- xhsw_downbind : scrolls down one weapon
- xhsw_qswitch : uses last weapon
- xhsw_primary : switches to primary
- xhsw_secondary : switches to secondary
- xhsw_melee : switches to melee
- xhsw_sapper : switches to sapper (Spy)
- xhsw_build : switches to build (Engineer)
- xhsw_destroy : switches to destroy (Engineer)
- xhsw_claw : switches to claw (Mannpower)

##### Spy Commands

- xhsw_upbind_disguise : scrolls up between the primary, secondary, and melee weapons as natural
- xhsw_downbind_disguise : scrolls down between the primary, secondary, and melee weapons as natural


## Making your own profiles

Copy `xhsw_template.cfg` to a new file

Initialize with:
```
exec xhsw_init
```
in your class file or a new start file.

Follow the TODO's in the template and execute your new file.

## Author & Support

[Nattajerk](https://steamcommunity.com/id/nattajerk/)

Support: [email](mailto:nattakorps@gmail.com)

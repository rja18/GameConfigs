_Note to self: probably should move crosshair commands to settings config._
# Config
The game's launch options automatically executes [autoexec4by3.cfg](https://github.com/rja2006/GameConfigs/blob/main/CounterStrike/Configs/autoexec4by3.cfg), to overwrite it type "exec [name of file]" into the console.<br>Ensure "host_writeconfig" is at the end of the cfg file.
## Launch Options
Launch options excluding config executions:<br>
`-tickrate 128 +fps_max 0 -novid -nojoy`<br>
Current config executions:<br>
`+exec autoexec4by3.cfg +exec settings_config.cfg`
## Sensitivities
_Updated for CS2 (30/9/2023)._
16:9 sensitivity: 10<br>4:3 sensitivity: 6.5<br>Zoom sensitivity: 0.75
## General Settings
General settings (not binds, viewmodel or crosshair) are in the [settings_config.cfg](https://github.com/rja2006/GameConfigs/blob/main/CounterStrike/Configs/settings_config.cfg) file.
## Graphics Settings
Graphics settings for each aspect ratio (CSGO) are in the [csgo_graphics_settings.md](https://github.com/rja2006/GameConfigs/blob/main/CounterStrike/csgo_graphics_settings.md) file.<br>**_They might need updating for CS2 after it releases._** ([CS2 settings](https://github.com/rja2006/GameConfigs/blob/main/CounterStrike/cs2_graphics_settings.md))
## Crosshair
![Screenshot of crosshair](https://github.com/rja2006/GameConfigs/blob/main/CounterStrike/Images/crosshair_screenshot.jpg)<br>
_Crosshair code: CSGO-f7kaq-6qwsj-LxjQe-HOsNc-LFR7B_
### Settings configuration:
_[Text file of commands list](https://github.com/rja2006/GameConfigs/blob/main/CounterStrike/Raw%20Text/crosshair_commands.txt)._<br>
**Crosshair Style**: _Classic static_   (_cl\_crosshairstyle "4"_)<br>
**Center Dot**: _No_   (_cl\_crosshairdot "0"_)<br>
**Length**: _2.0_   (_cl\_crosshairsize "2"_)<br>
**Thickness**: _0.2_   (_cl\_crosshairthickness "0.2"_)<br>
**Gap**: _-1.4_   (_cl\_crosshairgap "-1.4"_)<br>
**Outline**: _Off_   (_cl\_crosshair\_drawoutline "0"_)<br>
**Red**: _0_   (_cl\_crosshaircolor\_r "0"_)<br>
**Green**: _255_   (_cl\_crosshaircolor\_g "255"_)<br>
**Blue**: _0_   (_cl\_crosshaircolor\_b "0"_)<br>
**Alpha**: _Enabled_   (_cl\_crosshairusealpha "1"_)<br>
**Alpha Value**: _255_   (_cl\_crosshairalpha "255"_)<br>
**T Style**: _No_   (_cl\_crosshair\_t "0"_)<br>
**Deployed Weapon Gap**: _No_   (_cl\_crosshairgap\_useweaponvalue "0"_)<br>
**Show Player Crosshairs**: _Everyone_   (_cl\_show\_observer\_crosshair "2"_)<br>
**Show my crosshair when spectating bots**: _Always_<br>
### Misc commands:
_cl\_crosshaircolor "5"_<br>
_cl\_crosshair\_sniper\_width "1"_<br>

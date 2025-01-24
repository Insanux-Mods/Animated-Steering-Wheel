<h1 align="center">
Animated Steering Wheel For ETS2 / TruckersMP
</h1>

![GitHub Downloads (all assets, all releases)](https://img.shields.io/github/downloads/Insanux-Mods/Animated-Steering-Wheel/total?style=flat-square&color=%2300CB9B)
![GitHub Downloads (all assets, latest release)](https://img.shields.io/github/downloads/Insanux-Mods/Animated-Steering-Wheel/latest/total?style=flat-square&color=%2300CB9B)


## Installation Guide:
1. Open Steam
2. Close Euro Truck Simulator 2
3. Right click on ETS2 and go to `Manage > Browse Local Files` 
4. Open `Bin > win_x64`
5. Open the `plugins` folder.  If there is no `plugins` folder, create one
6. Open the .zip from the [Latest Release](https://github.com/Insanux-Mods/Animated-Steering-Wheel/releases/latest) of the plugin, extract everything to the `plugins` folder
7. Load Euro Truck Simulator 2 / TruckersMP

![](https://github.com/Insanux-Mods/Animated-Steering-Wheel/blob/main/install.gif)

Youtube Guide: https://www.youtube.com/watch?v=QMbzdzJd_lw

# Correct Folder Structure
```python
<game_install_location>/bin/win_x64/
│   eurotrucks2.exe
│   ...
│
└───plugins # Create the folder, if it does not exist
    │   Animated-Steering-Wheel.dll # copy from release
    └── Animated-Steering-Wheel.txt # copy from release
```

## Notes/Info:
- Wheel Speed, Driving Position and Parked Position Can All Be Changed Inside `\plugins\Animated-Steering-Wheel.txt`
- After Editing Anything Inside `\plugins\Animated-Steering-Wheel.txt` Turn Off The Electric/Engine Then Open Console And Type `sdk reload`
- This Plugin Does **Not** Work Correctly On TMP AV, Skoda And Bus
- This Plugin Does **Not** Support ATS

## Config File:
**Note:** As of the 1.50 plugin update you can now just adjust the wheel from the F4 menu adjusting the config manually is no longer needed
- The Config File Is At `\plugins\Animated-Steering-Wheel.txt`
- Inside The Config File You Will Have 4 Lines: `engine_off`, `engine_on`, `front_back`, `speed`
  - `engine_off` - The Wheel Position When The Electric Is **Off** *Accepts Any Value Between `-0.2` - `0.8`*
  - `engine_on` - The Wheel Position When The Electric Is **On** *Accepts Any Value Between `-0.2` - `0.8`*
  - `front_back` - How Close / Far The Wheel Is When The Electric Is **On** *Accepts Any Value [scs max: `-0.5` to `0.5`]*
  - `speed` - How Quickly The Wheel Moves From On To Off / Off To On [Higher Number The Slower It Moves]
```json
{
    "engine_off": 0.8,
    "engine_on": 0.0,
    "front_back": 0.0,
    "speed": 250
}
```
 
## Need Help?
- If You Have Any Problems With This Plugin You Can Contact [**Insanux Support**](https://discord.gg/insanux) And Head To The [**ask-for-help** Channel](https://discord.com/channels/737213060233822269/1032370614738100324)
- Make Sure You Include Your `game.log.txt` File From `Documents/Euro Truck Simulator 2` And Explain Your Problem

## Credits:
- [Roccovax](https://github.com/dariowouters)
- [InsaneCallum](https://github.com/Callum-Bell)
- [Baldy09](https://github.com/Baldywaldy09)

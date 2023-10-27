# Animated Steering Wheel For ETS2 / TruckersMP

## Installation Guide:
1. Open Steam
2. Close Euro Truck Simulator 2
3. Rick click on ETS2 and go to `Manage > Browse Local Files` 
4. Open `Bin > win_x64`
5. Open the `plugins` folder.  If there is no `plugins` folder, create one
6. Open the .zip from the [Latest Release](https://github.com/Insanux-Mods/Animated-Steering-Wheel/releases/latest) of the plugin, extract everything to the `plugins` folder
7. Load Euro Truck Simulator 2 / TruckersMP

![](https://github.com/Insanux-Mods/Animated-Steering-Wheel/blob/main/install.gif)

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
- The Config File Is At `\plugins\Animated-Steering-Wheel.txt`
- Inside The Config File You Will Have 3 Lines: `speed`, `engine_on` and `engine_off`
  - `speed` - How Quickly The Wheel Moves From On To Off / Off To On [Higher Number The Slower It Moves]
  - `engine_on` - The Wheel Position When The Electric Is **On** *Accepts Any Value Between `-0.2` - `0.8`*
  - `engine_off` - The Wheel Position When The Electric IS **Off** *Accepts Any Value Between `-0.2` - `0.8`*
```json
{
	"speed": 250,
	"engine_on": 0.0,
	"engine_off": 0.8
}
```
 
## Need Help?
- If You Have Any Problems With This Plugin You Can Contact [**Insanux Support**](https://discord.gg/insanux) And Head To The [**ask-for-help** Channel](https://discord.com/channels/737213060233822269/1032370614738100324)
- Make Sure You Include Your `game.log.txt` File From `Documents/Euro Truck Simulator 2` And Explain Your Problem

## Credits:
- [Roccovax](https://github.com/dariowouters)
- [InsaneCallum](https://github.com/Callum-Bell)
- [Baldy09](https://github.com/Baldywaldy09)

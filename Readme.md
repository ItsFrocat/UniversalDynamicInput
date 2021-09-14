# Universal Dynamic Input
[Wiki](https://github.com/Venomalia/UniversalDynamicInput/wiki) | [Discord](https://discord.gg/vEQYMPxgSR) | [Changelog](https://github.com/Venomalia/UniversalDynamicInput/blob/main/Changelog.md) | [DynamicInputTextureCreator Tool](https://github.com/Venomalia/DolphinDynamicInputTextureCreator/releases) | [Dolphin Forum](https://forums.dolphin-emu.org/Thread-universal-dynamic-input-texture-pack)

**UniversalDynamicInput** is a custom button package for [Dolphin emulator](https://dolphin-emu.org/). It uses [dynamic input textures](https://forums.dolphin-emu.org/Thread-introducing-dynamic-input-textures-a-new-feature-for-controller-icons) to create custom buttons in real time. Unlike traditional button packages, you can change the control settings at any time and the in-game textures will change. There are also no problems with texture packages. Take a look at this [Dolphin progress report](https://dolphin-emu.org/blog/2020/12/10/dolphin-progress-report-october-2020/#50-12801-dynamic-input-textures-by-iwubcode) for more info.

### [Download](https://github.com/Venomalia/UniversalDynamicInput/releases)

##  [Installation](https://github.com/Venomalia/UniversalDynamicInput/wiki/Installation):
- Dolphin 5.0-13603 or [newer](https://de.dolphin-emu.org/download/).
- The latest [release](https://github.com/Venomalia/UniversalDynamicInput/releases) of UniversalDynamicInput.
- At least one [Supported Game](https://github.com/Venomalia/UniversalDynamicInput/wiki/Supported-games).
- At least one [Supported Device](https://github.com/Venomalia/UniversalDynamicInput/wiki/Supported-Inputs-Devices).
- Place the **DynamicInputTextures** folder into Dolphin's **Load** directory:
  - Standard directory: `%UserName%\Documents\Dolphin Emulator\Load`
  - Portable mode (portable.txt): `DolphinDirectory\User\Load`
- Open Dolphin, enter Graphics > Advanced tab > Check `Load Custom Textures`.

As soon as you start a [supported game](https://github.com/Venomalia/UniversalDynamicInput/wiki/Supported-games), Dolphin should generate and load the textures.

If it does not work, try this [guide](https://github.com/Venomalia/UniversalDynamicInput/wiki/Problem-solving).

##  Screenshots:
![Image1](https://i.imgur.com/WIxE3IZ.jpg "Image1")
![Image2](https://i.imgur.com/3pcxh5P.jpg "Image2")

## [Supported Games](https://github.com/Venomalia/UniversalDynamicInput/wiki/Supported-games)
## [Supported Devices](https://github.com/Venomalia/UniversalDynamicInput/wiki/Supported-Inputs-Devices)

## FAQ:
#### Does it work with texture packs?
Yes, there are no known problems.

### Does it work with netplay?
Yes, but there can be problems with wii games because only player 1 can use Wii Remote 1.

### The textures are for the wrong controller
Try the [DevicesTextureChanger](https://github.com/Venomalia/UniversalDynamicInput/wiki/Supported-Inputs-Devices#devicestexturechanger).

### Do you accept game suggestions?
Yes, but I need the [texture dumps](https://github.com/Venomalia/UniversalDynamicInput/wiki/Dumping-Textures) to implement it. Dumps can be sent to me via [Discord](https://discord.gg/vEQYMPxgSR).

### How to create a pack?
Try this [guide](https://github.com/Venomalia/UniversalDynamicInput/wiki/Create-a-Package).

### Where can I ask questions?
You can use [Discord](https://discord.gg/vEQYMPxgSR) or [this thread](https://forums.dolphin-emu.org/Thread-universal-dynamic-input-texture-pack) in the Dolphin forum.

## Credits:
### [Contributors](https://github.com/Venomalia/UniversalDynamicInput/graphs/contributors)

### Special thanks:
[iwubcode](https://github.com/iwubcode) for this great feature and to all helpers for beta-tests, feedback, texture-dumps and other improvements.

Super Mario Galaxy [1](https://forums.dolphin-emu.org/Thread-super-mario-galaxy-1-hd-texture-mod) & [2](https://forums.dolphin-emu.org/Thread-super-mario-galaxy-2-hd-texture-mod) UI assets created by **Razius**.

Phantasy Star Online 1 & 2 UI assets created by [LutheeMajestic](https://forums.dolphin-emu.org/Thread-phantasy-star-online-episode-i-ii-hd-ui-project).

## License: CC BY 4.0
[![CC BY 4.0](https://i.creativecommons.org/l/by/4.0/88x31.png)](https://creativecommons.org/licenses/by/4.0/)

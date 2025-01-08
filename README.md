# **ATVMapHolder**
#### This mod adds map holders that allow you to attach digital map to the ATV.

## Preview
![Preview](https://github.com/Acitulen/ATVMapHolder/blob/main/ATVMapHolderPreview.png?raw=true)

## Features
- Map holders can be ordered through the in-game shop in tools section.
- Map holders can be attached to an ATV with a touch and detached by grabbing.
- Digital map can be attached to map holders with a touch and detached by grabbing.  
*They can be attached and detatched in any order.
- Map holders are compatible with both original and modded digital map v2.

## Manual instalation guide.

<details>
<summary>Install unreal shimloader</summary>

1. Copy `dwmapi.dll` into the `GAME/Binaries/Win64` directory. Its new path should be `GAME/Binaries/Win64/dwmapi.dll`.
2. Copy the contents of the `UE4SS` folder in the package into `GAME/Binaries/Win64`.

`GAME/Binaries/Win64` should now contain the following *new* files and folders:
- `GAME-Win64-Shipping.exe`
- `ue4ss.dll`
- `UE4SS-settings.ini`
- `dwmapi.dll` ← *This is the unreal-shimloader binary. It will load UE4SS for you.*
- `Mods/`
</details>

<details>
<summary>Install Fusion</summary>

1. Copy `everything (except mod floader)` from the archive to `GAME/Binaries/Win64/Mods/NynrahGhost-Fusion` directory.  
*you have to create `NynrahGhost-Fusion` floader manually.
2. Copy the contents of the `mod` folder in `GAME/Binaries/Win64/Mods/NynrahGhost-Fusion` directory.
3. Create floader `Bina` in `GAME` directory
4. Make an empty `mods.yml` file in `GAME/Bina` directory.
5. Run `Fusion.exe` from `GAME/Binaries/Win64/Mods/NynrahGhost-Fusion` directory.
</details>
<details>

<summary>Install ATVMapHolder</summary>

1. Copy `ATVMapHolder.pak` from the `pak` floader to `GAME/Content/Paks/LogicMods` directory. 
2. Run `Fusion.exe` from `GAME/Binaries/Win64/Mods/NynrahGhost-Fusion` directory.
</details>

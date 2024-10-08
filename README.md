# **ATVMapHolder**
#### This mod allows you to attach digital map to the ATV.

## Preview
![Preview](https://github.com/Acitulen/ATVMapHolder/blob/main/ATVMapHolderPreview.gif?raw=true)

## Features
- Displays the player's direction.
- Displays entities.
- Different colors of the radar blips. (radar colors module required).
- Different entity scanning speed. (according to radar speed module upgrade).
- Customizable map elements.

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
<summary>Install VoidMod-2.0.0</summary>

1. Copy `VoidMod2.pak` from the pak floader to `GAME/Content/Paks/LogicMods` directory. 
</details>

<details>

<details>
<summary>Install Fusion</summary>

1. Copy `everything (except mod floader)` from the archive to `GAME/Binaries/Win64/Mods/NynrahGhost-Fusion` directory.  
*you have to create `NynrahGhost-Fusion` floader manually.
2. Copy the contents of the `mod` folder in `GAME/Binaries/Win64/Mods/NynrahGhost-Fusion` directory.
3. Create floader `Bina` in `GAME` directory
4. Make an empty `mods.yml` file in `GAME/Bina` directory.
5. Run `Fusion.exe` from `GAME/Binaries/Win64/Mods/NynrahGhost-Fusion` directory.
</details>

<summary>Install ATVMapHolder</summary>

1. Copy `ATVMapHolder.pak` from the `pak` floader to `GAME/Content/Paks/LogicMods` directory. 
2. Copy the contents of the `mod` folder in `GAME/Binaries/Win64/Mods/Acitulen-ATVMapHolder` directory.
*you have to create 'Acitulen-ATVMapHolder' floader manually.
3. Run `Fusion.exe` from `GAME/Binaries/Win64/Mods/NynrahGhost-Fusion` directory.
</details>

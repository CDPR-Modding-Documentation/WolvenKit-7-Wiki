# Texture Editing

## The General Workflow

Texture Editing in Wolvenkit is straightforward:

1.  **Browse the Asset Browser** - TextureCache for the desired texture. Click "add to mod/dlc". Texture files are [**raw files**](https://github.com/Traderain/Wolven-kit/wiki/T5\_Project-structure) and will be added to the **/Raw folder** in your mod or dlc project. Depending on your [settings](https://github.com/Traderain/Wolven-kit/wiki/T1\_Getting-Started), the texture will be exported as .tga, .png, .jpg or .dds.

    > Full Guide: [The Asset Browser](https://github.com/Traderain/Wolven-kit/wiki/Asset-Browser#Adding-Game-Assets-to-your-mod-Textures)

![Asset Browser Textures](https://github.com/Traderain/Wolven-kit/wiki/assets/0.7\_asset\_browser\_textures.jpg)

1. **Edit your Texture in GIMP or Photoshop etc** - Double click on the file in the **/Raw folder**, it will open the texture in your preferred App.
2.  **Use the Import Utility in WolvenKit** - to convert the raw texture (.tga etc) to the Witcher 3 file format (.xbm). Click "Use Mod Files" and "Auto Fill Texture Groups" if applicable and then click "Import". WolvenKit will automatically import the raw texture to .xbm. The imported files are then automatically placed into the **/Uncooked folder** in your mod project.

    > Full Guide: [Import Utility](https://github.com/Traderain/Wolven-kit/wiki/Import-Utility)

![Asset Browser Textures](https://github.com/Traderain/Wolven-kit/wiki/assets/0.7\_import.jpg)

1.  Click "Pack Mod".

    > See [The WolvenKit Modding Workflow](https://github.com/Traderain/Wolven-kit/wiki/T5\_Project-structure)

## Exceptions: Icons, Map Tiles and Speedtree Textures

> Icons (png), Map tiles (jpg) and certain foliage textures (dds) do not need to be imported to xbm before packing a mod. WolvenKit will instead place these files directly into the **/Uncooked folder** of your mod project. From there, edit and pack the mod directly **(skip step 3!)**.

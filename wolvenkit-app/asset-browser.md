# Asset Browser

The Asset Browser is the main tool for adding files from the game (or another mod) to your mod project.

Open the Asset Browser either via the File Menu or by clicking on the inspect button on the Sidebar.

![Open Asset Browser](https://github.com/Traderain/Wolven-kit/wiki/assets/Inked0.7\_asset\_browser\_open\_LI.jpg)

## The Main View

The Asset Browser opens in a new window and lets you look through the game's assets (Files, Textures, Models, etc). There are five different categories of assets: 1. Bundled Files: These are all files that are compressed inside a _Bundle_ (e.g. blob0.bundle) in the game's data. 2. Collision Cache: Contains specific files with collision data in raw format (e.g. apb). 3. Sound Cache: Contains the audio files of the game. 4. Speech: Contains the speech files of the game. 5. Texture Cache: Contains all textures in raw format (e.g. tga). HINT: You can specify the extension to export in the settings.

![Asset Browser Start Window](https://github.com/Traderain/Wolven-kit/wiki/assets/0.7\_asset\_browser0.jpg)

The asset browser works like a file system: You can navigate through the game's folders like in Windows Explorer.

* Double click on a file to add it to the list of files to add (displayed on the right-hand side)
* Right click on a folder and you have the option to "select all files of folder"
* To add the selected files to your project as mod or dlc file click either **Add to Mod** or **Add to DLC**.

> Selecting "Uncook" or "Export" will attempt to uncook (this is usefull for meshes) or export (again, usefull for meshes) the selected file. Uncooked files will be placed into the **/Uncooked folder**. Exported files will be placed into the **/Raw folder** in your mod or dlc project.
>
> Different game files will be added to different folders in your mod project depending on the _kind_ of files they are. See [here](https://github.com/Traderain/Wolven-kit/wiki/T5\_Project-structure) for an explanation of the general modding workflow in Witcher 3.

## Adding Game Assets to your mod: Bundled Files

Bundle files are [**cooked files**](../help/glossary.md) and will be added to the **/Cooked folder** in your mod or dlc project.

![Asset Browser Bundle](https://github.com/Traderain/Wolven-kit/wiki/assets/0.7\_asset\_browser\_bundle.jpg)

## Adding Game Assets to your mod: Textures

Texture files are [**raw files**](../help/glossary.md) and will be added to the **/Raw folder** in your mod or dlc project.

These raw files will first have to be **imported** into the witcher 3 xbm file format before you can install your mod. The imported files are then automatically placed into the **/Uncooked folder**

> For an introduction to importing in WolvenKit with the Import Utility see here: [Import Utility](import-utility.md)
>
> Exception! Icons (png), certain minimap tiles (jpg) and foliage textures (dds) are not raw files and do not have to be imported to xbm but will be added directly as .png/jpg/dds to the [**uncooked folder**](../help/glossary.md). WolvenKit handles these execptions automatically.

![Asset Browser Textures](https://github.com/Traderain/Wolven-kit/wiki/assets/0.7\_asset\_browser\_textures.jpg)

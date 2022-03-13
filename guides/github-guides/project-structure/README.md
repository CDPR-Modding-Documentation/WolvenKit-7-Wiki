# Project Structure

## Raw-Uncooked-Cooked

The Witcher 3 modding workflow can sometimes be complicated, but here is a quick rundown of the major concepts.

> The most important thing to understand is that the game's engine in most cases uses **custom file formats** that first have to be created ("imported into the engine") from more well-known file types. 1. **Raw files** are all files that first need to be imported into a Witcher 3 RedEngine file format. See here for more information: [Import Utility](../../../wolvenkit-app/import-utility.md) Files in this category include:
>
> * Textures: tga, png, dds .etc
> * Meshes: fbx
> * Apex cloth files: .apb
>   1. **Uncooked files** are all files that are _converted_ from raw file types into Witcher 3's special file formats or otherwise specifically created from the engine: Uncooked files have a number of features, the most important being that they are often large in size and contain _raw_ data, such as the raw pixels of the texture.
> * Textures: .xbm, .w2cube, .texarray
> * Meshes: .w2mesh
> * Apex cloth files: .redcloth, reddest
> * And many more uncooked files that are created by the Engine
>   1. **Cooked files** are created from uncooked files via the _cook_ operation of wcc\_lite (the command line Witcher 3 official modding tools, which WolvenKit utilizes). See here for more information: **wcc\_lite commands \<missing link>**. Cooked files have the same ending as uncooked files and it can be confusing to keep them apart. Cooked files are _usually_ smaller in size than uncooked files.&#x20;
> * Textures: .xbm, .w2cube, .texarray
> * Meshes: .w2mesh
> * Apex cloth files: .redcloth, reddest
> * And many more cooked files that are created by wcc\_lite
>
> WolvenKit mirrors these steps in the Witcher 3 modding workflow in the Project structure to the left: DLC and Mods have **Cooked** and **Uncooked** folders for manual placement of files if you are already familiar with the process,. Otherwise WolvenKit's modding workflow does this for you.

## Packing a Mod in WolvenKit \<originally empty>

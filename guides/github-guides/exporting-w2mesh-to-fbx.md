# Exporting W2MESH to FBX

## INTRODUCTION

Currently implemented fbx uses FBX SDK, so it creates fbx scene and than exports this scene using native export SDK function. It has a limit to one animation, the one actually played on your render window (may be changed in the future). Export function creates two files, one binary and one ascii. An ascii file has additional extension to your original file name, e.g. yourfile.fbx\_ascii.fbx. Please note, that for some reasons some animation will be played upside down. We are investigating how to fix that problem, looks like Red Engine has some flag to set proper axis directions of their graphic files during render. We don't know it yet.

## PREPARATION

To export mesh with animation you have to have mesh, corresponding material and texture files, rig and animations with buffers included in your mod.

## INSTRUCTIONS

1. Start your Fast Render window from mod explorer context menu, right click on w2mesh file and select Fast Render.

![Imgur](https://i.imgur.com/YTbtqZK.png)

Your mesh will load into render window with textures. You have to have all texture files already loaded to your mod explorer.

![Imgur](https://i.imgur.com/7BV8ddT.png)

From that moment you may export your mesh to fbx. Choose Export option from render window context menu and select Fbx Mesh as export type. Your export file will include only mesh with materials and textures.

![Imgur](https://i.imgur.com/xj3jX2s.png)

1. Load rig file, choose load rig from render window context menu. To check if rig was properly loaded from context menu select View/Skeleton.

![Imgur](https://i.imgur.com/bFBURKA.png)

If you export you model at this moment you will have mesh, materials, textures, bones and bone weights deforming mesh in your export file.

1.  Load animations, choose load anims from context menu and select anim file. Please be sure to load correct file.

    After your anim file is loaded you will see in output window a message how many animations were loaded.

![Imgur](https://i.imgur.com/wPfjrsP.png)

Also your context menu will be filled with animations available for playing.

![Imgur](https://i.imgur.com/q1ciWJr.png)

1. Start playing some animation. This animation will be exported with fbx file.
2. To export fbx select Export from context menu and choose fbx as file extension. Two files will be created.

## IMPORT TO BLENDER

I don't have any $ tools so I use blender. 1. To properly import file to blender and probably to any other tool that supports fbx import you need to correctly setup few options on import. 2. Scale, for some reasons witcher meshes are rescaled down to very small model, to have it correctly visible choose global scale multiplicator of 100. ![Imgur](https://i.imgur.com/V3fQrOS.png)

1. Bones (Armature in blender), you need to setup correct axis for bones, X for primary bone and Y for secondary bone axis.

![Imgur](https://i.imgur.com/UKdsPt4.png)

Default options are diffrent so be carefull.

1. If everything went well you should see your model with animation at your scene:

![Imgur](https://i.imgur.com/W9hosHM.png)

Now you know what to do :).

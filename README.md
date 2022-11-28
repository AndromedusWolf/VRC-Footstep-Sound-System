# VRC-Footstep-Sound-System

## Overview
This is a system that allows you to quickly and easily add sounds to a player's footsteps when walking on a surface. For example, you can have a player make wooden floor footstep sounds when walking on a wooden floor.

This is being made free to use by the community and you may alter and improve the package as you wish. All I ask is that, if you alter the package and wish to distribute it, that you do so freely. There is no need to credit me, you may do so if you wish however.


## Dependencies
It is VERY important that you have [Udonsharp](https://github.com/vrchat-community/UdonSharp) downloaded already before downloading this package! The Footstep Sound System package won't work without it!


## Set-Up Footstep Sound System
1. Once you've imported or setup the Udonsharp package, import the Footstep Sound System package into Unity.
2. Open the Footstep Sound System folder and drag out the prefab
![Desktop Screenshot 2022 11 281 - 00 42 29 76](https://user-images.githubusercontent.com/99851805/204312024-f144c8a8-2dea-4da7-b77a-bcd1b90ff944.png)
3. Once you've done that, you are largely done! All you have to do now is assign Audio Sources to the surfaces that will be walked on.


## Set-Up Audio Sources
(All steps will refer to the image included below)
1. Ensure that the surface to be walked on has a collider attached to it. (Circled in blue)
2. Add an Audio Source to the surface. Do this by scrolling to the bottom of the inspector, clicking "Add Component" and picking Audio Source. (Circled in red)
3. Assign an audio clip to the AudioClip field of the Audio Source. (Circled in yellow)
*Note: For best results, choose an audio clip that is short (Like roughly one second long) and loops seamlessly
4. Ensure none of the checkboxes are marked. (Circled in magenta), unless you need them marked, in that case, go ahead, I won't stop you.
![Desktop Screenshot 2022 11 28 - 00 42 29 761](https://user-images.githubusercontent.com/99851805/204313923-472ffca8-7e8a-484b-be0c-e64d581e9a11.png)

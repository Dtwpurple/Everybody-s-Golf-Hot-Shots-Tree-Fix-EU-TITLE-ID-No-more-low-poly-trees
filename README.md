Must be using a hacked/modded switch with atmosphere support. 

If you want the same frames im getting you must overclock the switch. Cpu 1963. Gpu 1228. Mem 2133

To install just extract folder into root of switch sdcard.

<img width="1527" height="625" alt="{AF3D6FBA-7C55-4917-A47E-F26C6E9A797E}" src="https://github.com/user-attachments/assets/bf40698f-f224-4e8b-95a9-221ddc50ec7a" />

Im too lazy to put a before picture but here is an after. You can see all the trees are no longer low poly. Whats awesome about this is that they all sway with the wind now. the low poly ones didnt. 
 NEWEST UPDATE INFO:
 Shadowdistance increased which also increases the light distance so less pop-in.
-
antialiasing at 8
-
anisotropic filtering at 16
-
optimized settings so it runs well even tho we added all this shit. it runs better than the last patch.
-
When moving shadowdistance to max it also forces the raindrop shader thing to render at the same distance as the shadows.
-
^ Which causes big groups of raindrops hitting the ground to look like they are moving up because of how fast they come down at 45-50fps. Lock it to 30 to mitigate it.
-
had to reupload 421 because I forgot the new boot.config which changes the following
-
enabled gpu multithreading option
-
increases nvn gpu firmware memory to 256 instead of 32
I have noticed very few things have banding now. i cant figure out a way to fix this sorry, tried for hours. Unfortunately the shadow distance has a baked in limit. so even trying to max it out like the trees has no effect. this is the best we get boys.

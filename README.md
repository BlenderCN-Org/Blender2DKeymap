# Blender2DKeymap
A keymap close to 2D industry standards for blender 2.8


-------------------------------------------------

Installation instructions:

From the settings window, in the keymap section choose "import keymap" and load the .py file.
To setup your interface as in the startup file, open the .blend file with blender and choose "File>Save Startup File".

Startup file look:



![Imgur](https://i.imgur.com/j1cZ6SB.png)

-------------------------------------------------


I have been working on a 2D friendly keymap, and I wanted to submit it for feedback.

The idea behind this is to make blender and Grease Pencil a more welcoming experience for people who come from a 2D background, and to give them some shortcuts that will stay close to their expectations. I have been using it quite a bit and while I'm still always adding stuff and tweaking, I think I can submit it so people can tell me what they would like to find in something like this.

Make your 2D artist friend try this keymap and let me know!

The global layout is very reminiscent of habits people will have developped in Adobe softwares such as photoshop, flash and after FX. I think there is still a lot to add but I hope it's a good starting point.

Here are some of the main features:

* Pan With Space : Staple of 2D softwares, you can now pan with space, zoom with space+ctrl, dezoom with space+ctrl+alt, and rotate the view with left click+alt.

* play with Return : to easily play your animation now that space is used.

* ctrl+left click for lasso everywhere : no matter the mode, select defaults to lasso, and box select in the dope sheet and outliner. Box select with ctrl+alt.

* ctrl+A selects all, ctrl+D unselects all.

* for grease pencil objects; B for draw mode, E for edit mode, S for sculpt, Esc always brings back to Object Mode, and Tab brings up pie menu. Keys for modes because in 2D, modes are tools.

* Same sort of things for the sculpt mesh tools because these are the more "traditional artist" modes and they go hand in hand: E for edit mode, S for sculpt, and B for texture paint.

* Arrows to move strokes in increments (this one is still buggy because of issues with blender, I'm waiting to get a response)

* F6 creates duplicate keyframe, F7 blank keyframe

* relevant first letter shortcuts for sculpt tools that are easy to remember (visible from hovering the tools)

* right click erases grease pencil and inverts tool in sculpt

* double click selects linked

* A for add menu

* alt+right click for project strokes menu, alt+shift+right click for GP lock axis 

* Create GP interpolation from any edit mode with ctrl+shift+E

* Since this is based on AZERTY layouts, "," and ";" change frames, ":" and "!" go from key to key to easily flip drawings

* Move objects and keys with a right click tweak to avoid conflict with selection and tools

* G for Grab tool, R for rotate tool, Q for scale (S is taken by Scuplt)

* Right click menus on click action to free up right click tweaks.


Many other improvements here and there.



I'm not very familiar with Github but here is a repository I've set up that also includes a startup file with a good GreasePencil setup.

Please let me know if you would like to see some improvements or if that helps you feel like you're doing 2D, and if you would like to see something like that in the official blender release.

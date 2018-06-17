# script-tools

This is an ongoing collection of useful one-off C# scripts that I have created for Unity, including example scenes.

-------------------

AnimSpriteController
=======

![gif](https://imgur.com/Ol4JuGC.gif)

*AnimSpriteController* allows the user to implement a sequence of any number of sprite textures as an animation. 
Useful for custom animations exported from something like After Effects, which otherwise couldn't be done within Unity.

-------------------

CustomEditorCamera
=======

![gif](https://imgur.com/ADkJXaN.gif)

*CustomEditorCamera* is designed to be placed on the Main Camera, allowing for control similar to a 3D editing package.
Additionally, the view will center on any objects selected with a mouse click. Click any non-collision area to de-select.

Note that currently this requires the added step of manually creating a "Selected" Tag in the project.

- Rotate/Orbit: Drag right-mouse button
- Translate: Drag middle-mouse button
- Zoom: Mouse scroll wheel
- Zoom (smoothly): Ctrl + Alt + middle-mouse

-------------------

LightTrigger
=======

![gif](https://imgur.com/kFUpzft.gif)

*LightTrigger* works with a trigger volume around an object of interest, activating a camera light only when it enters that volume.
The example scene should show how this simple script can be set up and used.

-------------------

TriggerToClick
=======

![gif](https://imgur.com/IeYO9lD.gif)

*TriggerToClick* is specifically for activating On Click events in a World Space Unity UI button with a trigger volume attached.
Useful for creating VR/AR user interfaces.



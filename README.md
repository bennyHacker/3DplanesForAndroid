# 3D Planes For Android
Player vs 3 point planes for android

Thanks for checking out my sketch! 

This program runs very similar to my older version for desktop.

Here are the instructions:

- move player by tapping and holding left side of screen (a joystick icon will appear)
- pivot camera by tapping and holding right side of screen
- open keyboard by tapping the keyboard icon (keyboard closes normally by pressing 'back' on your device)
- jump by tapping the person leaping icon
- New! switch firstPerson/thirdPerson by pressing the camera icon
- New! grab ball by tapping interact button (appears when cursor hovering ball) (first person only)
- create a shape by tapping the box or "build" icon
- screen works best when tilted on its side!


In the older version you just had to tap a number on the keyboard to generate a shape

In this version it's a little more complicated

Under normal conditions, the build tool won't actually do anything.
In order to get it to work, you must have a number input in the keyboard

Pressing "go" or "send" on the keyboard will reset your input and cause it to not work

here are the possible inputs:

- 4 : generate bridge flush with feet
- 5 : generate a higher bridge
- 6 : generate a big box
- 7 : generate a big ramp
- 8 : generate a rotating bridge (broken as of version 1.0)
- 9 : generate a ball
- 0 : New! generate a cylinder
- p : New! generate an AABB (axis aligned bounding box)

If you see clipping, that is due to a bug with the camera and not the player collision

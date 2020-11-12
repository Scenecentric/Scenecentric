////////////////////////////////////////////////////////////////////////////////////////////////

                       INSTRUCTIONS

////////////////////////////////////////////////////////////////////////////////////////////////

ADDING SPRITES

Click the image icon (small landscape icon) and then click again inside the Stage. A placeholder will appear. Right-click inside the placeholder and choose an image from your computer.

ANIMATING SPRITES

You can animate a sprite using the Timeline. Using the Timeline, click the last frame of a Sprite. Back to the Stage, change the Sprite's position and click the Play button.

To add a keyframe to a sprite, select the position to add a new keyframe and click the "insert keyframe" icon located in the icons bar on top.

ADDING TEXT

Click the T icon to add a text to the Stage. Then use the Properties window to type a text, change its color, size, etc.

RESIZING THE STAGE

Click the Resize icon (small diagonal arrow) located in the icons bar on top.

////////////////////////////////////////////////////////////////////////////////////////////////

                    ADDING LINGO SCRIPTS

////////////////////////////////////////////////////////////////////////////////////////////////

To add a script to a sprite, select the sprite on the Stage and click the "Code" icon located in the icons bar on top.
You can also add scripts to the Script Layer in the Timeline. Just double click on a frame of the Script Layer.

WHAT HAS BEEN IMPLEMENTED SO FAR

MOUSE CLICK UP:

on mouseUp
go to frame X
end

on mouseUp
goToNetPage "http://www.apple.com/"
end

TEMPORARY INTERSECT (COLLISIONS) SOLUTION:

on intersect 4
go to frame 1
end
* This script must be applied to a sprite.

LOOP:

on enterFrame
go to the frame
end



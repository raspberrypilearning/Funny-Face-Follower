## Make a Mask

In this step, we're going to make individual sprites that will anchor to our eyes and nose to make a crazy cartoon face that follows yours around the screen!

--- task ---
Go into the **Costumes** tab for your current sprite and click the little paintbrush to create a new costume in the **Paint editor**.
Create a simple circle shape that will be the nose of your mask.

[[[generic-scratch-vector-mode]]]

--- /task ---

--- task ---
Create a new sprite by hovering over the little blue cat face at the bottom left, and then clicking on the paintbrush that appears. This will open the **Paint editor** again.

Make this sprite look like an eye by drawing one circle inside another and making them different colours.
--- /task ---

--- task ---
Go back to your nose sprite and copy the code there onto your new sprite by dragging it across to where your sprite is shown underneath the Stage. 

When you are over the sprite, you should see it wiggle to notify you that you can let go. Let go with your mouse and it will copy across to the new sprite.
``` blocks3
when gf clicked
turn video [on v]
set video transparency to (0)
forever
    go to x:(x coord of (nose v)::#0fbd8c)y:(y coord of (nose v)::#0fbd8c)
```
--- /task ---

--- task ---
Go back to your eye sprite now and remove the `turn video on`{:class="block3extensions"} and `set transparency to 0`{:class="block3extensions"} blocks from the code. 

Make sure you also change the two `coord of nose`{:class="block3extensions"} blocks to say `right eye`{:class="block3extensions"} in the drop down.
``` blocks3
when gf clicked
forever
+    go to x:(x coord of (right eye v)::#0fbd8c)y:(y coord of (right eye v)::#0fbd8c)
```
--- /task ---

--- task ---
Duplicate your new eye sprite by right-clicking on it below the stage and choosing **Duplicate**.
--- /task ---

--- task ---
Go into your new eye sprite and change the two `coord of right eye`{:class="block3extensions"} blocks to say `left eye`{:class="block3extensions"} in the drop down.
``` blocks3
when gf clicked
forever
+    go to x:(x coord of (left eye v)::#0fbd8c)y:(y coord of (left eye v)::#0fbd8c)
```
--- /task ---

--- task ---
Click the green flag to see your new face mask come to life and follow you around the screen!
--- /task ---

--- save ---

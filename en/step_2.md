## Facial recognition with Scratch

For this activity, we’re going to use a special version of Scratch created for just this reason! You can open this special fork of Scratch any time by following [this link](https://machinelearningforkids.co.uk/scratch3/){:target="_blank"} to make your own machine learning projects.


Unfortunately, because this version of Scratch is a bit different to the normal one - if you want to be able to save your work, you’ll need to download your project to your computer and re-open it in the special version of Scratch when you want to use it again.

--- task ---

If working **online**, open the [starter project](https://machinelearningforkids.co.uk/scratch3/){:target="_blank"} in Scratch.
 
As this project requires connection to the cloud based machine learning engine, offline work is not possible.

You should see...
 
![starter project](images/starter_project.png)

--- /task ---

--- task ---

Once you’ve followed the link above, you should be able to see a brand new, empty Scratch project, just like you're used to - the cool part comes when we add some new Extensions that are included in this fork of Scratch. The two extensions we want to enable are Video Sensing and Facial Recognition - add them both now.

--- collapse ---
--- 
title: Adding extensions in Scratch
---
--- /collapse ---

--- /task ---

Now that we have added the extensions we need to Scratch, you should see two new menus on the left of your screen. You may have used Video Sensing before, but the Facial Recognition blocks may be new to you. 

These new blocks have been created to access an already existing Machine Learning model that exists on the cloud and has been trained to recognise human faces. We’re simply using these blocks to tell Scratch to check with the online model to see where the face appears on your stage.

--- task ---

Let’s see if they work!

Begin by adding a `When Green Flag Clicked`{:class="block3events"} to start our project.
--- /task ---

--- task ---
Next, we need to use our `video sensing`{:class="block3extensions"} blocks to make sure that the camera is on and totally opaque when the project starts. Add a `set transparency to 0`{:class="block3extensions"}.

--- /task ---

--- task ---
Click the Green flag to test your work and see the camera come online.  
Give your browser permission to use your camera if you are asked.
--- /task ---

Now, we're going to change the costume of our cat sprite to something more like a face.

--- task ---
Stop the project and click on the costumes tab for your cat sprite. Add a new costume that you want to use as your mask and delete the old ones of the cat. Here I've used the 'heart face' costume, but you can use anything you like.
---collapse ---
---
title: Adding costumes in Scratch
---
--- /collapse ---
--- /task ---

Now, we're going to add the code that will make the mask detect and follow your face!
--- task ---
At the bottom of you script, add a `forever`{:class="block3control"} block from the control list. 
--- /task ---

--- task ---
Next, add a `go to x and y`{:class="block3motion"} block inside your forever loop.
--- /task ---

--- task ---
Open the `Facial Recognition`{:class="block3extensions"} menu on the left and drag across the small round `x coord of nose`{:class="block3extensions"} and `y coord of nose`{:class="block3extensions"} blocks and pop them into their corresponding spots (making sure you match x with x and y with y!) 
--- /task ---

--- collapse ---
--- 
title: Adding extensions in Scratch
---
--- /collapse ---

--- /task ---


--- save ---

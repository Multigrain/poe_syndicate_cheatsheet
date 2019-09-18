# Path of Exile Syndicate Cheat Sheet

This is just a simple python script to create the well known cheat sheets we have seen
across Reddit but in a more programmatic way versus just straight up Photoshop. The GUI
is made in Tkinter to keep package management as simple as possible. Credit to the formatting
based on the ones I've seen floating around on Reddit (There are a few and I cant find origin)
and images from the wiki.

Clicking on each cell in the table toggles between the colour's. You can change the
existing colours in code or even add new ones to cycle between. All the images are separated
into individual assets for easy updates/changes.

Currently I haven't added the ability to export as an image so for now you have to use 
a form of screen capture. Also on a screen with a resolution smaller than 1920x1080 you will
have to stitch your screenshots together, I have scrollbars.

Also if any of the information is outdated please let me know or even just PR a fix so I can update.
There wasn't really one detailed reliable source that's up to date that I could find.

I have included a blank image if you don't want to run script, and an example image.

## Supported OS
* Windows

I have only tested it on windows and mac. Mac tkinter has problems with the rgba images
so either have to rework images or change the GUI framework. If anyone has a more elegant fix
lemme know. Linux might work as I don't think it has same problem as OSx.

## Requirements
* python
  * Tkinter (should be included by default in python 3.7+)
  * Pillow


## To Do

* Export/Import functionality
* Ability to save as image
* Add scalability for smaller screens

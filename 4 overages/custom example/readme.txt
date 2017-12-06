WUnderground Gauge Pack Custom Example

You can take images from the gauge pack and rename them to use them for other things. For 
devices and variables (in other words, things that change), Indigo needs an image that's
specially named as the basis for it's logic and it needs to be named this way:

	image+.png

It doesn't have to be called "image" but the structure of the filename is important. For
example, it could be called severeWeatherAlert+.png. This is also what you will see in the 
control page editor.  Then, you add additional images with names that reflect the state
(or variable value) that you want to key on. For example, severeWeatherAlert+true.png. I 
like to use the "true" or "on" value for image+.png so that I can see how it looks when 
I'm building my pages.

Then you can take images from the gauge pack and rename them to suit your needs.  The 
files in this custom folder are but one example. You will notice that +false and +off are 
made with a blank PNG image (that is found in the jewelry folder) because in this example
we want the off and untrue values to "hide" the ambient glow. The files in this example
are:

WUoverageGreen+.png
WUoverageGreen+false.png (no glow)
WUoverageGreen+off.png (no glow)
WUoverageGreen+on.png (displays glow)
WUoverageGreen+true.png (displays glow)

You will take these images and place copies in the Indigo images folders for devices and
variables and put a corresponding center bubble from this gauge pack int the static 
folder. Of course, you don't have to use the green glow; you can use any images you like.

There is a good Indigo wiki article on image selection heuristics (how Indigo will choose
which image to display) found here: 

http://wiki.indigodomo.com/doku.php?id=cp_custom_images

See also:
http://forums.indigodomo.com/viewtopic.php?f=149&t=12499
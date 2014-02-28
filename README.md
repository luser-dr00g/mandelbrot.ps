mandelbrot.ps
=============

An interactive Mandelbrot-set explorer for ghostscript

Inspired by A K Dewdney's The Armchair Universe

Draws a typogram preview while calculating the escape times for each box,
Calculates the Max and Min and redraw with filled boxes,
Print config values, shortcut menu and offer PS prompt until EOF (ctrl-D),
call showpage and loop to the beginning.

You can also change the drawing style. The normal definition is:

    /colorpixel /hsbwheel load def

but you can also use any of:

    /evenodd /tenrip /skippy

in place of /hsbwheel. eg.

    /colorpixel /skippy load def

And remember to hit EOF (ctrl-D) to re-draw the image with your changes.

a version from Nov 22, 2012 is archived at
http://code.google.com/p/xpost/downloads/detail?name=mandel2.ps

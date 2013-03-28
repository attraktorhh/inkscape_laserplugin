Inkscape Laserplugin
====================

An inkscape plugin for creating gcode for the laser cutter in the attraktor makerspace.
Based on the work of the thinkhaus hackerspace (http://wiki.thinkhaus.org/index.php?title=THLaser_Plugin).

Put the attraktor_laser.py and attraktor_laser.inx in your inkscape extensions folder (/usr/share/inkscape/extensions/ on ubuntu).

To create gcode select all objects that you want to laser, make sure they are paths by clicking on "Path/Object to Path" and export with "Extensions/Export/Attraktor Laser..."

The default values are OK for engraving. For cutting adjust the feedrate to 100-200 mm/minute depending on the material thickness.

In order to have stuff lasered in the right order put them on separate layers. Lower layers will be lasered first. If you want to override the feedrate for a layer name it in the following way: "LAYERNAME [feed=150]".

There is an additional plugin called eggbot_hatch from the eggbot project (http://egg-bot.com) included. It can put lines into closeds paths - that way you can engrave solid black or striped objects.

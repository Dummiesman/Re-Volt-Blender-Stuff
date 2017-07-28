# Changelog HabitatB

## 2017-05-08

+ Car textures will now be loaded even if / is used instead of \ in parameters.txt (thanks to Gotolei for reporting)
+ Textures are now kept even after reopening a .blend file with an imported prm/w
+ Export now takes object scale, rotation and translation into account properly. This should also fix issues with exported ncp files. (Thanks to R6 for reporting)
+ New buttons in the tool panel. You can now import and export directly from there. There also are new buttons for batch-setting object types, as well as additional also-export-as properties. For edit mode, you now get buttons for selecting all faces of one or more types. (Thanks to Gotolei for inspiration)
+ Dummiesman changed the world export script to be a lot more efficient and less prone to errors. Thanks a lot for putting up with my code.
+ Many small bug-fixes that you can read about on GitHub.

## 2017-07-26

+ Experimental POS support (only import, no export)
+ Fixed the PRM export issue where only 50% of the faces were exported
+ Fixed the selection buttons for faces in the tools panel.
+ Object scale is taken into account when exporting

## 2017-07-27
+ Renamed vertex color and uv channels to match Blender defaults
+ Removed icons from the additional export buttons

## 2017-07-28
+ Added Lights and Shadow section in the Tool panel
+ Added button for automatically shading objects
# cities: skylines assets

some notes for buildings:

Set Blender units to meters, with a scale of 1.000 - when exported correctly this will ensure that each grid line in blender represents one grid line in-game. Make sure the center point for the mesh is at the middle of the bottom of the mesh - this will tell the game engine where the bottom of the building is.

(easiest - select bottom faces before you delete them, shift-S -> cursor to center, then ctrl-shift-alt/option-C -> origin to 3d cursor)

When exporting, settings to use:
- first, select object and ctrl-a -> rotation and scale -> check 'Location' in panel
- export to FBX
- see wiki for texture naming conventions
- export selected objects (and select your mesh before exporting)
- set scale to 8.00
- Forward: -Z Forward
- Up: Y Up
- Apply Transform: true
- Apply Modifiers: true
- all other settings as default.

Refer to http://www.skylineswiki.com/Asset_Editor for more information.

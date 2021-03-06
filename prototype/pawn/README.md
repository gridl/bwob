To run
======

    python run.py

Controls
========

    Esc: quit
    Tab: switch control scheme
    Arrows or WASD: pan
    1/2: zoom
    F12: screenshot

Removing parts
--------------

P-axe: left-click on the axe and then on the base of the part you want to remove. All parts
"outward" from the removed part will also be removed.

O-axe: left-click on the axe and then click on the base of the part you want to remove. For
branching paths, you can either click on the "outer" half to remove a single branch, or the "inner"
half to remove all branches.

Control scheme rando
--------------------

	Left-click in gameplay area: place random part
	Right-click in gameplay area: place 10 random parts
	Middle-click in gameplay area: place 100 random parts

Placing a part might fail, because it randomly picks a place where no part can grow. In this case
no part will be placed.

Control scheme tetris
---------------------

Current part for placement is shown in panel. Places where current part can go are shown with
white circles.

	Left-click in gameplay area: place current part
	Left-click in panel area: trash current part

Control scheme pyweek
---------------------

Nine parts (three of each color) are available at any given time. The selected part, if any,
appears with a white circle behind it. Places where selected part can go are shown with white
circles, as with the tetris control scheme.

	Left-click in gameplay area: place selected part
	Left-click in panel area: select part
	Right-click in panel area: recycle part

Control scheme utree
--------------------

Arbitrary stalks may be placed at any time by dragging from edge to edge. Drag from the entry point
of the tile to the exit point of the tile. To create a branch, drag the individual stalks from the
entry point. Branches may not be created coming from the same entry point as an organ.

Organs are placed the same as in control scheme pyweek.

	Left-click on edge or left drag from edge: grow stalk from selected edge
	Left-click in panel area: select organ
	Right-click in panel area: recycle organ


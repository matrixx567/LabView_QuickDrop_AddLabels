# LabView QuickDrop AddLabels

A LabVIEW Quick-Drop (QD) plug-in to easily add or remove labels to blockdiagram elements.


## Installation
Place the `Add Labels.vi` file in your `<LabVIEW>\resource\dialog\QuickDrop\plugins` folder.

## Usage

This quick-drop plug-in works only in the block diagram.

### Add or remove a label to SubVIs

Select a SubVI within a blockdiagram.  
Press `Ctrl+Space` and  `Ctrl+Q`  to add a label to a SubVI.
For removing the label press `Ctrl+Space`and `Ctrl+Shift+Q`


The animated GIF below show the three possible options of the plugin:

* Add/Remove a label to a SubVI.
* Add/Remove a subdiagram label to a structure element.
* Add/Remove a label to a wire
* Show again an already set wire label

![Using the plug-in](../master/usage.gif)

It is also possible to select more than one element within a blockdiagram. Therefore the appropriate label will be added to the selected elements.

## Hints
The plug-in is developed in LabVIEW 2016. If you have an older version of LabView you have to save the provided project to this older version by yourself.
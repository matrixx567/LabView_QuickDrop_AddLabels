# LabView QuickDrop AddLabels

A LabVIEW Quick-Drop (QD) plug-in to easily add or remove labels to blockdiagram elements.


## Installation
Place the `Add Labels.vi` file in your `<LabVIEW>\resource\dialog\QuickDrop\plugins` folder.

## Usage

This quick-drop plug-in works only in the block diagram.

### Add or remove a label to SubVIs

Select a SubVI within a blockdiagram.  
Press `Ctrl+Space` and  `Ctrl+Q`  to add a label to a SubVI.
For removing the label press `Ctrl+Space`and `Ctrl+Shift+Q`.

### Add or remove a subdiagram label to a structure element

Select a structure element within a blockdiagram.
Press `Ctrl+Space` and `Ctrl+Q`to add a subdiagram label to the structure element.
For removing the label press `Ctrl+Space`and `Ctrl+Shift+Q`.

### Add or remove a label to a wire

Select a wire.
Press `Ctrl+Space` to open the quick drop. Insert a label text to the input field.
Press `Ctrl+Q` to add the inserted label to the wire. The plug-in will add `>>` before and after the label text.
For removing the label press `Ctrl+Space`and `Ctrl+Shift+Q`.
If you want to add the removed label again press `Ctrl+Space` and `Ctrl+Q`.


The animated GIF below show the three possible options of the plugin:

* Add/Remove a label to a SubVI.
* Add/Remove a subdiagram label to a structure element.
* Add/Remove a label to a wire
* Show again an already set wire label

![Using the plug-in](../master/usage.gif)

It is also possible to select more than one element within a blockdiagram. Therefore the appropriate label will be added to the selected elements.

## Hints
The plug-in uses a malleable VI. Therefore the plu-in only works with LabVIEW 2017 and above.
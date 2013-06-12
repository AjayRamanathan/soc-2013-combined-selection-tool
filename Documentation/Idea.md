#Introduction

[Gimp][0] is an open source softwaree for high-end image processing. For the image editing there are seven different selection tools available.My Project is to turn the seven selection tools into fewer more compact set of tools. The new set of tools should have to be musch faster/easier to use than the old ones.For example, the user shouldn't have to go out of the image in the menu bar to change the options. It also must be easy to user for all users.And the new tool need to have adequate shortcuts.

#[The current Selection tool][1] 

[Rectangle Selection Tool][2] `R` 
The Rectangle Selection tool is designed to select rectangular regions of the active layer.

[Ellipse Selection Tool][3] `E` 
The Ellipse Selection tool is designed to select circular and elliptical regions from an image, with high-quality anti-aliasing.

*Improvements* : *Needs Rotation; so that more than the basic shapes can be achieved; More shapes other than Rectangle and Ellipse needs to be introduced*

[Select by colour Tool][4] `Shift+O`
The Select by Color tool is designed to select areas of an image based on color similarity. It works a lot like the Fuzzy Select tool (“Magic Wand”).Select by Color tool selects all pixels that are sufficiently similar in color to the pixel you click on, regardless of where they are located. 

[The Magic Wand/Fuzzy Select][5] `U`
The Fuzzy Select (Magic Wand) tool is designed to select areas of the current layer or image based on color similarity.

[Foreground Select Tool][6] 
This tool lets you extract the foreground from the active layer or from a selection. It is based on the [SIOX][7]

*Improvements* : *All the three tools are very similar;can be combined to make a easy to use tool.Foreground Select Tool can is achived by selecting 2 version of multiple colours [One for the backround and on for the foreground],Same can be achieved by choosing multiple colours.*

[Free Select Tool][8] `F`
The Free Selection tool, or Lasso, lets you create a selection by drawing it free-hand with the pointer, while holding down the left mouse button

[Intelligent Scissors][9] `I`
Intelligent Scissors is useful when you are trying to select a region defined by strong color-changes at the edges.


[0]: http://www.gimp.org/ "Gimp"
[1]: http://docs.gimp.org/en/gimp-tools-selection.html "Selection Tool"
[2]: http://docs.gimp.org/en/gimp-tool-rect-select.html "Rectangle Selection Tool"
[3]: http://docs.gimp.org/en/gimp-tool-ellipse-select.html "Ellipse Selection Tool"
[5]: http://docs.gimp.org/en/gimp-tool-fuzzy-select.html "Magic Wand"
[4]: http://docs.gimp.org/en/gimp-tool-by-color-select.html "Select by Color"
[6]: http://docs.gimp.org/en/gimp-tool-foreground-select.html "Foreground Select Tool"
[7]: http://www.siox.org/ "SIOX"

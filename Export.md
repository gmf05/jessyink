# Export #

The export extension has changed quite substantially in JessyInk version 1.5. While before JessyInk presentations were exported directly in Inkscape from the file that had been used to create them, an intermediate step of exporting the presentation to a new file using FireFox is now required. The reason for this change is that in the old way of exporting a JessyInk presentation all the effects, transitions and other changes to the image that are coded in JavaScript had to be reimplemented in Python. This limited the flexibility of JessyInk and made it very hard to maintain.


To export your presentation, follow the steps outlined below:


  * Create a JessyInk presentation in Inkscape.
  * Load your presentation in Firefox. At the moment, Firefox is the only borwser that implements the functions required for the export feature to work.
  * Press the "e" key to start the conversion of your presentation to an svg image with one layer for every effect or transition. The result will be offered as a download. Please note that Firefox might save the resulting file under some seemingly random name (most likely ending in .part). Of course you are welcome to change this name. However, even with the original name the file should open in Inkscape, although you may have to tell your operating system which programme to open it with.
  * Open the new image in Inkscape.
  * Select save as from the file menu.
  * Enter a file name and choose the location where you want to save the exported presentation.
  * Select "JessyInk zipped pdf or png output (`*`.zip)" as the file type.
  * Click the save button.
  * The export dialog box shown below will appear. In this dialog box you can select the format (either PDF or PNG) and the resolution. With the PDF format the resolution refers to the resolution of the effects that are rendered to a bitmap image for the export (e.g. blur).
  * Click the ok button. Please be patient. Depending on the number of slides and effects, the export may take a while. After the message "document saved" apeared in the status bar, you should find a zip file in the location you chose containing one file for each slide and effect in the format you specified.

Using the intermediate step of creating a new image in the browser first means that the same code is used for the effects on screen as for the export. Even if new effects, transitions or other features are added to JessyInk, the code for the export extension will stay the same. Dialog box of the export extension. Graphical representation of the new export.

![http://jessyink.googlecode.com/files/extension_export.png](http://jessyink.googlecode.com/files/extension_export.png)

Dialog box of the export extension.

![http://jessyink.googlecode.com/files/extension_export_stepbystep.png](http://jessyink.googlecode.com/files/extension_export_stepbystep.png)

Graphical representation of the new export.
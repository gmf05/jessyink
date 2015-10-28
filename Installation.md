# Installation #

To obtain basic functionality, only three simple steps are required.

## Installing the JessyInk extensions for InkScape ##

For Ubuntu, installation packages are available on the launchpad site. After installing the package following the instructions on launchpad, you can continue directly with step 3 (Installing the JessyInk skript).

The JessyInk extensions depend on the "inkex" script provided by Inkscape. Therefore, the easiest way to install them is to simply copy all the files found in the folder named "inkscapeExtensions" of the distribution to the directory containing the "inkex.py" file. Depending on your operating system, this file is usually located in one of the following directories:

  * on Windows (English localisation): "C:\Program Files\Inkscape\share\extensions"
  * on Linux: "/usr/share/inkscape/extensions"
  * on OS X: "/Applications/Inkscape.app/Contents/Resources/extensions"

Having copied the files to the correct location, Inkscape will automatically display the submenu "JessyInk" in the "effects" menu. The submenu will contain entries for all the different JessyInk extensions.

Should you want to install the JessyInk extensions in a different location or should you experience problems running the extensions, please verify that one of the paths given at beginning of the Python script of each JessyInk extension points to the directory where the "inkex.py" script is located.

## Changing file permissions (UNIX) ##

Depending on your platform (UNIX-like, Linux, OS X), you may have to change the permission of the files. The python files need to be executable. Should you experience problems you can try the following: Open the terminal, change into the directory where the JessyInk files are located and change the permissions using:

```
chmod 755 jessy*py
chmod 755 jessyInk.js
chmod 644 jessy*inx
```

## Installing the JessyInk script in an SVG file ##

After the JessyInk extension has been installed, a new sub-menu titled JessyInk is available in the effects menu. Selecting install/update in this menu opens an effect window. Pressing apply in this window, installs (or updates) the JessyInk script. Unless you inspect the document in the XML editor, you won't notice any change.

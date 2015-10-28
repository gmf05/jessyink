# Introduction #

A feature that has been requested several times and has yet to be implemented is the support of a master-page (i.e. a page that contains the elements that should be displayed on every slide).


# Option 1 #

This option has been proposed by  [poisendw...@web.de](http://code.google.com/u/@UhdQQ1VXDhhNWwZ8/) and described on the issue page. This is a verbatim copy of the issue description:

How to use a master page
  1. Select  the lowest layer in Inkscape (e.g."Title" in "jessyink\_0\_1.svg".
  1. Create a new layer below the lowest layer and call it e.g. "Master"
  1. Draw background elements and images as you like it
  1. Lock the layer "Master"
  1. Open the "XML-Editor" in Inkscape.
  1. Select the first element "svg:g"
  1. On the right hand side select the "inkscape:groupmode" attribute and click on "delete attribute" above in the symbol panel (see also attached screenshot).
![http://jessyink.googlecode.com/files/Layer2Master.png](http://jessyink.googlecode.com/files/Layer2Master.png)
That's it!

If you want to modify the Master:
  1. Open the "XML-Editor" in Inkscape.
  1. Select the first element "svg:g"
  1. Type "inkscape:groupmode" in the empty field, enter "layer" as attribute value and click "set"
  1. Unlock the layer in the "layer" dialog and modify it
  1. Lock the layer and delete the inkscape:groupmode-attribute (see above)

When you open this svg in firefox, the Master page will always be
displayed!

# Option 2 #

Inkscape supports the cloning of elements. It is therefore possible to create an object on one layer and then copy clones the other layers. If the original is changes, all clones will be updated accordingly.
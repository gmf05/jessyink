# Video element #

The video element was inspired by a blog post from Tom Ibbotson. Tom suggested the videos could be embedded into JessyInk presentations using the HTML5 video tag and provided a first example.


To make the integration of video easier, an Inkscape extension to add a video element to a JessyInk presentation was created. This video element is the first of a new kind of JessyInk extensions that come with there own visual object visible in Inkscape. The Inkscape extension only copies this object into the presentation. The options (URL of the video and its size) are then assigned by changing the text in particular field and adjusting the size of a rectangle. For JessyInk 2, It is planned to move all JessyInk extension to this format to improve the user experience and make JessyInk more flexible and more easily extensible.


Note that, during the presentation, you have to right click the video and select "play" from the context menu to start playing the movie. Since this triggers a click on the slide, it is recommended that you install the no-click mouse handler to avoid that effects or transitions interfere.


## Adding a video to a presentation ##

### Adding the video element ###

Select video form the JessyInk sub-menu available in the effects menu. In the effects window that appears, select apply. A video element will be added to the current layer.



![http://jessyink.googlecode.com/files/element_video.png](http://jessyink.googlecode.com/files/element_video.png)

_The video element._

### Setting the URL of the video ###

To set the URL of the video, replace the text "<replace this text with the url of the movie>" in the video element with the URL of the video you want to be displayed.


In Inkscape, this can be done by selecting the text tool in the side bar by clicking on it. Then move the cursor over the text string saying "<replace this text with the url of the movie>" in the video element and click it. Select the whole text string by pressing the "control" and the "a" keys. Afterwards, either type the URL of the video or, if you have copied the URL into the clipboard, paste it into the text field by pressing the "control" and the "v" keys.


Note that if you want to use a video stored on your local computer, you have to prefix the path with "file://" (e.g. "[file:///home/joeuser/videos/holidays2010.ogg](file:///home/joeuser/videos/holidays2010.ogg)").



![http://jessyink.googlecode.com/files/element_video_set_url.png](http://jessyink.googlecode.com/files/element_video_set_url.png)

_Setting the URL of the video._

### Setting the size of the video ###

To set the correct size of the video you need to adjust the base size of the grey rectangle.


In Inkscape, you can adjust the size of the base size of the gray rectangle by selecting the rectangle tool in the side bar by clicking on it. Afterwards, move the cursor on the grey rectangle in the lower part of the video element and click on it. The tool bar above drawing will change and boxes for changing the width and hight of the base rectangle will appear. Set the width and hight to the original size of the video you want to include (these values can for example be obtained from the "properties" dialog of the file in your file manager).


Should you wish to change the display size of the video, you can do so by selecting it using the selection tool (top most tool in the side bar). However, you have to set the correct base size following the steps outlined above first. If you fail to set the base size, your video will distorted.



![http://jessyink.googlecode.com/files/element_video_set_size.png](http://jessyink.googlecode.com/files/element_video_set_size.png)

_Setting the size of the video._

## Compatiblity ##

### Ubuntu 9.10 ###

Compatibility table for the video element on Ubuntu 9.10.
| **browser** | **remarks** |
|:------------|:------------|
| FireFox 3.6.4pre | works       |
| Chromium 5.0.342.7 | video is not displayed |
| Opera 10.10 | video is not displayed |
![http://jessyink.googlecode.com/files/logo.jpg](http://jessyink.googlecode.com/files/logo.jpg)
# JessyInk #
JessyInk is a JavaScript that can be incorporated into an Inkscape SVG image containing several layers. Each layer will be converted into one slide of a presentation. Current features include: slide transitions, effects, an index sheet, a master slide and auto-texts like slide title, slide number and number of slides.
# News #
**23 February, 2013:** Fernando da Rosa Morena published a blog post with a very complete and detailed comparison of Prezi and JessyInk. The article is titled [Presentaciones, Prezi vs. JessyInk](http://www.fedaro.info/2013/02/23/presentaciones-prezi-vs-jessyink/) (Spanish) and can be found on [Fernando's website](http://www.fedaro.info/). It also includes examples and video.

**22 February, 2013:** JessyInk release **1.5.6**: The main purpose of this release is to introduce the Mozilla Public License Version 2 (MPL) as an alternative license for the core JessyInk script. This change was made on request of Thorsten Behrens of [The Document Foundation](https://www.documentfoundation.org/). Thorsten informed me that Marco Cecchetti, a GSoC student working on LibreOffice, had considerably improved the Impress export to svg drawing inspiration from the JessyInk code. Thorsten requested the release of the core JessyInk script under the MPL to make it easier to distribute this code with ports of LibreOffice on other platforms. After consultation with other contributors, I was happy to comply with this request.

**27 December, 2010:** JessyInk release **2.0.0 alpha 1**: This is a development snapshot of version 2 of JessyInk. The main purpose of this release is to give the community an opportunity to provide feedback on the new design of JessyInk. This version is a re-implementation of the code in a highly modular way. The user interface is now based on graphical objects that can be copied and grouped for installation of the scripts and assignment of effects and views. So far only very basic functionality is provided. However, further features will be added in future versions leading up to version 2.0.0.

Although this version of JessyInk is functional, it is not recommended for production use.

**26 December, 2010:** **JessyInk on Drumbeat**: About a month ago I created an account for JessyInk on Drumbeat. Since then, over 300 people registered for the project. I am glad about the interest in the project and hope that the community around JessyInk will grow further. Only with the support of a vibrant community we can improve JessyInk and take it to the next level. I therefore would like to thank all people contributing and using JessyInk.

Drumbeat is a community website for people interested in improving the web sponsored by Mozilla. You can find out more about Drumbeat at [www.drumbeat.org](http://www.drumbeat.org)

**7 November, 2010:** JessyInk release **1.5.5**: This release fixes two bugs concerning the export of JessyInk presentations. The export should now be faster and more accurate.

**27 October, 2010:** JessyInk release **1.5.4**: This release fixes the version numbering in the install extension.

**24 October, 2010:** JessyInk release **1.5.3**: This release fixes two bugs concerning the use of non-ASCII characters in layer names.

**5 October, 2010:** A big "thank you" goes out to **Nico Göth** for the donation of some memory for my laptop! Work is so much more enjoyable, without the constant paging to and from the hard-disk.

**15 August, 2010:** Presentation: **JessyInk - A set of Python extensions to create presentations in Inkscape by Hannes Hochreiner** is now available for [download](http://jessyink.googlecode.com/files/2010-07-19_Hochreiner_EuroPython.svg). In his presentation at EuroPython 2010, Hannes provided a brief introduction of Inkscape before explaining its extension facility in more detail. The JessyInk set of extensions was used as an example to demonstrate different patterns thought to be useful for different types of extensions. To finish off, JessyInk and its various features were introduced.

**15 August, 2010:** New article: **Show and Tell - Creating presentations with Inkscape and JessyInk by Dmitri Popov**: Dmitri had a look at JessyInk for the Linux Magazine. His article, published in [Issue 117](https://code.google.com/p/jessyink/issues/detail?id=117) for August 2010, describes the installation of JessyInk and covers some of JessyInk's features in more detail. Furthermore, general tips on how to create nice visuals for presentations with Inkscape are supplied. Dmitri's conclusion: Give Inkscape/JessyInk a closer look when creating your next presentation!

**14 August, 2010:** New tutorial: **A tutorial Introduction to JessyInk: Presentations in Inkscape by Tim Teatro**: The second article in Tim's tutorial series on JessyInk is now available. In a step-by-step guide Tim explains in detail how to create a simple presentation using JessyInk. Topics covered include basic set-up, transitions, effects, master slides and auto-texts. In addition to the descriptions and screenshots, a sample file is provided making it easy to for new users see how JessyInk works. This is a great resource for new and experienced Inkscape/JessyInk users alike, so check it out on Tim's blog at: [http://www.timteatro.net/2010/08/12/a-tutorial-introduction-to-jessyink-presentations-in-inkscape/](http://www.timteatro.net/2010/08/12/a-tutorial-introduction-to-jessyink-presentations-in-inkscape/)

**9 August, 2010:** New tutorial: **Installing JessyInk by Tim Teatro**: Tim has published a very nice tutorial on how to install JessyInk under Linux, Windows XP and 7. It's the perfect starting point for people who want to check out JessyInk and start creating their first presentations using Inkscape. The tutorial is available on Tim's blog at: [http://www.timteatro.net/2010/07/31/installing-jessyink/](http://www.timteatro.net/2010/07/31/installing-jessyink/)

**3 August, 2010:** JessyInk release **1.5.2**: This is a bug fix release. A problem that could cause the export to fail has been fixed. Furthermore, the determination of the position of the mouse has been changed to work with newer versions of Chrome.

**15 May, 2010:** JessyInk release **1.5.1**: Due to a problem with the view definitions in Firefox, a bug-fix release was published today.

**14 May, 2010:** JessyInk release **1.5.0**: Thanks to HTML5 JessyInk just gained a new feature! It is now possible to integrate videos in your JessyInk presentations. Thanks to an idea from **Tom Ibbotson**, you can create even more impacting presentations by adding videos. The **video extension** is also the first extension to be presented in the new style. For the upcoming version 2.0 of JessyInk, all elements will be updated to this style. Any feedback on how you like the new extension is highly appreciated.

Thanks are also due for **Jameson Rollins**, who volunteered to help with packaging by providing Debian **packages**. The popularity of the packages underlines the importance of his and **Dominic Evans'** work on them. Thanks a lot!

Last, but not least, several bugs were fixed and improvements made to make JessyInk work even better, especially with Inkscape 0.47.

**12 December, 2009:** JessyInk release **1.4.0**: From the user feedback it is obvious that zoom-based presentations are getting increasingly more popular. Responding to this trend, JessyInk introduced a new extension for mouse navigation. This new mouse handler allows the presenter to drag and zoom the slide as well as to create an ad-hoc view by clicking on any object on the slide.

**20 September, 2009:** After the introduction of a host of exciting new features in release 1.3.0, this release (**1.3.1**) corrects two issues that came up recently. Marc Eberhard improved the event handling in drawing mode to avoid conflicts between drawing on the slide and dragging the image. Furthermore, parsing of the transform matrix with views was changed, so that views work in Opera now as well.

**2 August, 2009:** The JessyInk team is proud to announce the release of **JessyInk version 1.3.0**. This release features very exciting contributions from **Marc Eberhard**, who implemented a **drawing mode** allowing users to draw on the slides during the presentation in the browser. Another interesting new feature is the ability to assign "views." This feature can be used to zoom-in on a particular region of the slide. **"Views"** provide exciting new ways to enhance your presentations. Also new in this release is the option to **customise the key bindings**. To further improve the compatibility and usability of JessyInk, custom keys can now be assigned to all actions. For maximum flexibility, each mode (slide, index, drawing) has its own set of key bindings.

**1 June, 2009:** **JessyInk 1.2.0** has been released today. This release features **improved keyboard and mouse controls** thanks to contributions from **Egor Zindy** as well as the often requested **PDF export** extension. Furthermore, the scheduling mechanism for transitions and effects has been changed, which should improve the perceived performance of JessyInk presentations.

**15 April, 2009:** There was a small glitch in the demo file of JessyInk version 1.1.0. Some of the images have not been embedded. Please use the newly provided **JessyInk version 1.1.1**.

**15 April, 2009:** I am happy to announce that **JessyInk version 1.1.0** has been published today. Installation is now even easier, as it is no longer required to set the "onload" attribute. Simply use the "install/update" extension and you are done! The new release also features linking to specific slides, clipping of the content to the size of the slide and a new extension that lists all JessyInk transitions, effects and auto-texts contained in a presentation. On the technical side, all JessyInk attributes have been moved into their own namespace to make JessyInk a well behaved citizen of the XML community. Furthermore, the release includes fixes to a couple of bugs that have been reported since the release of version 1.0.0. Special thanks go to **Jos Hirth** of InkSlide fame for sharing his insights.

**4 April, 2009:** **heathenx** has published an episode on JessyInk in the series of his wonderful screencasts of Inkscape tutorials! It's a great tutorial for getting started with step-by-step explanations of how to install and use JessyInk. [Make sure to check it out!](http://screencasters.heathenx.org/wp-content/videos/ep086/ep086.html)

**28 March, 2009:** Today the first feature complete release of JessyInk has been published. It is available for download either from launchpad (https://launchpad.net/jessyink) or from this site. Special thanks go to Marcel Rouweler and heathenx for their feedback and testing efforts as well as Ted Gould for integrating a patch required by JessyInk into Inkscape.

**23 May, 2008:** The beta of version 1.0 is out! This release is the first feature complete version of JessyInk. JessyInk now supports transitions, master slides, effects, auto-texts and, of course, an index sheet mode. I still have to catch up on the documentation, but feel free to experiment with this version.

**9 May, 2008:** Version 0.2 of JessyInk is now available for download! Notable changes include the **new Python extensions** for (un)installing JessyInk and setting transitions. Please note that due to the way Inkscape interacts with extensions, step 5 of the manual installation procedure (setting the "onload" property) still has to be done by hand. Another great new feature are **effects**: single elements on one page can now be assigned a build in/out effect. A new Python extension for setting effects is available as well.

**16 April, 2008:** Inkscape extensions are now available to install and uninstall JessyInk. Due to the particular way in which Inkscape handles extensions, users are still required to make one manual change in the Inkscape XML editor to complete the installation. However, a bug report with corresponding patch has been filed.

**26 March, 2008:** The JessyInk project is now registered in [Launchpad](https://launchpad.net/jessyink/). Issue tracking has been moved to the "[Bugs](https://bugs.launchpad.net/jessyink/)" page in Launchpad. Plans for design changes and future directions of the project can be found in the "[Blueprints](https://blueprints.launchpad.net/jessyink/)" and can be discussed on dedicated wiki pages on this website.

**22 March, 2008:** Updated the JessyInk script to reflect the project name change and made installation easier. With the initial release, following the installation instructions did not produce a scaleable presentation. The new script takes care of making the required changes to the SVG file to yield a scaleable presentation. All that is required is adding the "svg:script" tag in the Inkscape XML editor, copying the script into the tag and adding an "onload" argument with the value "jessyInkInit()" to the root node.

**20 March, 2008:** Due to the positive feedback, I decided to continue developing JessyInk. The first goal will be to clean up the script (e.g. put new attributes into the "jessyInk" namespace) and write an Inkscape extension for easy installation of the script.
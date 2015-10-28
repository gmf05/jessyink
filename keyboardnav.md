# JessyInk keyboard navigation (proposal) #

This page discusses keyboard navigation for upcoming versions of JessyInk. It is a **proposal** and may not reflect the current state of JessyInk. See also the [mouse navigation](mousenav.md) page.

## In slide mode ##

Moving backward and forward using set transitions:
  * **space** move to the next slide
  * **left** and **right** move back and forward one slide

Moving backward and forward without transitions:
  * **up** and **down** move back and forward one slide
  * **page up** and **page down** move back and forward one slide

Moving to the first and last slide:
  * **home** or **zero** moves to the first slide
  * **end** moves to the last slide

Switching to index mode:
  * **i** toggles from _slide_ to _index_ mode

## In index mode ##

Zooming in and out:
  * **0** reset zoom level (default zoom set to 4 slides across instead of 3?)
  * **-** zoom out (display more slides)
  * **+** or **=** zoom in (display less slides)

Moving around:
  * **up**, **down**, **left**, **right** arrows to select a slide
  * **page up** and **page down** move back and forward one page

Moving to the first and last slide:
  * **home** moves to the first slide
  * **end** moves to the last slide

Selecting a slide:
  * **i** or **enter** toggles from _index_ to _slide_ mode, selecting the highlighted slide

## Issues ##

### Solving the non-US keyboards issues ###
There might be an issue with the **-**, **+**, **=** zoom keys on non-US keyboards.

To sort this out, keyboard handling has tentatively been changed from _onkeyup_ to _onkeypress_ and keycodes identifiers were changed from _e.keyCode_ to _e.charCode || e.keyCode_.

### What does it all mean? ###
  * First of all, keys such as **i**, **=**, **-**, **+** are now identified by their ASCII code, rather than keycode. This should solve issues related to detecting those on different keyboards (**XXX** please confirm).
  * The problem however is that events are generated on key _down_ rather than key _up_. It's a departure from previous versions, so it may be a problem: Before, if a key was inadvertently pressed, this could give time to say something before releasing the key. Now when the key is pressed, action is immediate. This behaviour however is now on-par with mouse behaviour, which generated events on presses rather than releases.

### Please test ###
Could someone with a French, German or any other non-US keyboard tell me if the zoom keys work? I've been testing keyboard layouts with the onscreen keyboard, but it's far from ideal.

So if you have a non-US keyboard, Please test and feel in the blanks...

|Platform / Key|i|-|+|=|Space|Enter|Up|Down|Left|Right|PageUp|PageDown|
|:-------------|:|:|:|:|:----|:----|:-|:---|:---|:----|:-----|:-------|
|UK / Firefox 3.10 / Ubuntu 9.04 |?|?|?|?|?    |?    |? |?   |?   |?    |?     |?       |
|UK / Firefox 3.10 / XP |Y|Y|Y|Y|Y    |Y    |Y |Y   |Y   |Y    |Y     |Y       |
|UK / Opera 9.5 / XP |Y|Y|Y|Y|Y    |Y    |Y |Y   |Y   |Y    |Y     |Y       |
|UK / Opera 9.64 / XP |Y|Y|Y|Y|Y    |Y    |Y |Y   |Y   |Y    |Y     |Y       |
|UK / Chrome 2.0.172.28 / XP |Y|Y|Y|Y|Y    |Y    |Y |Y   |Y   |Y    |Y     |Y       |
|UK / Safari 4 (528.16) / XP |Y|Y|Y|Y|Y    |Y    |Y |Y   |Y   |Y    |Y     |Y       |
|DE / Firefox 3.10 / XP |Y|Y|Y|Y|Y    |Y    |Y |Y   |Y   |Y    |Y     |Y       |
|DE / Opera 9.5 / XP |Y|Y|Y|Y|Y    |Y    |Y |Y   |Y   |Y    |Y     |Y       |
|DE / Opera 9.64 / XP |Y|Y|Y|Y|Y    |Y    |Y |Y   |Y   |Y    |Y     |Y       |
|DE / Chrome 2.0.172.28 / XP |Y|Y|Y|Y|Y    |Y    |Y |Y   |Y   |Y    |Y     |Y       |
|DE / Safari 4 (528.16) / XP |Y|Y|Y|Y|Y    |Y    |Y |Y   |Y   |Y    |Y     |Y       |

(DE only tested on onscreen keyboard)

# Branch and presentation #

Code is available here:
https://code.launchpad.net/~ezindy/jessyink/ui-additions
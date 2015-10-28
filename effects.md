# Introduction #

Although it had often been written that effects in presentations are bad, I still think they can be helpful. Therefore, JessyInk implements effects. Currently, the same effects as transitions are available: appear, fade, pop.

# Details #

Effects can be assigned using the JessyInk effects extension. First, the object (or group) that one desires to assign an effect to has to be selected. Afterwards, the desired effect can be selected in the extension window. For each object or group two effects, a build in and a build out effect, can be selected. Each effect has a number associated with it that reflects its position in the series of all effects on a slide. The order number of two or more effects can be the same, which simply means that these effects will be played at the same time. Furthermore, the duration in seconds of the effect can be selected by setting the corresponding number to a value between 0.1 and 10.0. Please note that the duration has no effect for the type "appear", as this effect is instantaneous.

Pressing "apply" saves the changes. As with many JessyInk extensions, there will be no immediately visible effect in Inkscape. However, in a browser the object, with the effect assigned, will appear and/or disappear, according to the assigned effects over a time span corresponding to the duration selected.

![http://jessyink.googlecode.com/files/extension_effects.jpg](http://jessyink.googlecode.com/files/extension_effects.jpg)
_Screenshot of the effects extension._
# Mouse handler #

Mouse handler are a set of functions that determine what actions are taken when the user performs different actions using the mouse, such as clicking on a certain object on the screen, dragging a slide or zooming in on a portion of the slide.

Since mouse actions are somewhat more complex than key presses, mouse actions are assigned as a set of functions. Currently, three such sets are available for JessyInk. Apart from the default set, there is a set, where a mouse click does not trigger any action and finally a set optimsed for zoom-based presentations.

## Assigning a mouse handler set ##

Using the JessyInk "mouse handler" extension, the different sets of mouse handlers can be selected.

Pressing "apply" saves the changes.


![http://jessyink.googlecode.com/files/extension_mouse_handler.png](http://jessyink.googlecode.com/files/extension_mouse_handler.png)

_Dialog window of the mouse handler extension._

## The default mouse handler ##

With the default mouse handler the following assignment of actions applies:

Default mouse handler actions in slide mode
| **mouse event** | **action** |
|:----------------|:-----------|
| mouse down      | dispatch next event |

Default mouse handler actions in index mode
| **mouse event** | **action** |
|:----------------|:-----------|
| mouse down      | switch to slide mode |

Default mouse handler actions in drawing mode
| **mouse event** | **action** |
|:----------------|:-----------|
| mouse down      | start drawing |
| mouse up        | end drawing |
| mouse move      | draw       |

## The no-click mouse handler ##

With this mouse handler the assignment is identical to the default mouse handler, just that the mouse click does not trigger any actions.

## The dragging/zoom mouse handler ##

With the dragging/zoom mouse handler the actions for index and drawing mode are the same. For slide mode, the following assignment of actions applies:

Dragging/zoom mouse handler actions in slide mode
| **mouse event** | **action** |
|:----------------|:-----------|
| mouse down      | start dragging |
| mouse up        | end dragging |
| mouse move      | drag the slide |
| mouse click     | create ad-hoc view |
| mouse scroll    | zoom in/out |

An ad-hoc view is a view that is created on the fly, without being defined in Inkscape. If an object that is visible in its entirety on the screen is clicked on, a zoom is applied, so that the object fills the screen. If more than one object was under the mouse pointer at the time of the click, the largest entirely visible object is used. If no suitable object for a zoom is found, the slide is zoomed out.

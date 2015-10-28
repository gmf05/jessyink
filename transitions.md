# Transitions #

Currently, there are three different slide transitions available in JessyInk: appear, fade and pop.


Transitions can also be assigned to the master slide where they will act as the default transition for all slides.


## The "appear" transition ##

The "appear" transition is the simplest transition. With this transition the slide simply appears. The effect is instantly. Therefore, the duration setting has no effect on this transition.



![http://jessyink.googlecode.com/files/transition_appear.png](http://jessyink.googlecode.com/files/transition_appear.png)

_Illustration of the "appear" transition._

## The "fade" transition ##

The "fade" transition incrementally increases the opacity of a slide. The time from zero opacity to full opacity can be adjusted using the duration setting.



![http://jessyink.googlecode.com/files/transition_fade.png](http://jessyink.googlecode.com/files/transition_fade.png)

_Illustration of the "fade" transition._

## The "pop" transition ##

The "pop" transition incrementally increases the opacity of a slide and scales it at the same time. As with the "fade" transition, the duration can be adjusted.



![http://jessyink.googlecode.com/files/transition_pop.png](http://jessyink.googlecode.com/files/transition_pop.png)

_Illustration of the "pop" transition._

## Assigning transitions to a slide ##

Using the JessyInk "transition" extension, the transitions for the slides can be set by supplying the name of the layer in the dialog window and selecting the transition type. Different transition types for transitioning in and out can be specified. Furthermore, the duration in seconds of the transition can be specified by setting the corresponding number to a value between 0.1 and 10.0. Please note that the duration has no effect on the transition type "appear", as this transition is instantaneous.


Pressing "apply" saves the changes. The default is for the slides to simply "appear". If transition are specified with a master slide, these transitions will be used as the default transitions.



![http://jessyink.googlecode.com/files/extension_transition.png](http://jessyink.googlecode.com/files/extension_transition.png)

_Dialog window of the transition extension._

## Assigning transitions to the master slide ##

A transition can be assigned to the master slide in the same way that it is assigned to any other slide. If a transition is assigned to the master slide, this transition is used as the default transition for all slides (i.e. if a slide is not assigned a transition, the master slide transition is used).

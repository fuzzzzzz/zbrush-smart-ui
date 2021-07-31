# Smart UI

 > Smart UI plugin is a plugin for Zbrush 2020/2021

## Description

**Smart UI** is a configurable floating ui for **ZBrush 2021**, which can dock on any sides of the canvas, you just assign a hot keyto a toolbars.
**9 toolbars** are available :

* Brushes
* Alphas
* Parametric Geometry modifiers
* Materials
* Macros
* Parametric primitives
* Subtools ( limit to 42 first subtools)
* Views settings
* ZModeler (support custom zmodeler brushes)

You can define custom settings for each of the available toolbars, to display at the **LEFT**, **TOP** , **RIGHT** or **Bottom** of the Zbrush canvas.
You can display as Text or Icons.

TWw modes to exit the Toolbar
You can define how many item to display
You can setup 42 actions per toolbars.
just compute 42*9 and you got a wide number of action ready at your finger tips.

### Warning :
When the toolbar is displayed, you can't interact with the zbrush UI and canvas. So you can exit with :

 * Keyboard input (with **SPACE**, **ESC** or **ENTER**)
 * or Enable Quick exit

**QUESTION**: What is the Quick Exit mode ?

**ANSWER** : You can click anywhere to exit the toobar quickly. But, (of course there is a but), the quick exit consist of a button which cover the whole screen, when we click on that invisible button, the button fade  in and out to full white, but this is how ZBrush interaction with `[INoteButton]` is working, and can't to change this behavior, so if you don't like the flash when exiting thetoolbar, you can simple disble the Quick Exit mode.

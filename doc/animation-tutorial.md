# Slate - Animation Tutorial

In Slate, it's possible to see a preview of how an animation will look. The animation is based on one or more "frames" or "cells" in your image. This tutorial will show one way to create these frames and then go through the process of customising the animation settings.

Firstly, we'll start off with a single frame, composed of three layers:

![Single frame](https://github.com/mitchcurtis/slate/blob/animation-tutorial/doc/images/slate-animation-tutorial-1.png)

The initial project can be downloaded [here](https://github.com/mitchcurtis/slate/blob/animation-tutorial/tests/manual/screenshots/resources/animation-tutorial-1.slp).

We want to have 6 frames in our animation, so we need to increase the size of the canvas. To do so, open the Change Canvas Size dialog by clicking on the tool button in the left-hand side of the toolbar:

![Change Canvas Size](https://github.com/mitchcurtis/slate/blob/animation-tutorial/doc/images/slate-animation-tutorial-1.1.png)

Change the width of the image to 216 pixels and click OK to confirm. Now you should see this:

![Change Canvas Size](https://github.com/mitchcurtis/slate/blob/animation-tutorial/doc/images/slate-animation-tutorial-2.png)

Let's make the transparent background white. Select the "background" layer in the Layers panel. Switch to the Fill tool, and the click on the transparent area to fill it with white. It will look then like this:

![Fill](https://github.com/mitchcurtis/slate/blob/animation-tutorial/doc/images/slate-animation-tutorial-2.1.png)

To make it easier to see which frame is which, we'll add some vertical guides between each one.

In order to drag a guide onto the canvas, the rulers must be visible. Click on the "Show rulers" tool button in the tool bar. Do the same for guides by clicking on the next tool button to the right.

We're going to recreate the following guides:

![Guides](https://github.com/mitchcurtis/slate/blob/animation-tutorial/doc/images/slate-animation-tutorial-2.2.png)

To drag a vertical guide onto the canvas, click on the ruler on the left side of the screen and drag outwards. Repeat this step until there are five vertical guides on the canvas at 36 pixel intervals. Then, drag a horizontal guide onto the canvas so that we have some reference for vertical movement in our animation.

# Processing Art

This was just a quick project to get my feet wet in processing. After enough tweaking, I was pretty happy with the "abstract art" paintings a user could produce with just some mouse motion:

<img src="http://petercottle.com/miscPics/abstract.png"/>

# Demo

You can play with the interface [here](http://petercottle.com/experiment/abstractArt.html) and a faster version [here](http://petercottle.com/experiment/abstractArt_fast.html) .

# Graphic Effects

* The color of the brush particle is based on it's velocity vector which is mapped directly into the HSB color space. The saturation and brightness are computed from the velocity magnitude, which leads to particles that brighten when their speed increases.

* Mouse clicks both grow the size of the brush and induce random jittering, leading to a hand-drawn feel for certain parts of the arcs.



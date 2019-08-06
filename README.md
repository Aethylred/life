# Life, don't talk to me about life...

This is a basic implementation of [Conway's Game of Life](http://en.wikipedia.org/wiki/Conway's_Game_of_Life). I use this on occasion to stress test browersers. When I wrote this in 2008 only Chrome managed to get more than a frame per second, and that was with a 30 x 30 table. The table is now 75 x 75 because it hits the limit set on recursive function calls in some browsers (cowards).

If you'd like to see if your broweser can do better, update the value in `onload="startlife(75)"`, if the table isn't rendered then the JavaScript has crashed out.

Use this [link](https://htmlpreview.github.io/?https://github.com/Aethylred/life/blob/master/life.html) to preview [`life.html`](life.html) in all its CPU consuming glory.

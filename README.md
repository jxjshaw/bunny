bunny
=====
It's the Stanford bunny!  To use it in your projects do

    npm install bunny
      
And then you can access the vertices/faces of the mesh as follows:

    var bunny = require("bunny");
    var positions = bunny.positions;
    var faces = bunny.faces;
    
That's pretty much it.

![](https://raw.github.com/mikolalysenko/bunny/master/images/bunny.png)

Credits
=======
The infamous bunny is part of the [Stanford 3D scanning repository](http://graphics.stanford.edu/data/3Dscanrep/#bunny).  For a short history, see [Greg Turk's page](http://www.cc.gatech.edu/~turk/bunny/bunny.html).

# PIXICAM
A world container which can be viewed through an accompanying camera.

See here:
<a href='http://georgiee.github.io/pixicam/'>Basic Examples</a>
Usage:

```

var options = {
  screenWidth: 5000,
  screenHeight: 700,
  width: 5000,
  height: 500,
  centerX: 0,
  centerY: 0
}

var world = new pixicam.World(worldSize);
world.setScreenSize(500, 500);
world.setSize(5000,1000);
world.setCenter(0,0);

var camera = world.camera;
//now move and zoom the camera

```


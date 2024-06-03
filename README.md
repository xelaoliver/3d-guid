# A BEGINNERS GUIDEBOOK TO 3D

On windows, Ctrl+f and input your querie. On Mac, Cmd+f and input your querie. This allows quick searches in this file.

> Add more to the introduction

### 3D PROJECTION

The basics of 3D projection start by transforming the x, y& z coordinates into x& y to display onto the screen. This can be accomplished by using this script:

````
focalLength=400

x*(focalLength/z)
y*(focalLength/z)
````

The _focalLength_ is usually set to 400 because it gives a convincing illusion of perspective.

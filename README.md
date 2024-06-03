# A BEGINNERS GUIDEBOOK TO 3D

**NOTES**

On windows, Ctrl+f and input your querie. On Mac, Cmd+f and input your querie. This allows quick searches in this file.

> Some of the scripts may vary due to the variety of programming languages. In all examples, the scripts are presented as an mathematical expression.

### 3D PROJECTION

The basics of 3D projection start by transforming the x, y& z coordinates into x& y to display onto the screen. This can be accomplished by using this script:

````
focalLength=400

x*(focalLength/z)
y*(focalLength/z)
````

The _focalLength_ is usually set to 400 because it gives a convincing illusion of perspective.

### CAMERA ROTATION MATRICES

3D engines use rotation matrices that require trigonometric calculations to rotate each vertex correctly and and consistant speeds. This can be accomplished by using these scripts:

**X ROTATION MATRIX**

```
z*sin(XCameraRoation)+x*cos(XCameraRotation)
z*cos(XCameraRoation)-x*sin(XCameraRotation)
```

**Y ROTATION MATRIX**

```
z*sin(YCameraRoation)+y*cos(YCameraRotation)
z*cos(YCameraRoation)-y*sin(YCameraRotation)
```

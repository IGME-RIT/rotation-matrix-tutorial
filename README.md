# Rotation Matrix Tutorial

This is a demonstration of using a rotation matrix to describe an orientation in 3D space.

# About

This demo contains 3 lines representing the 3 cardinal axes:	X (red), Y (green), and Z (blue). These can be rotated to any orientation.

A rotation matrix is a collection of 9 scalars arranged in a 3x3 matrix. The rotation matrix has special properties including:
  - Each column represents the object's local X, Y, and Z axes in world space
  - A rotation applied from a matrix can easily be reversed by applying the inverse of that matrix
  - The inverse of a rotation matrix is the transpose
  - Multiplying two rotation matrices together gets a rotation matrix which, when applied, has the same result as the two separate matrices

In this simulation the Q and E buttons will alter the Y component of the axis of rotation. W and S will alter the X component of the axis of rotation. A and D will alter the Z component of the axis of rotation.

# Setup

In order to setup, run the following in a shell, then open the project in your preferred editor. Windows setup has been configured for use with Visual Studio.

Windows:
```
cd path/to/folder
setup.cmd
```
Linux:
```
cd path/to/folder
./setup
```

# Credits

For more reading, check out [3D Math Primer for Graphics and Game Development](http://www.amazon.com/Primer-Graphics-Development-Wordware-Library/dp/1556229119) by Fletcher Dunn & Ian Parberry

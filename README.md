This is a **WIP** fork of [phaser-plugin-isometric](https://github.com/lewster32/phaser-plugin-isometric), refactored to make it work with Phaser 3.5+.

## Description
Phaser Isometric is a comprehensive axonometric plugin for Phaser which provides an API for handling axonometric projection of assets in 3D space to the screen.
The goal has been to mimic as closely as possible the existing APIs provided by Phaser for standard orthogonal 2D projection, but add a third dimension.
Also included is an Arcade-based 3D AABB physics engine, which again is closely equivalent in functionality and its API.

## Features

* Familiar Phaser API - if you've grasped the basics of Phaser, you can use this!
* 3D geometry helpers in the form of Point3 and Cube
* Adjustable axonometric projection angle to allow for classic 2:1 pixel dimetric, true 120° isometric or any angle you like via ```scene.isometric.projectionAngle```
* Simple x+y (with z fudging)
* Arcade Physics derived 3D physics engine (**Working, but needs refactoring!**)
* Helpful debug utilities (**Not working yet!**)
* Familiar factory methods added to GameObjectFactory and GameObjectCreator so you can do ```scene.add.isoSprite```
* Refactored to support Phaser 3.5+

## Examples
Check out the [docs](https://github.com/sebashwa/phaser3-plugin-isometric/tree/master/docs) folder and the [github-page](https://sebashwa.github.io/phaser3-plugin-isometric/)

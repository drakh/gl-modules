gl-modules
==========
A guide to WebGL programming using npm and browserify

## Goals

Broadly the goals of this 

* Teach WebGL with minimal amount of magic
* Wrap common verbose tasks in modules to reduce code size and avoid errors
* ... but don't try to abstract stuff that doesn't need it
* Emphasize code reuse


## Assumed knowledge

* Proficiency with JavaScript
* Basic understanding of node.js and npm
* Some familiarity with graphics concepts will be helpful

# Outline

### [Lesson 0: Preliminaries](https://github.com/mikolalysenko/gl-modules/blob/master/Lesson00/README.md)

Topics covered:

* CommonJS modules
* npm and node.js
* browserify
* Interactive work flow, beefy and live-reload
* Deployment/hosting options

Modules introduced:

* [node.js](http://nodejs.org/)
* [npm](https://npmjs.org/)
* [browserify](https://github.com/substack/node-browserify)
* [beefy](https://github.com/chrisdickinson/beefy)

### [Lesson 1: Setting up WebGL](https://github.com/mikolalysenko/gl-modules/blob/master/Lesson01/README.md)

Topics:

* Initializing WebGL

New modules:

* [game-shell](https://github.com/mikolalysenko/game-shell)
* [gl-now](https://github.com/mikolalysenko/gl-now)

### 2D Drawing

Topics:

* Basic 2D drawing
* Buffers
* Shaders
* Uniforms
* Attributes
* Varying variables

New modules:

* [gl-shader](https://github.com/mikolalysenko/gl-shader)
* [gl-buffer](https://github.com/mikolalysenko/gl-buffer)

### Textures

Topics:

* Multidimensional arrays
* Textures
* ndarrays for images
* Mipmapping

New modules:

* [ndarrays](https://github.com/mikolalysenko/ndarray)
* [gl-texture2d](https://github.com/mikolalysenko/gl-texture2d)

### Framebuffers

Topics:

* Framebuffers
* Offscreen rendering
* Feedback effects
* Basic GPGPU programming

New modules:

* [gl-fbo](https://github.com/mikolalysenko/gl-fbo)

### Coordinate Transformations

Topics:

* Active vs. passive transformations
* Coordinate transformations
* Homogenous coordinates
* Clipping frustum
* Cameras and model matrices

New modules:

* [gl-matrix](https://github.com/toji/gl-matrix)

### Indexed geometry

Topics:

* Element arrays
* Meshes
* Vertex array objects

New modules:

* [gl-vao](https://github.com/mikolalysenko/gl-vao)

# Links

[Overview of graphics pipeline](http://acko.net/files/fullfrontal/fullfrontal/webglmath/online.html)

[WebGL specification](http://www.khronos.org/registry/webgl/specs/latest/)

# Credits
(c) 2013 Mikola Lysenko. MIT License
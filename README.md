# Model View Projection
## Understanding WebGL coordinate spaces

This content kit explores how to take data within a WebGL project, and project it into the proper spaces to display it on the screen. It assumes a knowledge of basic matrix math using translation, scale, and rotation matrices. It explains the three core matrices that are typically used to represent a 3d object: the model, view and projection matrices.

Lesson          | JSFiddle                                                       | Code
--------------- | -------------------------------------------------------------- | --------------------------------------------
Clip Space                  | TODO   | [01-clip-space](lessons/01-clip-space)
Homogeneous Coordinates     | TODO   | [02-homogeneous-coordinates](lessons/02-homogeneous-coordinates)
Model Matrix                | TODO   | [03-model-transform](lessons/03-model-transform)
Divide by W                 | TODO   | [04-divide-by-w](lessons/04-divide-by-w)
Simple Projection           | TODO   | [05-simple-projection](lessons/05-simple-projection)
Perspective Matrix          | TODO   | [06-perspective-matrix](lessons/06-perspective-matrix)
View Matrix                 | TODO   | [07-view-matrix](lessons/07-view-matrix)

## Getting started

The lessons can either be worked online from JSFiddle, or downloaded and explored locally. The content of the lessons is mixed in with the code. The `script.js` files contain most of the lesson, while the `index.html` contains the HTML and shader code. To download these files either [download the zip file](https://github.com/TatumCreative/mdn-model-view-projection/archive/master.zip) or run `git clone git@github.com:TatumCreative/mdn-model-view-projection.git`.

## Lesson requirements

These lessons require a [browser and device that support WebGL](https://get.webgl.org/). The browsers that support WebGL are Firefox 4+, Google Chrome 9+, Opera 12+, Safari 5.1+ and Internet Explorer 11+. Be aware that not all devices support these features. There are many tutorials available throughout the web on graphics programming, but this content kit specifically targets web developers. It's assumed that the audience is familiar with intermediate level web development, markup, and JavaScript.

## Updates and Correction

[Submit an issue](./issues) or a [pull request](https://help.github.com/articles/using-pull-requests/) for any corrections or updates. For a history of the updates visit the [commit history](https://github.com/TatumCreative/mdn-model-view-projection/commits/master).
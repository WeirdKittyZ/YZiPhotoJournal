# Y &middot; Zi's Photo Journal

This website uses the [PHOTORAMA](https://github.com/sunbliss/photorama) theme. Check out this page for download instructions.

## To upload photo 
 - Select a gallery folder
 - Add gallery and gallery cover photo in  _gallery/index.html_, under **images:**
```sh
     - image_path: /gallery/gallery#/g#b#.JPG
       gallery-folder: /gallery/gallery#/
       gallery-name: "" ##same as album-title below##
       gallery-date: ""
```
 - Create a new folder _gallery/gallery#_
   - upload images to this file
   - this folder should include _gallery/gallery##/index.html_
 ```sh
---
layout: album
title: ""
description: ""
active: gallery
header-img: "img/gallery-bgII.jpeg"
album-title: "" ##same as gallery-name above##
images:
 - image_path: /gallery/gallery#/g#b#.JPG
   caption: 
   copyright: © YZi Photo Journal
images:
 - image_path: /gallery/gallery#/g#b#.JPG
   caption: 
   copyright: © YZi Photo Journal
---
```

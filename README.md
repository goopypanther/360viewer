360viewer
=========

Lightweight 360 degree panoramic image viewer using [aframe](https://aframe.io).

Installing
----------

Just put it into a web-accessable directory. Everything is javascript & html5.
Image files can be anywhere on the same server. (Aframe blocks cross-origin requests by default.)

Usage
-----

Add an img parameter to the query string to view an image. For example:

http://mycoolwebsite.com/360viewer.html?img=coolPanoramicImage.jpg

Currently images need to be fully spherical. It would be fairly easy to modify the code to wrap a rectangular panorama around the inside of a cylinder.

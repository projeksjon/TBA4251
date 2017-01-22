[![TBA4251](https://infinite-plains-41468.herokuapp.com/images/logo_orange_shdw.png)](https://infinite-plains-41468.herokuapp.com/)
# TBA4251, Programming in Geomatics

## About
This vector based web Geographic informationsystem is developed as a project in the course "Programming in Geomatics" at NTNU. The aim of the course is to combine computer science with knowledge of geographic information systems. The subject is self-tought, and is a chance to experience a process of developing a web application and a geographic information system from start to end. The process involves everything form the choice of technology to design and implementation.

[TBA4251](https://infinite-plains-41468.herokuapp.com/)

In this project, my focus have been on making a geographic informationsystem that are easy to use and with a nice user experience. The application may be used on any device, PC as well as a mobile phone (I have not been able to test the application on Apple-products, and can therefore not guarantee full compatibility with these kind of devices).

## Use
### Functionality:

* Change color, opacity and name of layer
* Download layer
* Delete layer
* Hide and view layer
* Zoom/pan to layer
* Change layer order
* Spatial operations
  * Buffer
  * Union
  * Intersect
  * Difference

### How to use:
```
$ heroku create
$ git push heroku master
$ heroku open
```

## Documentation
Most of the magic happens in Geometry.js and in Main.js

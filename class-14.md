# Transforms

The transform property comes in two different settings, two-dimensional and three-dimensional 
 
 1. 2D Rotate 
 The rotate value provides the ability to rotate an element from 0 to 360 degrees.
 
 ```
 .box-1 {
  transform: rotate(20deg);
}
.box-2 {
  transform: rotate(-55deg);
}


 ```
 
 ![](http://www.coolwebmasters.com/uploads/posts/2010-02/1265196287_css-01.png)
 
 2. 2D Scale 
  allows you to change the appeared size of an element. The default scale value is 1, therefore any value between .99 and .01 makes an element appear smaller while any value greater than or equal to 1.01 makes an element appear larger.
  
  ```         
.box-1 {
  transform: scale(.75);
}
.box-2 {
  transform: scale(1.25);
}

```

3. 2D Translate
with the scale value, to set both the x and y axis values at once, use the translate value and declare the x axis value first, followed by a comma, and then the y axis value.
```
.box-1 {
  transform: translateX(-10px);
}
.box-2 {
  transform: translateY(25%);
}
.box-3 {
  transform: translate(-10px, 25%);
}


```

4. 2D Skew
is used to distort elements on the horizontal axis, vertical axis, or both

```
.box-1 {
  transform: skewX(5deg);
}
.box-2 {
  transform: skewY(-20deg);
}
.box-3 {
  transform: skew(5deg, -20deg);
}

```

![](https://miro.medium.com/max/2400/1*_NVMTnvHTM9teQxrVRlDeg.png)


# CSS Transitions
CSS transitions allows you to change property values smoothly, over a given duration.

```
Their properties :

transition
transition-delay
transition-duration
transition-property
transition-timing-function

```


  

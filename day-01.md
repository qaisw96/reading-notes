# Responsive web design 

the practice of building a website suitable to work on every device and every screen size, no matter how large or small, mobile or desktop.


broken down into three main components : 

+ flexible layouts
+ media queries
+ flexible media


## Flexible Grid


```
Using the flexible grid formula we can take all of the fixed units of length and turn them into relative units :


target ÷ context = result

```

for example : 

```
HTML

<div class="container">
  <section>...</section>
  <aside>...</aside>
</div>

```

```
CSS

section,
aside {
  margin: 1.858736059%; /*  10px ÷ 538px = .018587361 */
}
section {
  float: left;
  width: 63.197026%;    /* 340px ÷ 538px = .63197026 */   
}
aside {
  float: right;
  width: 29.3680297%;  /* 158px ÷ 538px = .293680297 */
}


```


## Media Queries 

 provide the ability to specify different styles for individual browser and device circumstances, the width of the viewport or device orientation


There are a couple different ways to use media queries :

1. using the @media rule inside of an existing style sheet, importing a new style sheet using the @import rule
2. linking to a separate style sheet from within the HTML document




# Float

There are four valid values for the float property :
+ Left 
+ Right
+ None (the default) ensures the element will not float
+ Inherit which will assume the float value from that elements parent element.


![](https://i1.wp.com/css-tricks.com/wp-content/csstricks-uploads/print-layout.png?resize=540%2C270&ssl=1)

# What's a Table?

A table represents information in a grid format.
Examples of tables include financial reports, TV
schedules, and sports results.

```
Note: The <td> elements are the data containers of the table.
They can contain all sorts of HTML elements; text, images, lists, other tables, etc.
```

```
A simple HTML table:

<table style="width:100%">
  <tr>
    <th>Firstname</th>
    <th>Lastname</th>
    <th>Age</th>
  </tr>
  <tr>
    <td>Jill</td>
    <td>Smith</td>
    <td>50</td>
  </tr>
  <tr>
    <td>Eve</td>
    <td>Jackson</td>
    <td>94</td>
  </tr>
</table>

```

```
<thead> =====> The headings of the table should sit inside the <thead> element.
<tbody> =====> The body should sit inside th element.
<tfoot> =====> The footer belongs inside the element
```

![table](http://ictacademy.com.ng/wp-content/uploads/2017/10/HTML-Table-Structure.png)



> ## WHAT ARE BUILT-IN OBJECTS? 
>> + BROWSER OBJECT MODEL :
The Browser Object Model contains
objects that represent the current
browser window or tab. It contains
objects that model things like
browser history and the
device's screen. 
>> + DOCUMENT OBJECT MODEL :
The Document Object Model uses
objects to create a representation of
the current page. It creates a new
object for each element (and each
individual section of text)
within the page.
>> + GLOBAL JAVASCRIPT OBJECTS
The global JavaScript objects
represent things that the JavaScript
language needs to create a model
of. For example, there is an
object that deals only with
dates and times. 

![DOM](https://simplesnippets.tech/wp-content/uploads/2018/10/what-is-document-object-model-in-JS-featured-image.jpg)

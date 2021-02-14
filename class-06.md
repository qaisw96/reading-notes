## JS Object 


Objects group together a set of variables and functions to create a model
of a something you would recognize from the real world. In an object,
variables and functions take on new names. 

```
var person = {
  firstName: "John",
  lastName: "Doe",
  age: 50,
  eyeColor: "blue"
};

```


## To access an object :

```
objectName.propertyName

or

objectName["propertyName"]
```

## The Document Object Model (DOM) specifies
how browsers should create a model of an HTML
page and how JavaScript can access and update the
contents of a web page while it is in the browser window. 


![dom](https://www.w3schools.com/js/pic_htmltree.gif)




> ## With the object model, JavaScript gets all the power it needs to create dynamic HTML:

>> + JavaScript can change all the HTML elements in the page
>> + JavaScript can change all the HTML attributes in the page
>> + JavaScript can change all the CSS styles in the page
>> + JavaScript can remove existing HTML elements and attributes
>> + JavaScript can add new HTML elements and attributes
>> + JavaScript can react to all existing HTML events in the page
>> + JavaScript can create new HTML events in the page


## Accessing and updating the DOM tree involves two steps:

```
1. Locate the node that represents the element you want to work with.
2. Use its text content, child elements, and attributes. 
```

## Finding HTML Elements

Method | Description
-------|---------
document.getElementById(id)	| Find an element by element id
document.getElementsByTagName(name)	| Find elements by tag name
document.getElementsByClassName(name)	| Find elements by class name


## TRAVERSING THE DOM 

```
When you have an element node, you can select
another element in relation to it using these five
properties
```

![dom](https://www.qualitestgroup.com/images/howto/DOMTree_HowTo.png)

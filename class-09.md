# HTML Form

## Why Forms?
The HTML form element is used to create an HTML form for user input



The ```<form>``` element is a container for different types of input elements, such as: text fields, checkboxes, radio buttons, submit buttons, etc.

Type |	Description
-----|-------------
```<input type="text">```	| Displays a single-line text input field
```<input type="radio">``` |	Displays a radio button (for selecting one of many choices)
```<input type="checkbox">``` |	Displays a checkbox (for selecting zero or more of many choices)
```<input type="submit">```	| Displays a submit button (for submitting the form)
```<input type="button">```	| Displays a clickable button


![](https://cdn-stack.compsmag.com/wp-content/uploads/2021/02/Login-Page-with-HTML5-Forms-Tips-and-Tutorial-583x350.jpg)


```
<form action="http://www.example.com/login.php">
<p>Username:
 <input type="text" name="username" size="15"
 maxlength="30" />
</p>
</form>
```

## CSS Lists 
```
In HTML, there are two main types of lists:

unordered lists (<ul>) - the list items are marked with bullets
ordered lists (<ol>) - the list items are marked with numbers or letters
The CSS list properties allow you to:

Set different list item markers for ordered lists
Set different list item markers for unordered lists
Set an image as the list item marker
Add background colors to lists and list items
```


## JavaScript Events
Event handlers can be used to handle and verify user input, user actions, and browser actions
```
Things that should be done every time a page loads
Things that should be done when the page is closed
Action that should be performed when a user clicks a button
Content that should be verified when a user inputs data
And more ...
```

## UI EVENTS 
Occur when a user interacts with the browser's user interface (UI) rather than the web page
EVENT | DESCRIPTION
--------|--------
load | Web page has finished loading
unload | Web page is unloading (usually because a new page was requested)
error | Browser encounters a JavaScript error or an asset doesn't exist
resize | Browser window has been resized
scroll | User has scrolled up or down the page

## KEYBOARD EVENTS
Occur when a user interacts with the keyboard (see also input event)

EVENT | DESCRIPTION
--------|-------
keydown | User first presses a key (repeats while key is depressed)
keyup | User releases a key
keypress | Character is being inserted (repeats while key is depressed)

## MOUSE EVENTS
Occur when a user interacts with a mouse. trackpad, or touchscreen
EVENT | DESCRIPTION
-------| --------
click | User presses and releases a button over the same element
dbl click |  User presses and releases a button twice over the same element
moused | own User presses a mouse button while over an element
mouseup | User releases a mouse button while over an element
mousemove | User moves the mouse (not on a touchscreen)
mouseover | User moves the mouse over an element (not on a touchscreen)
mouseout | User moves the mouse off an element (not on a touchscreen)

## HOW EVENTS TRIGGER JAVASCRIPT CODE

1. SELECT ELEMENT 
```
The element that users are
interacting with is the text input
where they enter the username.
```
2. SPEC!FY EVENT 
```
When users move out of the
text input, it loses focus, and the
blur event fires on this element
```
3.CALL CODE 
```  
When the blur event fires
on the username input, it
will trigger a function called
chec kUsername ()
```

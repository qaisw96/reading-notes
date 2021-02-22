# HTML5 Storage 
 it’s a way for web pages to store named key/value pairs locally, within the client web browser, Unlike cookies, this data is never transmitted to the remote web server (unless you go out of your way to send it manually)
 
 HTML5 STORAGE SUPPORT
IE	| FIREFOX |	SAFARI |	CHROME |	OPERA |	IPHONE |	ANDROID
----|--------|---------|---------|---------|--------|--------
8.0+ |	3.5+	| 4.0+ |	4.0+	| 10.5+ |	2.0+ |	2.0+


## USING HTML5 STORAGE
The data can be any type supported by JavaScript, including strings, Booleans, integers, or floats. However, the data is actually stored as a string. If you are storing and retrieving anything other than strings, you will need to use functions like parseInt() or parseFloat() to coerce your retrieved data into the expected JavaScript datatype.

```
HTML web storage provides two objects for storing data on the client:

window.localStorage - stores data with no expiration date
window.sessionStorage - stores data for one session (data is lost when the browser tab is closed)

```

Before using web storage, check browser support for localStorage and sessionStorage:

```
if (typeof (Storage) !== "undefined") {

    console.log("Code for localStorage/sessionStorage.")
   
} else {
    
    console.log("Sorry! No Web Storage support..")
}


```


## The localStorage Object
The localStorage object stores the data with no expiration date. The data will not be deleted when the browser is closed, and will be available the next day, week, or year.
```
Example

// Store
localStorage.setItem("lastname", "Smith");

// Retrieve
document.getElementById("result").innerHTML = localStorage.getItem("lastname");
Example explained:

Create a localStorage name/value pair with name="lastname" and value="Smith"
Retrieve the value of "lastname" and insert it into the element with id="result"

````

## The sessionStorage Object
The sessionStorage object is equal to the localStorage object, except that it stores the data for only one session. The data is deleted when the user closes the specific browser tab.

The following example counts the number of times a user has clicked a button, in the current session:
```
Example

if (sessionStorage.clickcount) {
  sessionStorage.clickcount = Number(sessionStorage.clickcount) + 1;
} else {
  sessionStorage.clickcount = 1;
}
document.getElementById("result").innerHTML = "You have clicked the button " +
sessionStorage.clickcount + " time(s) in this session.";

```

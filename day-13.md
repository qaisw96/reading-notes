# The method attribute
The method attribute defines how data is sent. The HTTP protocol provides several ways to perform a request; 
HTML form data can be transmitted via a number of different methods, the most common being the GET method and the POST method

# The GET method

```
used by the browser to ask the server to send back a given resource: "Hey server, I want to get this resource.
" In this case, the browser sends an empty body. Because the body is empty, 
if a form is sent using this method the data sent to the server is appended to the URL.

```

## for example :
```
<form action="http://www.foo.com" method="GET">
  <div>
    <label for="say">What greeting do you want to say?</label>
    <input name="say" id="say" value="Hi">
  </div>
  <div>
    <label for="to">Who do you want to say it to?</label>
    <input name="to" id="to" value="Mom">
  </div>
  <div>
    <button>Send my greetings</button>
  </div>
</form>


```

#The POST method

 method the browser uses to talk to the server when asking for a response that takes into account the data provided in the body of the HTTP request: 
 "Hey server, take a look at this data and send me back an appropriate result." 
 If a form is sent using this method, the data is appended to the body of the HTTP request.
 
 

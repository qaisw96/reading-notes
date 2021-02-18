# Debagging & Errors JS 

```
Each time a script enters a new execution context
there are two phases of activity :

1: PREPARE
• The new scope is created
• Variables, functions, and arguments are created
• The value of the this keyword is determined 

2: EXECUTE
• Now it can assign values to variables
• Reference functions and run their code
• Execute statements
```





## ERROR OBJECTS
Error objects can help you find where your mistakes are
and browsers have tools to help you read them. 


When an Er ror object is created, it will contain the
following properties:

PROPERTY | DESCRIPTION
---------|-----------
name | Type of execution
message | Description
fileNumber | Name of the JavaScript file
lineNumber | Line number of error

## There are several types of built-in error objects in JavaScrip

Error Name |	Description	
----------|-----------
EvalError |	An error has occurred in the eval() function. Note: Newer versions of JavaScript does not throw any EvalError. Use SyntaxError instead.	 
RangeError |	A number "out of range" has occurred	
ReferenceError |	An illegal reference has occurred	
SyntaxError |	A syntax error has occurred	
TypeError	| A type error has occurred	
URIError	| An error in encodeURI() has occurred



## A DEBUGGING WORKFLOW

## WHERE IS THE PROBLEM?
```
First, should try to can narrow down the area where
the problem seems to be. In a long script, this is
especially important.

1. Look at the error message, it tells you:
• The relevant script that caused the problem.
• The line number where it became a problem for
the interpreter

2. Check how far the script is running.
Use tools to write messages to the console to tell
how far your script has executed.

3. Use breakpoints where things are going wrong.
They let you pause execution and inspect the values
that are stored in variables. 
```

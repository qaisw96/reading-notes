# EJS 
is a simple templating language that lets you generate HTML markup with plain JavaScript 

## EJS Features : 

+ Fast compilation and rendering
+ Simple template tags: <% %>
+ Both server JS and browser support
+ Complies with the Express view system


## Tags 

Tag | use 
----- | -----
<%   | for control-flow, no output
<%_  |  Slurping’ Scriptlet tag, strips all whitespace before it
<%=  | Outputs the value into the template (HTML escaped)
<%-  | Outputs the unescaped value into the template
<%#  | Comment tag, no execution, no output
<%% | Outputs a literal '<%'
%> | Plain ending tag
-%> | Trim-mode ('newline slurp') tag, trims following newline
_%> | ‘Whitespace Slurping’ ending tag, removes all whitespace after it

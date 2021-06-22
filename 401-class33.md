## When to Use Context

+ Context is designed to share data that can be considered “global” for a tree of React components, such as the current authenticated user, theme, or preferred language
+ Context is primarily used when some data needs to be accessible by many components at different nesting levels. Apply it sparingly because it makes component reuse more difficult.


## Dream State
```
 snackbar system must easy to use and generally be very lightweight. We want to be able to place one on the screen with 
 just a couple of lines of code. Anything more and it’s overkill.
This means forget render props and higher order components.
We don’t want to deal with a messy React tree and wrappers. We don’t want action creators, reducers*, or any of that stuff.

```

## Globally Accessible
```

The state of our snackbars (which ones are visible) can be localized to a single centralized component. 
That same centralized component can be responsible for rendering them. There’s really no need for another
component somewhere in the tree to hook into that state (at least not in our use-case).


```


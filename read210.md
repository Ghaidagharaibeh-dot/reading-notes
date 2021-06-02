# Error Handling & Debugging
## Three ways to discover error
-  THE CONSOLE &
DEV TOOLS
Tools built into the browser
that help you hunt for errors. 
-  COMMON
PROBLEMS
Common sources of errors,
and how to solve them.
- HANDLING
ERRORS
How code can deal with
potential errors gracefully.

### ORDER OF EXECUTION
To find the source of an error, it helps to know how scripts are processed.
The order in which statements are executed can be complex; some tasks
cannot complete until another statement or function has been run: 
 ## How events trigger avascrtpt  
 When the user interacts with the HTML on a web page, there are three
steps involved in getting it to trigger some JavaScript code.
Together these steps are known as event handling. 
- Select t he element
node(s) you want the
script to respond to.
For example, if you want to
trigger a function when a user
clicks on a specific link, you need
to get the DOM node for that
link element. You do this using a
DOM query (see Chapter 5). 
- Indicate which event on
the selected node(s) will
trigger the response.
Programmers call this binding an
event to a DOM node.
The previous two pages showed
a selection of the popular events
that you can monitor for.
- State the code you want
to run when the event
occurs.
W hen the event occurs, on a
specified element, it will trigger
a function. This may be a named
or an anonymous function. 
##  How event handling can be used to provide feedback to users filling in a registration form.
- Select element

The element that users are
interacting with is the text input
where they enter the username. 
- spacify event

When users move out of the
text input, it loses focus, and the
blur event fires on this element.
- call code 

When the blur event fires
on the username input, it
will trigger a function called
chec kUsername ().This function
checks if the username is less
than 5 characters.



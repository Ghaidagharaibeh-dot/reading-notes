# What is a ‘Controlled Component’?

combine the two by making the React state be the “single source of truth”. Then the React component that renders a form also controls what happens in that form on subsequent user input. An input form element whose value is controlled by React.
### Should we wait to store the users responses from the form into state when they submit the form OR should we update the state with their responses as soon as they enter them? Why.
his form has the default HTML form behavior of browsing to a new page when the user submits the form. If you want this behavior in React, it just works. But in most cases, it’s convenient to have a JavaScript function that handles the submission of the form and has access to the data that the user entered into the form. The standard way to achieve this is with a technique called “controlled components”.


# Why would we use a ternary operator
A ternary operator allows you to assign one value to the variable if the condition is true, and another value if the condition is false. ... A ternary operator makes the assignment of a value to a variable easier to see, because it's contained on a single line instead of an if else block

# Rewrite the following statement using a ternary statement:

 if(x===y){
 console.log(true);
  } else {
 console.log(false);
  }
  
let num;
  let x;
  let y;
  num.driver (x === y)?  console.log(true)
 :  console.log(false);
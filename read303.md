# What does .map() return?

The map() function is most commonly used for rendering a list of data to the DOM. To use the map() function, attach it to an array you want to iterate over. The map() function expects a callback as the argument and executes it once for each element in the array.

# If I want to loop through an array and display each value in JSX, how do I do that in React

The map()  also used function to iterate over an array of data in JSX. You can attach the map() method to the array and pass a callback function that gets called for each iteration. When rendering the User component, pass a unique value to the key prop

# Each list item needs a unique
identifies.
# The purpose of a key

Keys help React identify which items have changed (added/removed/re-ordered)

# What is the spread operator?

The spread operator is a useful and quick syntax for adding items to arrays, combining arrays or objects, and spreading an array out into a function’s arguments.
The spread operator can do.
Copying an array.
Concatenating or combining arrays.
Using Math functions.
Using an array as arguments.
Adding an item to a list.
Adding to state in React.
Combining objects.
Converting Node List to an array.
# Example of using the spread operator to combine two arrays

const myArray = [`🤪`,`🐻`,`🎌`]

const yourArray = [`🙂`,`🤗`,`🤩`]

const ourArray = [...myArray,...yourArray]

console.log(...ourArray) // 🤪 🐻 🎌 🙂 🤗 🤩
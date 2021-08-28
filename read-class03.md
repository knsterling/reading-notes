**What does .map() return?**
A new array of numbers doubled their values.

**If I want to loop through an array and display each value in JSX, how do I do that in React?**
by using the map() function and assigning the resulting array of elements to listItems.

**Each list item needs a unique ____.**
key

**What is the purpose of a key?**
To identify which items have changed, are added, or are removed.

**What is the spread operator?**
A syntax for adding items to arrays, combining arrays or objects, and spreading an array out into a function’s arguments.

**List 4 things that the spread operator can do.**
Copying an array, Concatenating or combining arrays, Using Math functions, and Using an array as arguments.

**Give an example of using the spread operator to combine two arrays.**
const myArray = [`🤪`,`🐻`,`🎌`]
const yourArray = [`🙂`,`🤗`,`🤩`]
const ourArray = [...myArray,...yourArray]
console.log(...ourArray) // 🤪 🐻 🎌 🙂 🤗 🤩

**Give an example of using the spread operator to add a new item to an array.**
<!-- const fewFruit = ['🍏','🍊','🍌']
const fewMoreFruit = ['🍉', '🍍', ...fewFruit]
console.log(fewMoreFruit) //  Array(5) [ "🍉", "🍍", "🍏", "🍊", "🍌" ] -->

**Give an example of using the spread operator to combine two objects into one.**
<!-- const objectOne = {hello: "🤪"}
const objectTwo = {world: "🐻"}
const objectThree = {...objectOne, ...objectTwo, laugh: "😂"}
console.log(objectThree) // Object { hello: "🤪", world: "🐻", laugh: "😂" }
const objectFour = {...objectOne, ...objectTwo, laugh: () => {console.log("😂".repeat(5))}}
objectFour.laugh() // 😂😂😂😂😂 -->

**In your own words, what does the increment function do?**
the increment operator increments and returns the value before incrementing.

**How can you pass a method from a parent component into a child component?**
By the parent component passing props to the child component and the child accessing the data from the parent via 'this.props'.

**How does the child component invoke a method that was passed to it from a parent component?**
by using '(props)'

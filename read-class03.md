**What does .map() return?**
A new array of numbers doubled their values.

**If I want to loop through an array and display each value in JSX, how do I do that in React?**
by using the map() function and assigning the resulting array of elements to listItems.

**Each list item needs a unique ____.**
key

**What is the purpose of a key?**
To identify which items have changed, are added, or are removed.

**What is the spread operator?**
A syntax for adding items to arrays, combining arrays or objects, and spreading an array out into a functionβs arguments.

**List 4 things that the spread operator can do.**
Copying an array, Concatenating or combining arrays, Using Math functions, and Using an array as arguments.

**Give an example of using the spread operator to combine two arrays.**
const myArray = [`π€ͺ`,`π»`,`π`]
const yourArray = [`π`,`π€`,`π€©`]
const ourArray = [...myArray,...yourArray]
console.log(...ourArray) // π€ͺ π» π π π€ π€©

**Give an example of using the spread operator to add a new item to an array.**
const fewFruit = ['π','π','π']
const fewMoreFruit = ['π', 'π', ...fewFruit]
console.log(fewMoreFruit) //  Array(5) [ "π", "π", "π", "π", "π" ]

**Give an example of using the spread operator to combine two objects into one.**
const objectOne = {hello: "π€ͺ"}
const objectTwo = {world: "π»"}
const objectThree = {...objectOne, ...objectTwo, laugh: "π"}
console.log(objectThree) { hello: "π€ͺ", world: "π»", laugh: "π" }
const objectFour = {...objectOne, ...objectTwo, laugh: () => {console.log("π".repeat(5))}}
objectFour.laugh()  

**In your own words, what does the increment function do?**
the increment operator increments and returns the value before incrementing.

**How can you pass a method from a parent component into a child component?**
By the parent component passing props to the child component and the child accessing the data from the parent via 'this.props'.

**How does the child component invoke a method that was passed to it from a parent component?**
by using '(props)'

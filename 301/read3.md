# Reading :

1- map() function returns a map object(which is an iterator) of the results after applying the given function to each item of a given iterable

2- using map().






# The Spread Operator:




1- JavaScript, spread syntax refers to the use of an ellipsis of three dots (…) to expand an iterable object into the list of arguments.




2- Copying an array , Concatenating or combining arrays, Using Math functions, Using an array as arguments





3- * const myArray = [`🤪`,`🐻`,`🎌`]


* const yourArray = [`🙂`,`🤗`,`🤩`]


* const ourArray = [...myArray,...yourArray]


 * console.log(...ourArray) // 🤪 🐻 🎌 🙂 🤗 🤩




 
 
 4- * const fewFruit = ['🍏','🍊','🍌']

 * const fewMoreFruit = ['🍉', '🍍', ...fewFruit]

* console.log(fewMoreFruit) //  Array(5) [ "🍉", "🍍", "🍏", "🍊", "🍌" ]







5- * const objectOne = {hello: "🤪"}
* const objectTwo = {world: "🐻"}

* const objectThree = {...objectOne, ...objectTwo, laugh: "😂"}

* console.log(objectThree) // Object { hello: "🤪", world: "🐻", laugh: "😂" }

* const objectFour = {...objectOne, ...objectTwo, laugh: () => {console.log("😂".repeat(5))}}

* objectFour.laugh() // 😂😂😂😂😂












## Things I want to know more about

i want to learn about map
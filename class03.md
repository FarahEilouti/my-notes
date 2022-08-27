# class 03
## _Passing Functions as Props_
#
- What does .map() return?
#### It returns a new array
#
- If I want to loop through an array and display - each value in JSX, how do I do that in React?
#### we create a component that will render a user item, and then we can iterate it using map() or the regular for loop. for the map method; we attach it to an array we've created and pass a callback function that'll be called each iteration.
#
- Each list item needs a unique ____.
#### key
#
- What is the purpose of a key?
#### keys tell react of the occured changes upon items, like adding or removing, and identifies them. 
#
- What is the spread operator?
#### A syntax which eases the process of adding items into an array, and expands it into indivisual elements. 
#
- List 4 things that the spread operator can do.
#### making shallow copies, adding items, combining arrays, spreading an array.
#
- Give an example of using the spread operator to combine two arrays.
#### const cars = ['🚗', '🚙'];
const trucks = ['🚚', '🚛']; 

const combined2 = [...cars, ...trucks];

result: [ '🚗', '🚙', '🚚', '🚛' ]
#
- Give an example of using the spread operator to add a new item to an array.
#### const myLetters = ['A' ,'B' ,'C'];
const myNewLetters = ['d', 'e', ...myLetters];

result:  [ 'd', 'e', 'A', 'B', 'C' ]
#
- Give an example of using the spread operator to combine two objects into one.
#### let user1 = {name : "John", age : 20 };
let user2 = {name : "Ram", salary: '20K' };

let userCopy = {...user1, ...user2};

result: {name : "Ram", age :20 , salary : '20K'};
#
- In the video, what is the first step that the developer does to pass functions between components?
#### creating a function where the state exists.

#
- In your own words, what does the increment function do?
#### an increment function takes any value from the user and adds count to it  depending on user's choice
#
- How can you pass a method from a parent component into a child component?
#### we can use "this", similar to how props work. 
#
- How does the child component invoke a method that was passed to it from a parent component?
#### by calling the method using props in the child component.
#
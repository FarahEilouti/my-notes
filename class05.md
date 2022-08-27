# class 05
## _Putting it all together_
#
- What is the single responsibility principle and how does it apply to components?
#### This means that one component is responsible for only one responsiblity
#
- What does it mean to build a ‘static’ version of your application?
#### Static makes an application displayed but can't be used or not interactive. 
#
- Once you have a static application, what do you need to add?
#### functionality and react components for interactions
#
- What are the three questions you can ask to determine if something is state?
#### if they are mutable, if they can be defined in the component itself, if it's set and can be updated by an object... then they're states.
#
- How can you identify where state needs to live?
#### this depends on the use, we determine wether it will be local or global. 
#

- What is a “higher-order function”?
#### a function that can recieve other functions as parameters and return a function.
#
- Explore the greaterThan function as defined in the reading. In your own words, what is line 2 of this function doing?
#### it returns a new function.
#
- Explain how either map or reduce operates, with regards to higher-order functions.
#### because methds like map are shortcuts for longer functions that take space and complexity, it uses callback functions. 
#
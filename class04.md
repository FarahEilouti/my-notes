# class 04
## _React and Forms_
#
- What is a ‘Controlled Component’?
#### controlled components are components that it's data be controlled and handled by the cmponent's state.
#
- Should we wait to store the users responses from the form into state when they submit the form OR should we update the state with their responses as soon as they enter them? Why.
#### It's better to wait until the submission ocuurs, because we won't have missing or undefined attribute due to instant entering of data. 
#
- How do we target what the user is entering if we have an event handler on an input field?
#### By using react states to track interactions
#
- Why would we use a ternary operator?
#### ternary operators can be a shortend way of if stetements.
#
- Rewrite the following statement using a ternary statement:


if(x===y){
  console.log(true);
} else {
  console.log(false);
}

#### answer: 
let temp = ((x===y) 
##
? console.log(true) : console.log(false)
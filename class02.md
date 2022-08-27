# class 02
## _State and Props_
#
- Based off the diagram, what happens first, the ‘render’ or the ‘componentDidMount’?
#### Render first, then componentDidMount
#
- What is the very first thing to happen in the lifecycle of React? 
#### Mounting.
#
- Put the following things in the order that they happen: componentDidMount, render, constructor, componentWillUnmount, React Updates
#### constructor -> render -> componentDidMount -> react update -> componentWillUnmount
#
- What does componentDidMount do?
####  it's where statements run.
#
- What types of things can you pass in the props?
#### it allows passing values from one component to another.
#
- What is the big difference between props and state?
#### the state is internal an is used locally + can't pass data to other components. while the props can pass data from one component to another, which means it's external and can be controlled by whatever renders the component. 
#
- When do we re-render our application?
#### re-render is used when the state change in the parent component, or when the props get changed.
#
- What are some examples of things that we could store in state?
#### strings mostly, and numbers or other objects can be stored too. 
#
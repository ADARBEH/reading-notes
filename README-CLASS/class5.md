

## What is the single responsibility principle and how does it apply to components?

### The idea behind the SRP is that every class, module, or function in a program should have one responsibility/purpose in a program. As a commonly used definition, "every class should have only one reason to change".

## What does it mean to build a ‘static’ version of your application?

#### Static applications and websites render in the user’s browser without the need for server side processing, this means that all the rendering of HTML, CSS, and JavaScript is done on the client side, rather then relying on server side technologies. Whilst traditionally managing static websites and applications may seem like hard work, the medium has come on leaps and bounds over the past few years to the extent that it’s now perfectly feasible to run heavy content, rich media websites, and applications entirely in the browser – Good times!

## What are the three questions you can ask to determine if something is state?
## How can you identify where state needs to live?

##### The first part of thinking in React is identifying where the state should live. Once you've identified data, it should be stated in the application. We need to work out which components rely on the state, which can potentially mutate it and which should own it. This might not be blatantly obvious when we look at our component hierarchy. Remember, React data flow is unidirectional and data flows from the top of a component tree to the bottom. There's a three-step process to identifying which component should own state. Firstly, identify every component that render something based on state. That means the component receives all, or part of the state as props. Then, find a component higher up the tree than all the components that use the state, and put state in this component. This could be an immediate owner component or a component even higher up the tree. Lastly, if it doesn't make sense for state to live in a common owner component or one doesn't exist, create a new component to hold state, and add it to the hierarch


## What is a “higher-order function”?


### A higher order function is a function that takes a function as an argument, or returns a function. Higher order function is in contrast to first order functions, which don’t take a function as an argument or return a function as output.

### Earlier we saw examples of `.map()` and `.filter()`. Both of them take a function as an argument. They're both higher order functions.

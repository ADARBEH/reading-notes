
## Based off the diagram, what happens first, the ‘render’ or the ‘componentDidMount’?

### First Render Cycle
#### In an isomorphic app, the first render cycle is the most important. This is where you will use lifecycle events to control what environment code runs in. For example, some third-party libraries are not loadable or usable on the server because they rely on the window object. You might also want to add some custom scroll behavior on the window event. You will need to control this by hooking into the various lifecycle methods available on the first render.

---
## What is the very first thing to happen in the lifecycle of React?

#### Mounting: During the mounting process, an instance of a component is produced and injected into the DOM.

---
## REACT PROPS VS. STATE
#### Passing props from component to component in React doesn't make components interactive, because props are read-only and therefore immutable. If you want interactive React components, you have to introduce stateful values by using React State. Usually state is co-located to a React component by using React's useState Hook:

---
## What is the big difference between props and state?
### PROPS
- ##### The Data is passed from one component to another.
- ##### It is Immutable (cannot be modified).
- ##### Props can be used with state and functional components.
- ##### Props are read-only.
### STATE
- ##### The Data is passed within the component only.
- ##### It is Mutable ( can be modified).
- ##### State can be used only with the state components/class component (Before 16.0).
- ##### State is both read and write.
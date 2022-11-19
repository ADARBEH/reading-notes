### what is Redux Basic ?
#### Redux is a predictable state container for JavaScript apps. It helps you write applications that behave consistently, run in different environments (client, server, and native), and are easy to test. On top of that, it provides a great developer experience, such as live code editing combined with a time traveling debugger.



---
### install Redux
```
npm install --save redux
```


### simple example of Redux Basic

```
import { createStore } from 'redux'

// Action
const increment = () => {
  return {
    type: 'INCREMENT'
  }
}
const decrement = () => {
  return {
    type: 'DECREMENT'
  }
}

// Reducer
const counter = (state = 0, action) => {
  switch(action.type) {
    case "INCREMENT":
      return state + 1;
    case "DECREMENT":
      return state - 1;
  }
};

let store = createStore(counter);

// Display it in the console
store.subscribe(() => console.log(store.getState()));

// Dispatch
store.dispatch(increment());
store.dispatch(decrement());
```

---

### If we have more than one reducer we can use combineReducer to combine them

```
import { combineReducers } from 'redux'
```

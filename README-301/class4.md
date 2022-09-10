
## What is a ‘Controlled Component’?

### The Controlled component renders form elements and controls them by keeping the form data in the component's state. Instead of the DOM, the component handles the input of the form element. It has the functions that govern the data that is passed on every onChange event. The mutable state is kept inside the state property and updated only with the setState() method. The Controlled component takes its current value through props and notifies the changes by the callbacks.

## Should we wait to store the users responses from the form into state when they submit the form OR should we update the state with their responses as soon as they enter them? Why.


### we update the state with their responses as soon as they enter them to be more interactive

## How do we target what the user is entering if we have an event handler on an input field?


```
{

 constant: event.target.value  

}
```

## Rewrite the following statement using a ternary statement:


```
{

if x===y ? console.log(true) : console.log(false)

}
```




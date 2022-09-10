## What does .map() return?
#### The map() method creates a new array populated with the results of calling a provided function on every element in the calling array.

### Return value
#### A new array with each element being the result of the callback function.
---

## If I want to loop through an array and display each value in JSX, how do I do that in React?

1. #### you can save your data as array in file and named .(json)

2. #### you can git your data at put in workspace by command (require('path of file');)

3. #### make maploop for your array 
---

## Each list item needs a unique "Key"

---
## What is the spread operator?

#### The spread operator is a new addition to the set of operators in JavaScript ES6. It takes in an iterable (e.g an array) and expands it into individual elements,The spread operator is commonly used to make shallow copies of JS objects. Using this operator makes the code concise and enhances its readability.
---





## List 4 things that the spread operator can do.

- #### Copying an array
- #### Concatenating or combining arrays
- #### Using Math functions
- #### Using an array as arguments
- #### Adding an item to a list


---
## Give an example of using the spread operator to add a new item to an array.

```
{
const odd = [1,3,5];
const combined = [2,4,6, ...odd];
console.log(combined); ===== [ 2, 4, 6, 1, 3, 5 ]
}

```

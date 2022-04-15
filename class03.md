> # Passing Functions as Props

## .map() and keys

1. What does .map() return?
    - a new array the same length as the incoming array
1. If I want to loop through an array and display each value in JSX, how do I do that in React?
    - something like the code block below -- map (or forEach or filter) the array and as part of the return value(s), have the function render a list that contains each item in the array:

```
const numbers = [1, 2, 3, 4, 5];
const listItems = numbers.map((number) =>
  <li>{number}</li>
);
```

1. Each list item needs a unique ____.
    - key
1. What is the purpose of a key?
    - to keep track of changes to individual items in an array

## Spread operator

1. What is the spread operator?
    - an ES6 operator that allows you to expand an object, string, array, etc -- it has many different uses
1. List 4 things that the spread operator can do.
    - copy arrays or objects, merge arrays or objects, convert a string to characters, remove duplicates
1. Give an example of using the spread operator to combine two arrays.
    ```
    const list1 = [1, 2, 3]
    const list2 = [4, 5]
    const mergedList = [...list1, ...list2]
    ```

1. Give an example of using the spread operator to add a new item to an array.
    ```
    const listC = [1, 2, 3]
    const listD = [...listC]
    listD.push(4)
    console.log('listC:', listC)
    console.log('listD:', listD)
    "listC:" [1, 2, 3]
    "listD:" [1, 2, 3, 4]
    ```

1. Give an example of using the spread operator to combine two objects into one.
    ```
    const obj1 = {a: 1, b: 2}
    const obj2 = {c: 3}
    const mergedObj = {...obj1, ...obj2}
    ```
## How to Pass Functions between Components

1. In the video, what is the first step that the developer does to pass functions between components?
    - The developer sets up state properties and a function that will use state to map through an array.
    
1. In your own words, what does the increment function do?
    - It loops through an array (or whatever argument is passed to the function) and for each item it checks for a match to the name property, if it finds a match it increments the count property, and it returns that item in the array, which is held by a variable, to hold the entire output array

1. How can you pass a method from a parent component into a child component?
    - with props, by making something a property on the child component

1. How does the child component invoke a method that was passed to it from a parent component?
    - with props, by using the syntax `this.props.PROPERTY-NAME` to invoke the method, where `PROPERTY-NAME` is the identifier assigned to the method that was passed from the parent component(s)
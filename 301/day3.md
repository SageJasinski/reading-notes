# Readings for class 3

1. using `.map` will return an new array based on what is passed through it

2. You can use the `.map` feature to loop through an array and inside of that method you can have each item passed through be set to a specific JSX element

3. Make sure when making multiple list items that each list item has a unique key

4. Key's are very important as they help react keep track of what specific items have been changed or updated

## Operator

1. The Spread operator `...` will take an array and "spread" each item out for functions that expect separate arguments.

2. Spread operators can do otherthings as well, such as combining two arrays, adding new items to an array, combining two objects together, and copying arrays.

3. Combining arrays:

```js
    const arrOne = [1,2,3];
    const arrTwo = [4,5,6];
    const combArr = [...arrOne,...arrTwo]; // [1,2,3,4,5,6]
```

4. adding new items:

```js
    const arrOfNum = [3,4,5];
    const firstNums = [1,2,...arrOfNum]//[1,2,3,4,5]
```

5. Combining objects:

```js
    const objOne = {day: 1};
    const objTwo = {day: 2};
    const objThree = {...objOne,...objTwo} //{day: 1, day: 2}
```

## Passing functions between components

1. First the developer creates the functions he wishes to pass in

2. The function he creates takes in the `people` array of objects and conditionally increments the count property of the object based on if the name passed through the function matches the name provided, Then the function returns the new person and updates the people array.

3. To pass a method from a parent to a child you can set the name that you want to refrence the methode to a `this.nameOfMethodToPass`

4. To call that method in the child component you would use `this.props.newNameOfMethod()` in the child component

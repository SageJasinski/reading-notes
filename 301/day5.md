# readings for day 5

1. single responsibility principle is to have each component take care of one task instead of many

2. A static version is a version of your site that has little interactivity but shows a proof of concept

3. once you have a static version of your site you need to add the interactivity or state to your site

4. the three question are:

 - Is it passed in from a parent via props?

 - Does it remain unchanged over time?

 - Can you compute it based on any other state or props in your component?

5. In order to decide where state needs to live we must identify which components need to use it and decide which component is the parent holder to pass down the information

## Higher-Order

1. A higher order function is a function that operate on other functions

2. line two is an arrow function which will return the value passed as long as the value passed is greeater than n or the value passed in the parent function

3. map inside of a another function will take in the parent numbers passed and compare and separate them and return a new array that the parent function can then continue to use.
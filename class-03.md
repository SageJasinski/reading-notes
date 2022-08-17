# Class 03 Notes

## Html Lists

when writing a list in html you should use an unordered list when you want to have bullet points or other marks that do not need to be in a sequential order. us the Ordered list when you would like the list items to be in a sequential order.To change the bullet style of the list use the `type` attribute to set if you want circles, disc, or square bullets. You can also change the NUmbering on an ordered list with the `type` attribute to lower/uppercase letters, roman numerals, or numbers by default.

## CSS box model

In the box model a margin is like a chicken coupe which surrounds and protects everything inside it. The padding is like the mother hen, who sits in the chicken coupe and provides space and protection for the eggs.

The four parts of the box model are:

1. The margin - the outer most box (the shed)
2. The boarder - Is around the padding (the hay)
3. The padding - surrounds the content (the mother hen)
4. The content - Is the lowest box layer (the egg)

## JS

an array is a storage element which can store stings,numbers, objects, and other arrays.

```Javascript
 const people = [['pete', 32, 'librarian', null], ['Smith', 40, 'accountant', 'fishing:hiking:rock_climbing'], ['bill', null, 'artist', null]];
```

above is an example of an array. to access the items in the array first call the name of the array followed by the slot number(which starts at 0) of the object you want to grab.

To make writing operator a little faster here are 5 commonly used shorthands for operators:

1. Addition - `x += f()` is the same as ` x = x + f()`
2. Subtraction - `x -=3` is the same as ` x = x - 3`
3. Multiplication - ` x *= 1` is the same as `x = x *1`
4. Logical OR - `x || = f()` is the same as ` x = x || f()`
5. Logical AND - `x &&= f` is the same as `x = x && f`

If you try to add different data types together you will get different outputs depending on the order you place them. for example:

```JS
let a = 10;
let b = 'dog';
let c = false;

// evaluate this
console.log((a + c) + b;)
```

Will return `10dog` in the console.

A conditional statement should be used when you want to evaluate data types and values in your code. For example if you wanted to check the input of a user entered search word in a search bar you would use an `if()` statement  to check the initial input value of the user.

Use a loop when you'd like to have a task repeated over and over until you specify it to complete.
An example of this is if you want to iterate through a customers shopping cart to show all the available slots for items, you can loop through adding new items until the desired amount is shown.

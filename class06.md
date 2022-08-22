# Class notes

## JavaScript objects

An object in JS is like an Array in the sense that it store different types of data in one container. Some advantages that objects have over arrays and variables is that because they can store functionality as well the information inside the objects can be called individually. It is also much easier to call individual objects by name than arrays.
When writing and calling an object dot notation(`object.thing`) is preferred however if you have the object
defined at runtime you can't use dot notation but instead use bracket notation.

```js
const dog = {
  name: 'Spot',
  age: 2,
  color: 'white with black spots',
  humanAge: function (){
    console.log(`${this.name} is ${this.age*7} in human years`);
  }
}
```

The code above is an example of an object. Here you will notice the `this` operator which in this case will evaluate to `spot` because the `this` operator will alway reference the local object.

## The DOM

The DOM is a way for a script to interact with and change the web page. It is represented with objects and nodes. The DOM is not a scripting language but rather a webAPI that allows Javascript to know and manipulate elements and other documents. Without the DOM javascript would not be able to access these elements or documents.

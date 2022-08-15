# Class 2 reading notes

## HTML

semantic elements are elements that are easier to understand for the human reader of your code. It is important to use semantic elements so that you and others who are reading your code can quickly identify different characteristics of your code.
An example of a semantic tag is the h1 tag as when you look at it you know that this is a top level heading. There are 6 different levels of headings, as the number goes down so does the level or in most cases the size of the heading.

the `<sup>` and `<sub>` elements are for when you want certain text to appear at the top or bottom of the text that is inline, These are called super, and subscripts. For example if you were displaying a number for a math problem and you wanted it to have an exponent of 3 you would write:

```html
10<sup>3</sup>
```

In the `<abbr>` element you must give it the **tittle** attribute in order for it to display what your abbreviation stands for.

```html
<abbr tittle="Federal Bureau of Investigation">F.B.I.</abbr>
```

These elements are useful to know when writing html.

## CSS

There are a couple ways to apply CSS to an html file. The first is to do it inline with the `<style>` attribute in the actual html file. There you can add your CSS directly to the html file. The second way is to create a separate CSS file and add it to the html file using the `<link>` attribute and specifying that it is a stylesheet. The best practice however is to use a separate CSS file as this cuts down on the clutter of the code and makes it easier to implement edits if you only need to edit the css and not the html. 

A basic CSS block might look like this:

```html
h2 {
    color: black;
    padding: 5px;
   }
```

In this example the h2 is called the selector, were you define what it is you'd like to change the style of. The declaration is the block of properties that you are changing. Everything inside the brackets is a declaration. Then you have the properties these are the thing in the h2 you are changing. Here we are changing the color and padding property of the h2 selector.

## JavaScript

When writing JS make sure to pay attention to your data types. There are two you want to have a firm grasp of. the first is the number data type these are pretty self explanatory and are things like 1,2,3 etc. the second is the string data type these are the text inputs and can look like this **one,two,three**. The string data type is a sequence of text enclosed in single quote marks.

Also when thinking of logic you want to use in JS it's important to know the different types of operators available to you.
There are four different types of operators:

1) Mathematical - These are operation such as addition (+), Subtraction (-), multiplication (*), and division (/) which can all be used in JS

2) Assignment - this is when yuo want to assign something to something using the `=` sign. this is used for thing such as assigning values to variables.

3) Strict equals - you would use a Strict equals `==` when you want the value to be exactly the same as what you specify. for example you may want the number 5 returned instead of the string five in that case you would use the strict equals sign which will only return the number 5.

4) Not equal - Use the Not equal (!=) use this when you want to check if a value isn't equal to the one yuo will specify.

In addition to these types you also have comparison operators like:

- Greater than or less than `< and >`
- Greater/Less than or equal to `<= or >=`

You can also use logical operators such as && AND which allows you to change together multiple expressions so that ALL of them have to evaluate to true for the expression to return true. the || OR operator is used for linking multiple expressions together and will return true if ONE or more expression evaluate to true.

All these operators are great for use in functions and if statements.

Using functions is crucial to having a well made interactive web page. If you wanted a search bar you couldn't do it without functions, If you wanted a button to trigger something, you couldn't do it without functions.

An if statement will check if a condition is true then it will execute the code. If you want to add another condition for the if statement to check if the previous statement where false then you would use the else if command right under the if statement.

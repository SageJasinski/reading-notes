# Class 01

A haiku called "A Simple Request"
> A request is sent,<br> speaking TCP IP. <br>You give me packets? <br> -Sage Jasinski

## Parsed files

HTML, CSS, and JS are parsed separately in the browser. The browser will first read the HTML file which then will point it in the direction of any link or script elements which would contain CSS or JS files. Once a request has been sent for those CSS and JS files the browser will store an in memory tree for the html and an in memory structure for the CSS and JS. Once the browser executes the JS the user then can see the web page and interact with it.

## Finding Images

Searching for images on google is a great way to find images for your website. Although most of the images are copyrighted you can go to the “tools” section then go to the “usage rights” section and select “Creative Commons licenses.”

## Variable variables

Variables are items that store certain information that can be used for later. Variables are important to Java script because they hold all the functionality that makes java script what it is. You can’t have a login page without JavaScript and variables, and you can’t have functional buttons without JavaScript and variables either. With out variables you couldn’t interact with the web page because you wouldn’t be able to change or set certain values within functions or the page.

In javascript there are five different types of variables:

1. Stings - A string is a sequence of text. To mark a variable as a string use the quotation marks at the beginning and end of the variable data.

```js
let String = 'text';
```

2. Numbers - a number is exactly what it sounds like. to indicate something is a number simply type the number after the equals sign with no quotation marks.

```js
let number = 30;
```

3. Boolean - A boolean is a true or false statement and you set the value of the statement by typing true or false after the equals sign.

```js
let boolean = true;
```

4. Array - An array is an assortment of values stored in one reference. to indicate an array use square brackets at the beginning and end of your array.

```js
let array = [12,'Hello',13,'Hi'];
```

5. Object - An object is any other type of data in Java script.

```js
let title = document.getElementbyID('title');
```

Adding javascript to your html document is easy and will allow you to use these variable types in your web page. Simple call the script where you need it using the `<script>` element in your HTML file.

```html
<script src="filename.js"></script>
```

## HTML attributes

An HTML attribute is any extra information that the element might need that isn't part of the contents of the tag. The attribute will be placed in the opening tag. For example you can give any HTML element an ID or class attribute like this:

```html
<li class="list">Content</li>
```

## HTML Element

An html element has three main parts to it. FIrst is your opening tag. this is where you will state what type of element it is as well as putting any necessary attributes in it. the second is the content this is everything between the opening tag and closing tag. This is what will be displayed on the web page. next is the closing tag which signals to the browser that this element is done and there is no further content needed for it.

### difference between a Section and an Article

some elements seem similar nd do similar things but are used in different ways. For example the `<article>` and `<section>` elements are use both to group content together but the article tag is more used for self-contained content in the page where as the section is used more to dived different sections of the page.

### Everyday element

Some elements are essential to a web page's functionality. these commonly used elements are:

- A header
- A nav element
- A main content section
- A sidebar
- A footer

Each of these plays a special role in the web page and should be looked out for.

### Semantics

It is beneficial to use semantic tags as it will help the read ability of your code note only to you and other coders but also to the browser. for example setting a top level heading with `<span>` is a little confusing to read but an `<h1>` element is easily identifiable and read able while also setting its contents as a high level heading.

## Metadata

Meta data is stored in the head section of an html web page and can play a key role in search engine optimization. You can add a description to your page which will help search engines post your link higher in relevant searches. to do this all you need is the `<meta>` tag and it can be used like this:

```html
<!DOCTYPE html>
<html>
  <head>
    <meta name="description" content="A page that I made to demonstrate making an HTML page">
    <title>My test page</title>
  </head>
</html>
```

You can also add things like authors the same way which can help search engines when looking for specific site that contain certain people.

## First steps

the first steps to designing a website are first figuring out what exactly you want to accomplish with your site. Next set yourself some goals you want the website to hit. Then you can start wireframeing and planning out the look of your website.

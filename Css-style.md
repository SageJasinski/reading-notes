# It's Style Time

## What is a CSS?

CSS , or cascading style sheet, is a style language for telling the browser how you'd like your code to look and be presented on the web page.

## What does it look like?

CSS is a rules based language meaning you define a group of rules with styles that you want your html elements to have. So if you have a header or h1 tag and you want it to be blue in css you'd write it:

```css
h1 {
    color: blue;
}
```

Make sure to open and close your style with curly brackets as well as closing each rule in a semi colin.

## How to Link Your Style to Your Page

There are a few ways to accomplish this. My preferred method is to have an external style sheet to keep it separate from the html file. To do this simply add a link to the sheet in the head section of the html file.

```html
<head>
<link rel="stylesheet" href="mystyle.css">
</head>
```

This will make it so you can have an easily readable html file and a separate easily readable css file.

## Now in Color

So you want to change the color of things around here. CSS recognizes 3 different ways to reference color. the first is through the color name like so:

```css
h1 {
    color: green;
}
```

this is a fast way to get an element the color you want, although if the shade of green you want isn't what is provided how do you get a more refined controls over the color? Glad you asked my personal favorite way to add color is via the colors hex value for example:

```css
h1 {
    color: #00ff00;
}
```

you can go to google and easily find a color picker that will show you the hex value of the color you want.

Another way to accomplish this is via the **R,G,B** values.

```css
h1 {
    color: rgb(0,0,255);
}
```

for a little bit of a cheat sheet you can go to [This CSS properties reference](https://developer.mozilla.org/en-US/docs/Web/CSS/Reference) to get an extensive list of different properties that can be called.

[Back to Home](README.md)

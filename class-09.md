# Class 9 reading notes

## HTML forms

Forms are very important to web develoupment, they allow the user to search or manipulate user interface elements on the client side but can also store information on the serverside that the client would want acess to.

When designg forms it is important to keep in mind what it is you are asking the user for, and what you need the form to do. Large forms can frustrate users so only ask for pertinent values.

When creating a form element you can use:

- `<form>` to define the form element and put other elements inside
- `<feildset>` to create groups (or sets) that share the same purpose
- `<legend>` in conjunction with the feildset inorder to describe the function of the set
- `<label>` this can increase the acessability of your website. Labels also are clickable which makes them handy in getting user input.
- `<input>` to get any type of user input and return it in the form.

## JavaScript events

Events are like a car waiting at a trafic light. The car won't go until the light turns green. likewise an event waits for something to happend before it starts running it's code. An event listener will take two parameters. The first is the name of the event we want, the second is the code we want it to run once the event has happended.

The event object is a short hand that provides extra features to the event handler on  call. The Target of an event object is useful as it targets the place where the event was called on the page rather thanthe whole page itself.Watch out for event bubbling which is when an event first checks the elemts it was called on then checks it's parent and the next until it reaches the html element.Event capturing doe a smiliar thing but instead of starting with the element it was called on it first checks the html element and continuse down until it finds the direct parten of the element.

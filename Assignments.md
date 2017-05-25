# Assignment 9

To ease into working with the `canvas` today you'll replicate part B of Assignment 8 using figures you draw on the `canvas.` Your page should generate 25 shapes, randomly selecting between rectangles, squares, circles, or another shape of your choosing drawn using `paths`. This last shape cannot be a triangle (but see the triangle example [here](https://developer.mozilla.org/en-US/docs/Web/API/Canvas_API/Tutorial/Drawing_shapes#Drawing_a_triangle) for inspiration). Each shape should have random dimensions, color, and starting location. The starting location **must** be on the canvas; i.e. the shape cannot "spawn" outside of the bounds of the `canvas`.

**NOTE:** these shapes do *not* correspond to DOM elements.

Due May 30.

# Read Me

Read the [MDN Canvas Tutorial](https://developer.mozilla.org/en-US/docs/Web/API/Canvas_API/Tutorial) from **Basic usage** through **Advanced animations**. I suggest you work through the code samples given, we'll be talking briefly about `canvas` during class and then you will be given your bext assignment.

# Assignment 8

### Part A

Create a JavaScript object that represents a <code>Square</code>. Each <code>Square</code> will have an ID, a random color, and a random width assigned to it. Write a simple program that creates an array of 10 <code>Square</code> and prints the array to the console.

### Part B

Extend your boxes so that they have members for storing a <code>top</code>, a <code>left</code> property. For each <code>Square</code> in your array create a <code>div</code> element on your page at the <code>top</code> and <code>left</code> coordinates stored within the object. Make sure these cordinates are lay within the dimensions of the viewport (see <code>window.innerWidth</code> and <code>window.innerHeight</code>). **NOTE:** you only need to worry about checking these bounds at the time you create the square; you needn't worry about what happens if the viewport size changes after you display the square.

### Part C

Animate the squares from above. Add a random <code>velocityX</code> and <code>velocityY</code> property which represents the distance the <code>Square</code> will move at each iteration of <code>requestAnimationFrame</code>.

### Part D

In this part of the assignment you will add some basic gamification to the page. Each <code>Square</code> object should be removed from the page (and deleted from memory) if it is clicked on as it moves across the page. Additionally, each <code>Square</code> should "bounce" off the edges of the viewport when it collides with them. Finally, clicking on the <code>body</code> of the page (any area that is **not** a <code>Square</code>) all objects on the page should stop moving and no new elements should be created. Clicking <code>body</code> again should turn all that functionality back on.

Due May 18.

# Assignment 7

The following is a group assignment. One keyboard, multiple sets of eyes; i.e., don't divy up the work by each tackling a separate file and working in parallel. 

### Part A

Build a web app similar to the one you did for Assignment 4, Part B. Get the user’s first name, last name, and email address. All fields are required. This time, collect the user’s input and display in on the page in a table which you dynamically create. For each new user create a new table row and cells to display the data.

Due May 4

READ [Animating with javascript: from setInterval to requestAnimationFrame](https://hacks.mozilla.org/2011/08/animating-with-javascript-from-setinterval-to-requestanimationframe/), [Understanding JavaScript's requestAnimationFrame() method for smooth animations](http://www.javascriptkit.com/javatutors/requestanimationframe.shtml), [MDN's Canvas Tutorial](https://developer.mozilla.org/en-US/docs/Web/API/Canvas_API/Tutorial) for next week.

Some other resources you may be interested in:

[Eloquent JavaScript](http://eloquentjavascript.net/)
[JavaScript books by Dr. Axel Rauschmayer](http://exploringjs.com/)

# Assignment 6

### Part A

PIG is a simple dice game. One possible layout is shown below (click to enlarge). When the game starts the element containing the current player's name and the row of buttons, labels, and input elements below it are hidden. The players enter their names and click the New Game button to start the game (which also causes the hidden elements to be displayed). From that point on the players take turns following the rules displayed on the page.

[![](http://i.imgur.com/fy0Blsum.png)](http://i.imgur.com/fy0Blsu.png)

When building this and all future assignments pay attention to the aesthetics of your page. While I know that none of us are web **designers** we learned many techniques in CIS195 for creating consistent and attractive pages. Use that knowledge. Line elements up. Use font color, weight, and size to signify importance. Make the page pleasant to look at. A portion of your grade for each assignment will be for creating attractive pages as well as functional ones.

This *is* a group project.

Due May 4.

# Assignment 5

### Part A
Rewrite your previous checkbox page taking advantage of event delegation; i.e. use one event handler for all checkbox change events.
 
### Part B

Create a simple "guess-the-number" type game. It should choose a random number between 1 and 100, then challenge the player to guess the number in 10 turns. After each turn the player should be told if they are right or wrong, and if they are wrong, whether the guess was too low or too high. It should also tell the player what numbers they previously guessed. The game will end once the player guesses correctly, or once they run out of turns. When the game ends, the player should be given an option to start playing again.

Use page elements for all input and output (no `alert`, `prompt`, etc.) At the top of the page there should be instructions for new users.
 
### Part C

Write a simple page that will take sort three numbers the user enters via three separate `input` boxes and displays them in a `textarea` in sorted order when the user clicks a `button`. 

### Part D

Write a new page similar to the last one you did but this time take and sort names (strings).

### Part E

Add buttons to your last two pages that will display the provided values in reverse order.

Due May 4

# Assignment 4

### Part A

Write an application that will calculate the miles per gallon the user has achieved given the number of miles driven and the gallons of gas consumed as pictured below (click the image to enlarge it).

[![](http://i.imgur.com/lQ5z8hpm.png)](http://i.imgur.com/lQ5z8hp.png)

* The third text box should be disabled so that it is not editable by the user
* Your JavaScript should use `strict mode` [W3Schools](https://www.w3schools.com/js/js_strict.asp) [MDN](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Strict_mode)
* Write code to protect against bad (non-numeric) input
* Round input and output both to one decimal place

Due April 27

### Part B

Write an application that mocks subscribing to a mailing list as pictured below (click the image to enlarge it).

[![](http://i.imgur.com/lTdASklm.png)](http://i.imgur.com/lTdASkl.png)

* All three inputs are required, you may valicate that they are provided using either HTML or JavaScript
* Validate that the two email address inputs are the same and that they are at least potentially valid email addresses

These assignments are to be done *individually*.

# Assignment 3

After Joe stopped talking you were asked to complete the following project as a group in class:

Create a page with a five checkboxes. Whenever a change is made to one of the checkboxes a list of all currently selected checkboxes should be displaying in an element on the page.

1.	Wire up an event handler for the “change” event on the checkboxes
1.	When the change event fires, loop over all the checkboxes on the page checking if their “checked” property is true
    1. If it is, add its name to the list
    2. If not, ignore it 
    
1.	Display the list of all selected checkboxes 

Be sure that whoever posts the assignment for your group includes the names of *all* group members on the page.

Also, I'm going to hold off one more class on the survey I promised. 

# Assignment 2

For this assignment we completed the following in class:

* Create a page that displays an `alert()` upon the `DOMContentLoaded` event
* Create a page that displays a message to the user by modifying the content of an element upon the `DOMContentLoaded` event
* Create a page with a button that, when clicked, changes the font color of an existing element on the page
* Create a page that will take two numbers entered via text boxes and display their product on the page when a button is clicked

# Assignment 1

### Part A

Write the code necessary to declare and initialize one variable of each of the following types:

* A number
* A string with embedded quotes (hint: you will need to use the JavaScript escape character)
* A Boolean
* A homogeneous array using an array literal
* A heterogeneous array using an array literal
* An object using an object literal

Create a simple web page and display your code in it using `<code>` and `<pre>` tags. For this part of the assignment your code should **not** be executable. If you're feeling really adventurous try using [highlight.js](https://highlightjs.org/)


### Part B

Write an external JavaScript file that uses `prompt()` to get the user's name and then greets them using `alert()`.

### Part C

Write a JavaScript program that calculates how much it will cost the user to see a movie. Ask them how many adult tickets and how many children's tickets they want. Tickets cost $10.00 and $7.50 respectively. Display the total cost of all tickets to the user.

Post all three parts to the lbccwebdev.net server by 5:00 p.m. on April 13

# *Task 1*

For class on Thursday read [Chapter 1](https://github.com/getify/You-Dont-Know-JS/blob/master/up%20%26%20going/ch1.md) and [Chapter 2](https://github.com/getify/You-Dont-Know-JS/blob/master/up%20%26%20going/ch2.md) in [YDKJS Up & Going](https://github.com/getify/You-Dont-Know-JS/blob/master/up%20&%20going/README.md#you-dont-know-js-up--going). Using the console in your browser key in and experiment with the code samples in the book. Bring any questions you may have to class for discussion.

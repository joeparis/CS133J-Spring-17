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

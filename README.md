# Introduce yourself with HTML and CSS!


## Objective

Use basic HTML and CSS knowledge to introduce yourself with a profile card

## Prerequisites

To complete this project, students should have the following:
* Basic HTML Knowledge
* Basic CSS Knowledge
* Text editor such as Sublime or Atom

## Concepts

HTML | Description
---| -----------
Tags | Description of concepts they will need to know to complete project
Attributes | Description of concepts they will need to know to complete project

## Your Challenge

### Part I

To complete Part I, fulfill the following requirements:
Create the following:
* HTML file
* CSS file
* JS file
Link all of your files correctly.

---

### Part II HTML

To complete Part II, fulfill the following requirements:

Instructions should be listed as a numbered list. See below for an example:

1. Create an area that will show the picture of the Pokemon found and the text with the Pokemon's name.
2. Create an area that will display the text of the current location.
3. Create an area that will show the image of the player.

### Part III CSS

To complete Part III, fulfill the following requirements:

Instructions should be listed as a numbered list. See below for an example:

1. You can style your elements to your liking however, keep the following things in mind:
   * An element's position can be controlled using pixels specifying how far away it should be from the left, top, bottom, or right **only if** it has ```position: relative```, ```position: fixed```, or ```position: absolute```. Resource: https://www.w3schools.com/css/css_positioning.asp
   * Make sure to give an empty element a width and a height or you won't see it on the page!
   * Setting the width and height of the largest element to ```calc(100vw)``` and ```calc(100vh)``` is a convenient way to get a full screen element (which will work on newer browsers).

### Part IV JS

To complete Part III, fulfill the following requirements:

Instructions should be listed as a numbered list. See below for an example:

1. Create an Event Listener on the ```document``` that will listen for a ```keydown``` event. If the user presses an up arrow key, the player image should move 30 pixels up and change the image to the next walking image in the sequence (there are 4 total in a top, left, right, or bottom sequence). (Hint: You can use a counter to keep track of which image in the sequence should be displayed next).

2. Create a function called ```randLocation``` that will return a random number from 1 - 50 for our location ID.
3. Create a function called ```generateScene``` that will do the following:
  * Create a variable called ```xhr``` that will store a new XMLHttpRequest()
  * Open and send a 'GET' request at a random location-area (e.g. https://pokeapi.co/api/v2/location-area/3 or https://pokeapi.co/api/v2/location-area/23 or https://pokeapi.co/api/v2/location-area/49 ...etc. depending on your random number)
  * When the request is ready to be processed, do the following:
    * Store ```JSON.parse(xhr.responseText)``` in a variable
    * Display the name of the location on the webpage

4. Create a function called ```generatePokemon``` that will do the following:
  * Store a random number from 1 to however many pokemon are able to be encountered at our current location (Hint: Look at pokemon_encounters in the xhr response!)
  * Store the url of the corresponding pokemon into a variable
  * Create, open, and send a new XMLHttpRequest() to the pokemon url you just obtained
  * When the request is ready to be processed, do the following:
    * Display the name of the pokemon in the modal
    * Display the image of the poekmon in the modal (Hint: Look at ```sprites``` in the response!)

5. Create an immediately-invoked function expression (IIFE) called loop that will do the following:
  * Store a random number from 5000 - 10000 (this represents a random interval of time until a pokemon will appear)
  * Create a setTimeout that will run the following function after a random amount of time has passed:
    * Call the ```generatePokemon``` function
    * Create an alert saying that you've found a pokemon
  * Call itself (call the loop function again);

## Stretch Goals

List 4-5 stretch goals here.

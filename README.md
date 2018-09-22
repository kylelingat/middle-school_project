# Introduce yourself with HTML and CSS!


## Objective

Use basic HTML and CSS knowledge to introduce yourself with a profile card

## Prerequisites

To complete this project, students should have the following:
* Basic HTML Knowledge
* Basic CSS Knowledge
* Text editor such as Sublime or Atom

## Setup

* Fork and Clone Repo
* Create HTML file 
* Create CSS file
* Link CSS file to HTML file


# Instructions

## HTML

1. Create a `div` with an ID of `cardContainer`
2. Inside `cardContainer`, insert two divs called `profilePicture` and `profileText`
3. Inside `profileText`, insert the following tags:
     * `h1` - This will be your name such as "Barry Allen"
     * `h3` - This will be your title such as "Forensic Scientist & Speedster"
     * `p` - This will be a  bio/description of yourself
4. Your HTML structure should look like
  ```
<div id="cardContainer">
    <div id="profilePic"></div>
    <div id="profileText">
        <h1>Your Name</h1>
        <h3>Your Title</h3>
        <p>Your bio/description</p>
    </div>
</div>
  ```
  
  ## CSS
  
  ### #cardContainer
  
  1. Define a `width` for `cardContainer`
  2. Create a `border` for `cardContainer`
  
### #profilePic

1. Define the `width` to always be equal to the `width` of `cardContainer`
2. Define a `height` for `profilePic`
3. Set a `background-image` for `profilePic`. Use an image of yourself or what represents you
     * If you need to adjust the positioning and size, play around with the following properties
          * `background-position`
          * `background-size`

### #profileText

1. Center the text with `text-align`
2. Change the `opacity` of the `h3` tag

# Result

![Screenshot](https://i.imgur.com/gLlhL4k.png)

# Concepts
HTML | Description
-----|------------
div | A container element.
id | Specify an unique ID for an individual HTML element
h1 | Heading element 1
h3 | Heading element 3 
p | Paragraph tag

CSS | Description
----|------------
width |  Width of an element
height | Height of an element
border | Border around an element 
background-img | Set a background image of an element
background-position | Set the position of a background image of an element
background-size | Set the size of a background image
text-align | The alignment of text in an element
opacity | Opacity level of an element

# Stretch Goals

* Use `box-shadow` instead of `border`
* Use different web fonts


# Resources
* Please make sure to utilize Google!
* [Background image properties](https://www.w3schools.com/cssref/pr_background-image.asp)
* [Border](https://www.w3schools.com/css/css_border.asp)

  

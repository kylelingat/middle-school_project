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
     1. `h1` - This will be your name such as "Barry Allen"
     2. `h3` - This will be your title such as "Forensic Scientist & Speedster"
     3. `p` - This will be a  bio/description of yourself
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
  
  ### cardContainer
  
  1. Define a `width` for `cardContainer`
  2. Create a `border` for `cardContainer`
  
### profilePic

1. Define the `width` to always be equal to the `width` of `cardContainer`
2. Define a `height` for `profilePic`
3. Set a `background-image` for `profilePic`. Use an image of yourself or what represents you

### profileText

1. Center the text with `text-align`
2. Change the `opacity` of the `h3` tag

# Result

![Screenshot](https://i.imgur.com/gLlhL4k.png)

# Stretch Goals

* Use `box-shadow` instead of `border`
* Use different web fonts
  

# Week 1 Lab: Build Spotify Landing Page (Desktop)

**Overview:** In this lab, you will be [pair programming](https://en.wikipedia.org/wiki/Pair_programming) with another person sitting next to you to create the Spotify [landing page](https://www.spotify.com/vn-en/) from scratch using only HTML and CSS. The goal of this lab is to help you understand the materials that we went over in our first lecture especially around [CSS Box Model](https://www.w3schools.com/css/css_boxmodel.asp) and [CSS Positioning](https://css-tricks.com/almanac/properties/p/position/). After completing the lab, you should be able to create any webpage from scratch quichkly without any issue.
Below is a replica of Spotify Landing page that was developed using only HTML and CSS:
<img src='https://i.imgur.com/Y0Wub3u.gif' alt='Spotify Demo' />

## Milestone 1: Setup environment
At this point, you should have a working Text Editor that you are familiar with. Some of the most popular text editors are: 
* [Visual Studio Code](https://code.visualstudio.com/download) (Recommended)
* [Sublime Text](https://www.sublimetext.com/3)
* [Atom](https://atom.io/)
* [Notepad++](https://notepad-plus-plus.org/download/v7.5.6.html)
* [Vim](https://www.vim.org/download.php)
* [Emacs](https://www.gnu.org/software/emacs/)
* [Brackets](http://brackets.io/)

Alternatively, there are also online Text Editors that let you write code in the browser and see the results instantly. Popular ones are:
* [CodePen](https://codepen.io/) (Recommened)
* [JSFiddle](https://jsfiddle.net/)
* [CSS Deck](http://cssdeck.com/)
* [JS Bin](http://jsbin.com/)

Throughout the course, I will be using mainly Visual Studio Code and CodePen for code demostration.

## Milestone 2: Create 2 files: index.html and style.css, and link them together
* First, create a folder named "spotify"
* In the folder that you just created, create 2 empty files index.html and style.css 
* In the index.html, add the following code: 
<!DOCTYPE html>
<html>
  <head>
    <meta charset="utf-8">
    <title>Music for everyone - Spotify</title>
  </head>
  <body>
  </body>
</html>
This is the first skeleton of the HTML file. The <!DOCTYPE html> declaration means that the HTML file is HTML 5. The <title> tag defines a title in the browser toolbar, provides a title for the page when it is added to favorites, and displays a title for the page in search-engine results.
* Now, link the style.css with the index.html file by adding this code into the html file, below the <title> tag:
<link rel="stylesheet" href="style.css">
This line of code has to be within the <head> tag.

## Milestone 3: Layout all the parent containers
Spotify landing page has 7 parent containers from top to bottom:
1. Navigation bar
2. Banner
3. First white container (white-1)
4. First color container (color-1)
5. Second white container (white-2)
6. Second color container (color-2)
7. Footer
In the index.html, add the following code inside the <body> tag to add the 7 containers:
    <div id="navbar"> </div>
    <div id="banner"> </div>
    <div id="white-1"> </div>
    <div id="color-1"> </div>
    <div id="white-2"> </div>
    <div id="color-2"> </div>
    <div id="footer"> </div>
Each of the container has their own id/name and the name should be easy to understand.
Now, there are 7 distinct containers layed out in the html file. 

Now, give them some styling by giving height and background color to each of the container:
In the style.css, add the following code:
#navbar { height: 80px; background-color: black }
#banner { height: 660px; background-color: pink }
#white-1 { height: 650px; background-color: white }
#color-1 { height: 600px; background-color: pink }
#white-2 { height: 510px; background-color: white }
#color-2 { height: 750px; background-color: pink }
#footer { height: 500px; background-color: black }
Save and reload the index.html file on your Chrome browser. Now you can see 7 different containers layed out one on top of another.

## Milestone 4: Create the top navigation bar
The top navigation bar has the following properties: 
* Spotify logo on left
* Horizontal list of hyperlink on top right
* Fixed position on top of the page
* Transparent background color





## Other Resources
* [Chrome](https://www.google.com/chrome/browser/features.html) - the most popular web browser
* [Visual Studio Code](https://code.visualstudio.com/download) - a powerful text editor with a lot of useful plugins


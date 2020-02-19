# CSS-Bootstrap-Homework
The project was to create a portfolio including an index page, portfolio page and contact page.
This had to include a navigation bar, a responsive layout and responsive images on the pages while minimizing the use of media queries.

For all pages I linked a bootstrap cdn for styling and my own css file for the background image, to keep the background colour of my elements all the same and for sizing of images.

For the Index page I used a navbar from bootstrap that highlights the currently active page using the active class. The sr-only class is for use by screen readers, to allow visually impaired users know what page is active.
I used the bootstrap grid system to put elements into rows and then coloumns to control the design of the layout, the col-sm-6 class makes the element take up half the screen on screen sizes small and up while smaller screens will have the elemnet take up the full screen, this is used for the main elements on every page to make them responsive to the screen size.
The main element uses the bootstrap light border around the whole element.
The image is also made to be responsive by use of the img-fluid class, this sets the width to 100% of the container and the height to auto to make it alter its dimensions in response to the screen size.
The footer is made to stick to the bottom of the viewport by use of the fixed-bottom class from bootstrap. It also has a light style border on top from bootstrap. 

The portfolio page also uses the navbar from the bootstrap cdn, however the active class is changed to the portfolio page.
The main container uses the same style as both the Index and Contact page. Using the grid system it is split up into 3 rows, the first 2 with two columns and the last with one.
The rows use the class justify-content-center to keep the content in the middle of the container.
To keep the images responsive but also keep them a regular size, I used media queries in the css file to keep them all set to the same height at different screen sizes while also staying at 100% width of their coloumn.

The contact page has the Contact link as the active link.
The main content of this page contains the form tag and is split into 3 form groups, the first div has a label for name and an text input for the user to type their name, the second div is labelled as email and has an email input type for the user's email and the last div is labelled message and has a text area for the message.
The last part of the container is a submit button to submit the message.

The stylesheet contains the background image for the body of all pages, the colour for the navbar main and footer elements to make sure they are the same across all pages. 
The media queries are to set the height of the images at different screen sizes to make them unifrom to each other.
It also contains the footer id, setting its height and width to always be the same.
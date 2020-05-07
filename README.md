# Running the application

1. Go to the main directory
2. Open the index.html, using your browser

# Requirements for modifying the application:

- Having [node.js](https://nodejs.org/en/download/) installed on your machine.

# Modifying the application:

You can modify the html without any third party tools / scripts, but the styles has been written in the SCSS.
You can use your SCSS compiler or alternatively do the following steps, to achieve the the same result:
<br />

1. Go to the root directory of the project
2. Use the command: `npm install` (You have to do this just once)
3. Use the command: `npm run watch-styles`, to have the compiler running :)

Compiler is working in the real time, so everytime you make a change in one of the SCSS files, then this will be automatically compiled to the main.css file.

# Current SCSS file structure

- variables.scss -> for storing the variables, that are used in the other files
- basic-page-styling.scss -> for styling the page itself
- mixins.scss -> for SCSS [mixins](https://sass-lang.com/documentation/at-rules/mixin)
- main.scss -> for styling the drawing
- animations.scss -> for storing the drawing animations

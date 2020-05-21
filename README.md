# Techdegree Project 4 - Web Style Guide

**Skills Used:**

- CSS
- Sass

**Project Description:**

For this project I implemented Sass. I converted the provided CSS into Sass by creating a "scss" folder and created sub-folders inside of the scss folder for the base, component, and utilities partials. I changed the normalize.css file into a Sass partial and saved it to the base folder. I created a typography partial and saved it to the base folder. I created different component partials that grouped together the major sections of the site. Inside of the utilities folder, I created variables and mixins partials. In each of the scss sub-folders, I created an _index.scss file. These files are used to import individual partials from each sub-folder. I created a styles.scss, which is used to import all of the _index.scss files from the sub-folders. I used Scout-App to watch the Sass directories for changes and then automatically imported those changes to their respective Sass files. I created 5 color variables. I created a variable to be used for all media queries. I fulfilled the "exceeds expectations" requirements by using a media query mixin for all media queries, by using nested selectors, by creating a hover effect for buttons, which lightend the button's background color by 15% and by adding a CSS transition so that the color change fades in.

This project was designed according to the provided mockups.

**Exceeds Expectations Requirements:**

Create a media query mixin.

- Create a mixin that creates a media query inside of the selector that calls the mixin.
- The mixin should accept a single parameter for the size of the media query breakpoint.
- The mixin should create a min-width media query only.

Use the media query mixin for all media queries.

Use a nested selector structure for at least one component.

- Create a base selector for a group of related styles.
- Inside of that selector, use the Sass parent selector: & to append a child class selector to the base. An example would be in the navigation component use .nav as the base selector, and nest .nav-link inside of it.

Use built in Sass function to add hover effect.

- Created a hover effect for buttons.
- For the effect, lighten the button's background color by 15%.
- Add a CSS transition so that the color change fades in.

**Grade Received:**

Exceeds Expectations

You can see the live project at the following link: https://shoaibkamalkhan.github.io/.

You can see my portfolio at the following link: https://shoaibkamalkhan.github.io.

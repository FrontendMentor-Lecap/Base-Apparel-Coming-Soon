# Frontend Mentor - Base Apparel coming soon page solution

This is a solution to the [Base Apparel coming soon page challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/base-apparel-coming-soon-page-5d46b47f8db8a7063f9331a0). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
  - [Useful resources](#useful-resources)

## Overview

### The challenge

Users should be able to:

- View the optimal layout for the site depending on their device's screen size
- See hover states for all interactive elements on the page
- Receive an error message when the `form` is submitted if:
  - The `input` field is empty
  - The email address is not formatted correctly

### Screenshot

![](./images/screenshot.jpg)

### Links

- Solution URL: [https://github.com/FrontendMentor-Lecap/Base-Apparel-Coming-Soon]
- Live Site URL: [https://frontendmentor-lecap.github.io/Base-Apparel-Coming-Soon]

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow
- Javascript DOM

### What I learned

I have applied a lot of my learning in this project. Positioning elements inside parent elements, setting background images with a correct size and positioning was also essential. I also noted that the majority of times my restrictions regarding forms were included in the HTML instead of JS, by using a "required" or "type: email" I evaded the use of JS. But the 2 most important learning parts were:

1. Positioning the form button next to the input. In this case I positioned it by using an absolute value in respect with its parent element, which is an input container. This way, it doesn't matter if the width or height of the screen changes the button will remain in that position, I don't know if that is the best alternative but I think it works for me.

2. Using Javascript seems easy when performing tutorials and doing courses, but when it is time to put it in action, well... it is another story. In this case and with my current html and css settings 3 things had to change when an error ocurred:
   i. Error Icon should appear.
   ii. Error message should appear.
   iii. Border must change in the container

I had to go back and forward watching youtube videos and reading forums in order to get it done. I'm sure all the JS code that I wrote could be cleaned a lot, and better techniques must be available, but once again, it initially works for me.

### Continued development

I need to continue developing my JS skills to increase general technique and also improve code. It must be cleaner and more undestandable for other developers out there. I also need to continue improving the general alignment, sizing and ordering of elements in order to reduce the use of media queries and instead having a better component flow (if that is even an understandable term).

### Useful resources

- [https://stackoverflow.com/questions/60272725/email-validation-using-javascript-with-a-custom-message-below-the-input-field] - This page helped me with the Javascript error handling and most importantly with the regexMatch to identify if the text inserted in the field was a valid email address.
- [https://www.youtube.com/watch?v=In0nB0ABaUk&t=203s] - This is a video that helps adding error messages in forms, I recommend it as a useful resource with a short and clear explanation.

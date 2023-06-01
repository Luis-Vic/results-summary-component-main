# results-summary-component-main
 
## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
  - [Useful resources](#useful-resources)
- [Author](#author)


**Note: Delete this note and update the table of contents based on what sections you keep.**

## Overview

### The challenge

Users should be able to:

- View the optimal layout for the interface depending on their device's screen size
- See hover and focus states for all interactive elements on the page

### Screenshot

![](./screenshotproject. png) 

### Links

- Solution URL: [Add solution URL here](https://github.com/Luis-Vic/results-summary-component-main)



### Built with

- Semantic HTML5 markup
- CSS properties
- Flexbox
- Mobile-first workflow



### What I learned
In this project I learned how to use gradient backgrounds, relative unites and media queries
```css
  .first-container{
    background-image: linear-gradient(180deg, hsl(252, 100%, 67%), hsl(241, 81%, 54%));
    border-radius: 1.5em; /*24px*/
    height: 26.25em; /*24px*/
    z-index: 100;
    box-shadow: 0px 0px 1px;
}
```
```css 
  @media (min-width: 43.75em) and (max-width: 90em) {

    .wrap{
        display: flex;
        flex-direction: row;
        width: 40em; /*640px*/
        height: 26.25em; /*420px*/
        position: relative;
        margin: 1.25em auto;   
    }
  }
```

### Continued development
  relative units
  Javascript
  media queries


### Useful resources
  For this project I use https://www.w3schools.com/ - This helped me to built some blocks of the project.

## Author

- Frontend Mentor - [@Luis-Vic](https://www.frontendmentor.io/profile/Luis-Vic)




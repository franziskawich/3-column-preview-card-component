# Frontend Mentor - 3-column preview card component

This is a solution to the [3-column preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/3column-preview-card-component-pH92eAR2-). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

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
- [Author](#author)


## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover states for interactive elements

### Screenshot

![](./screenshot.png)

### Links

- Solution URL: [https://github.com/franziskawich/3-column-preview-card-component/](https://github.com/franziskawich/3-column-preview-card-component/)
- Live Site URL: [https://franziskawich.github.io/3-column-preview-card-component/](https://franziskawich.github.io/3-column-preview-card-component/)

## My process

### Built with

- Semantic HTML5 markup
- SCSS (saved as CSS)
- Flexbox
- Mobile-first workflow
- BEM methodology

### What I learned

media query with two breakpoints.

```css
@media only screen and (min-width: 28.1em) and (max-width: 56.5em) {
  .card__heading {
    display: inline;
    margin-left: 1rem;
  }
```

vertical align text-bottom, ch unit


```css
{
  display: flex;
  flex: 0 0 100%;
  }
```



### Continued development

Zoom attribution


### Useful resources

- [MDN: Vertical-align](https://developer.mozilla.org/en-US/docs/Web/CSS/vertical-align) - This helped me with ...


## Author

- Frontend Mentor - [@franziskawich](https://www.frontendmentor.io/profile/franziskawich)
- freeCodeCamp - [Franziska Wich](https://www.freecodecamp.org/fcc35fab9df-6b8c-445e-8aec-36ee00e99ba0)

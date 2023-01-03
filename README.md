# Frontend Mentor - Order summary card solution

This is a solution to the [Order summary card challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/order-summary-component-QlPmajDUj). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

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

- See hover states for interactive elements

### Screenshot

![](screenshot.png)

### Links

- Solution URL: [Solution](https://github.com/JustANipple/order-summary-component/blob/master/style.css)
- Live Site URL: [Live site](https://justanipple.github.io/order-summary-component/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Josh's Custom CSS Reset
- Custom properties
- Media queries

### What I learned

I removed the image standing in the main container just hiding the part that overflows

```css
.container {
  background-color: white;
  max-width: 450px;
  max-height: min-content;
  border-radius: 1.5rem;
  /* Hide image corners that don't get border radius */
  overflow: hidden;
  box-shadow: 0px 20px 60px -30px var(--neutral-desaturated-color);
  margin: 1rem;
}
```
### Continued development

Spacing is still something i don't really see as fixed values, so i try with relative units (rem) until i get it as close as the design is

### Useful resources

- [Remove part that overflows](https://developer.mozilla.org/en-US/docs/Web/CSS/overflow) - This helped me to remove the image corners to make it show the radius part of the container.
## Author

- Frontend Mentor - [@JustANipple](https://www.frontendmentor.io/profile/JustANipple)

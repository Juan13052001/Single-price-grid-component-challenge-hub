# Frontend Mentor - Single price grid component solution

This is a solution to the [Single price grid component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/single-price-grid-component-5ce41129d0ff452fec5abbbc). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Frontend Mentor - Single price grid component solution](#frontend-mentor---single-price-grid-component-solution)
  - [Table of contents](#table-of-contents)
  - [Overview](#overview)
    - [The challenge](#the-challenge)
    - [Screenshot](#screenshot)
    - [Links](#links)
  - [My process](#my-process)
    - [Built with](#built-with)
    - [What I learned](#what-i-learned)
    - [Continued development](#continued-development)
  - [Author](#author)

**Note: Delete this note and update the table of contents based on what sections you keep.**

## Overview

### The challenge

Users should be able to:

- View the optimal layout for the component depending on their device's screen size
- See a hover state on desktop for the Sign Up call-to-action

### Screenshot

DESKTOP

![](/screenshot-desktop.jpeg)

MOBILE
![](/screenshot-mobile.jpeg)
### Links

- Solution URL: [GitHub](https://github.com/Juan13052001/Single-price-grid-component-challenge-hub)
- Live Site URL: [Live Site](https://juan13052001.github.io/Single-price-grid-component-challenge-hub/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- CSS Grid

### What I learned

I learned how to use the grid-template-tasks and modify them to fit the screen size here you can see that instead of using two rows as in the desktop site, I set another row/area so that each one occupies 100% of the space I set. 

```css
@media(max-width: 375px) {
    .container {
        margin: 50px auto;
        display: grid;
        grid-template-columns: repeat(auto-fit, 300px);
        grid-template-rows: repeat(3, 1fr);
        grid-template-areas: 'top'
            'subscription'
            'whyUs';
        width: 350px;
        height: 700px;
        padding: 0;
    }
```

### Continued development

## Author
- Frontend Mentor - [@Juan13052001](https://www.frontendmentor.io/profile/Juan13052001)

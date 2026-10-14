# Frontend Mentor - Meet landing page solution

This is a solution to the [Meet landing page challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/meet-landing-page-rbTDS6OUR). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

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

![Screenshot](/images/screenshot.png)

### Links

- Solution URL: [https://github.com/Segarur21/meet-landing-page](https://github.com/Segarur21/meet-landing-page)
- Live Site URL: [https://segarur21.github.io/meet-landing-page/](https://segarur21.github.io/meet-landing-page/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid 
- Mobile-first workflow

### What I learned

Working on this project was an incredible exercise to master advanced **CSS Grid** layouts and responsive design while keeping the original HTML structure completely untouched. 

I am particularly proud of how I structured the complex desktop layouts for both the hero section and the footer using `grid-template-areas` and exact track sizing (`minmax`) to match design specifications precisely:

```css
@media screen and (min-width: 83rem) {
  .hero {
    display: grid;
    grid-template-columns: 1fr 1fr 1fr;
    grid-template-areas:
      "logo logo logo"
      "left content right";
    align-items: center;
    max-width: 144rem;
    margin-inline: auto;
  }
  
  .experience {
    display: grid;
    grid-template-columns: minmax(0, 30rem) minmax(0, 32rem) minmax(0, 28rem);
    grid-template-areas:
      "mark mark mark"
      "title content button";
    align-items: center;
    justify-content: center;
    column-gap: 10rem;
  }
}
```

### Continued development

In future projects, I want to continue refining my expertise in complex responsive grid architectures, ensuring pixel-perfect alignment and scaling across diverse viewport sizes while maintaining a clean, optimized CSS codebase.

### Useful resources

## Author

- Frontend Mentor - [@Segarur21](https://www.frontendmentor.io/profile/Segarur21)
- Github - [@Segarur21](https://www.github.com/Segarur21)
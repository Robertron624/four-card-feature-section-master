# Frontend Mentor - Four card feature section solution

This is a solution to the [Four card feature section challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/four-card-feature-section-weK1eFYK). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

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

- View the optimal layout for the site depending on their device's screen size

### Screenshot

### Links

- Solution URL: [Solution URL](https://github.com/Robertron624/four-card-feature-section-master)
- Live Site URL: [Live site URL](https://incomparable-frangipane-f545ff.netlify.app)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow

### What I learned

This project helped me learn some display grid options and how to use them, like grid-template-columns and grid-template-rows and align-conten and justify-content.


How to handle the layout in desktop according to the design.
```css
    .cards {
        display: grid;
        grid-template-columns: repeat(3, 1fr);
        justify-content: center;
        margin-inline: auto;
        align-content: center;
        max-width: 62rem;
    }

    .card {
        width: 17rem;
        height: 12rem;
        margin: 0 auto;
    }

    /* center first and last column vertically */
    .card:nth-child(n+1) {
        align-self: center;
    }

    .middle__cards {
        display: flex;
        flex-direction: column;
        gap: 2rem;
    }
```

### Continued development

If I were to continue this project, I would add more media queries to make it more responsive. I would also add more content to the page, like a footer and a header. I would also add more styling to the page, like a background image and a different font.

## Author

- Personal Website - [Robert Ramirez](https://robert-ramirez.netlify.app)
- Frontend Mentor User- [@Robertron624](https://www.frontendmentor.io/profile/Robertron624)
- Twitter - [@robertdowny](https://www.twitter.com/robertdowny)


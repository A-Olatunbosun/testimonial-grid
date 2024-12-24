# Frontend Mentor - Testimonials grid section solution

This is a solution to the [Testimonials grid section challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/testimonials-grid-section-Nnw6J7Un7).

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Useful resources](#useful-resources)
- [Author](#author)

## Overview

### The challenge

The challenge is to build out this testimonials grid section and get it looking as close to the design as possible using any tools to help complete the challenge.

Users should be able to:

- View the optimal layout for the site depending on their device's screen size

### Screenshot

![](./design/desktop-design.jpg)

### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)
- Live Site URL: [Add live site URL here](https://your-live-site-url.com)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow

### What I learned

I learned how to use CSS Grid to create layouts by utilizing various properties such as grid-template-columns, grid-column, grid-row, and more. I gained an understanding of how to position items using grid lines and how to span items across multiple rows and columns. Additionally, I applied the Mobile-First approach while building this project.

```css
.testimonials {
  display: grid;
  gap: 30px;
}

@media (min-width: 768px) {
  .testimonials {
    width: 90%;
    grid-template-columns: repeat(2, 1fr);
  }

  .card-one {
    grid-column: 1 / 3;
  }

  .card-two {
    grid-column: 1 / 2;
  }

  .card-three {
    grid-column: 2 / 3;
    grid-row: 2 / 3;
  }

  .card-four {
    grid-column: 1 / 3;
    grid-row: 3 / 4;
  }

  .card-five {
    grid-column: 1 / 3;
    grid-row: 4/5;
  }
}
```

### Useful resources

- [W3schools](https://www.w3schools.com/) - This is an amazing web-developer site that provide free tutorials and hands-on coding excercise, free and online tutorials with lots of examples. I'd recommend it to anyone learning web-development

## Author

- Frontend Mentor - [@A-Olatunbosun](https://www.frontendmentor.io/profile/A-Olatunbosun)
- Twitter - [@OlaTunBozz](https://x.com/OlaTunBozz)

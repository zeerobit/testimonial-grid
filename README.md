# Frontend Mentor - Testimonials grid section solution


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

-This is a solution to the [Testimonials grid section challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/testimonials-grid-section-Nnw6J7Un7). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 


### The challenge

- Build it to look as close as possible to the design provided.

Users should be able to:

- View the optimal layout for the site depending on their device's screen size

### Screenshot

![desktop-preview](https://user-images.githubusercontent.com/49578782/147886177-b0f95ea7-0523-473a-9dc0-386aa57b5fd3.jpg)


### Links

- Solution URL: https://www.frontendmentor.io/solutions/testimonial-grid-with-html5-and-grid-areas-GdWdhnJNG
- Live Site URL: https://zeerobit.github.io/testimonial-grid/

## My process

- Visualize the layout then started with mobile design first, added media query and used grid-areas for desktop layout

### Built with

- Semantic HTML5 markup
- CSS custom properties
- CSS Grid
- Mobile-first workflow
- [Styled Components](https://fonts.google.com/specimen/Barlow+Semi+Condensed)


### What I learned

- Learned that grid-template-rows is not always needed, in this challenge the second row was created automatically since there was not enough space to fit the fourth column in one row

To see how you can add code snippets, see below:


```css
 .testimonial__grid {
    max-width: 69rem;
    display: grid;
    grid-template-columns: repeat(4, 1fr);
    column-gap: 1.2rem;
    grid-template-areas:
      "card1 card1  card2 card5"
      "card3 card4  card4 card5 ";
  }
```


### Continued development

- building more complex grid layout in order to continue to improve my skills


### Useful resources

- [MDN] https://developer.mozilla.org/en-US/


## Author

- Frontend Mentor - [@Dblack84](https://www.frontendmentor.io/profile/Dblack84)
- Twitter - [@D_Black84](https://www.twitter.com/D_Black84)

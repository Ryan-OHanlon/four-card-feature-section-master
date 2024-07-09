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
  - [Useful resources](#useful-resources)
- [Author](#author)

## Overview

### The challenge

Users should be able to:

- View the optimal layout for the site depending on their device's screen size

### Screenshot

![screenshot](./screenshot.jpeg)

### Links

- Solution URL: [https://www.frontendmentor.io/solutions/four-card-feature-section-with-css-grid-and-flexbox-uNR-46dAKP](https://www.frontendmentor.io/solutions/four-card-feature-section-with-css-grid-and-flexbox-uNR-46dAKP)
- Live Site URL: [https://ryan-ohanlon.github.io/four-card-feature-section-master/](https://ryan-ohanlon.github.io/four-card-feature-section-master/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow

### What I learned

This challenge was my first attempt at using CSS Grid. The interesting thing was that to complete this challenge I had to use both CSS Grid and CSS Flexbox for both the mobile and desktop layout.

What I pulled away from this challenge is that using both Grid and Flexbox is best for responsive web design as you can use flexbox for the content and use grid for the overall layout of the website.

Using Grid is really complicated as trying to place container elements to a specific place is difficult. It was interesting to learn that you can a period (.) in with grid-template areas to place an empty spot on the grid.

```css
    main{
        display: grid;
        grid-template-columns: repeat(3, 1fr);
        grid-template-rows: repeat(4, 1fr);
        grid-template-areas: 
            ".team-builder."
            "supervisor team-builder calculator"
            "supervisor karma calculator"
            ". karma .";
        gap: 2rem;
```

### Continued development

I certainly want to continue using CSS Grid in future projects as the challenges increase in difficulty, I'll need to be able to know how to place elements in specific places on the webpage.

The other thing I still need to develop is learning how to measure and size elements while making them responsive. I try to make an exact match of the challenge knowing when I should have elements such as text stop being responsive at certain min-width and max-width but I can't figure out what CSS attributes or combination of attributes I'm not using to make that possible.

### Useful resources

- [Interactive Guide to Flexbox](https://www.joshwcomeau.com/css/interactive-guide-to-flexbox) - This helped me gain a deeper understanding of flexbox to be able to move individual elements such as the images to the left or right when they are under a flexbox.
- [Interactive Guide to CSS Grid](https://www.joshwcomeau.com/css/interactive-guide-to-grid) - This interactive guide helped me learn the fundamentals of CSS Grid. I would certainly recommend this to understand CSS Grid at a high level that will help you complete the desktop design of this challenge. You'll want to make the grid layout as the parent and then have the containers as the child.

## Author

- Website - [Ryan O'Hanlon](https://ryan-ohanlon.github.io/)
- Frontend Mentor - [@Ryan-OHanlon](https://www.frontendmentor.io/profile/Ryan-OHanlon)
- Twitter - [@RyanROHanlon](https://x.com/RyanROHanlon)


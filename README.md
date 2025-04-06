# Frontend Mentor - Stats preview card component solution

This is a solution to the [Stats preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/stats-preview-card-component-8JqbgoU62). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
- [Author](#author)
- [Acknowledgments](#acknowledgments)

## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size

### Screenshot

- Mobile
  ![](./solvedScreenshot/Screenshot%202025-04-06%20at%2021-39-26%20Frontend%20Mentor%20Stats%20preview%20card%20component.png)
- Desktop
  ![](./solvedScreenshot/Screenshot%202025-04-06%20at%2021-39-50%20Frontend%20Mentor%20Stats%20preview%20card%20component.png)

### Links

- Solution URL: [FM-Stats-Preview-Card](https://github.com/Praveen-BE/FM-Stats-Preview-Card)
- Live Site URL: [FM-Stats-Preview-Card](https://praveen-be.github.io/FM-Stats-Preview-Card/)

## My process

- I write HTML markup based on desktop Design
- CSS reset from [Josh W Comeau](https://www.joshwcomeau.com/css/custom-css-reset/)
- i create variable for color, size, weight and font-family in rootAndReset.css file
- i write css code

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow

### What I learned

```css
.stats__img {
  position: relative;
  margin: 0;
  inline-size: 100%;
}
.stats__img:before {
  content: " ";
  position: absolute;
  inset: 0;
  z-index: 10px;
  background-color: var(--clr-primary-200);
  opacity: 0.5;
}
```

## Author

<!-- - Website - [Add your name here](https://www.your-site.com) -->

- Frontend Mentor - [@yourusername](https://www.frontendmentor.io/profile/Praveen-BE)
<!-- - Twitter - [@yourusername](https://www.twitter.com/yourusername) -->

## Acknowledgments

- Frontend Mentors
- Kevin Powell

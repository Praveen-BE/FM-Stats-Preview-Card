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
  - [Continued development](#continued-development)
  - [Useful resources](#useful-resources)
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

in Mobile view, title has First line has three words, my design has two words, normal padding did not solve this issue. I try word-wrap also, but it does not solve the problem. Anyway desktop view is ok.

i refer from [oryanhach](https://www.frontendmentor.io/profile/oryanhach) frontend mentor [website](https://oryanhach.github.io/stats-preview-card-component/)

```css
.stats__content__summary h1 {
  font-size: calc(var(--fs-normal) * 2);
  line-height: 2rem;
  text-wrap: wrap;
  overflow-wrap: break-word;
}
```

## Author

<!-- - Website - [Add your name here](https://www.your-site.com) -->

- Frontend Mentor - [@yourusername](https://www.frontendmentor.io/profile/Praveen-BE)
<!-- - Twitter - [@yourusername](https://www.twitter.com/yourusername) -->

## Acknowledgments

- Frontend Mentors
- Kevin Powell

# Frontend Mentor - 3-column preview card component solution

This is a solution to the [3-column preview card component challenge on Frontend Mentor](https://divines-column-card-challenge.netlify.app/). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)

## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover states for interactive elements

### Screenshot

![Mobile View](./screenshots/Web%20capture_12-9-2023_223536_127.0.0.1.jpeg)
![Desktop View](./screenshots/Web%20capture_12-9-2023_223912_127.0.0.1.jpeg)

### Links

- Solution URL: [github.com/I-Divine/3-column-preview-card-component-main](github.com/I-Divine/3-column-preview-card-component-main)
- Live Site URL: [https://divines-column-card-challenge.netlify.app/](https://divines-column-card-challenge.netlify.app/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Mobile-first workflow

### What I learned

I really like how the transition effect turned out:

```css
.link :hover {
  background-color: rgba(0, 0, 0, 0);
  color: hsl(0, 0%, 95%);
}
.link a {
  border: 3px solid hsl(0, 0%, 95%);
  padding: 7px 25px;
  border-radius: 30px;

  font-family: "Lexend Deca", sans-serif;
  text-decoration: none;
  font-size: 15px;

  background-color: hsl(0, 0%, 95%);

  transition-property: color background-color;
  transition-duration: 200ms;
}
```

### Continued development

I would like to learn more on mobile first design and responsive web design;

## Author

- Frontend Mentor - [@GamerZwrld](https://www.frontendmentor.io/profile/GamerZwrld)
- Twitter - [@IgwedinmaI](https://www.twitter.com/IgwedinmaI)

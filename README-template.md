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

Add a screenshot of your solution. The easiest way to do this is to use Firefox to view your project, right-click the page and select "Take a Screenshot". You can choose either a full-height screenshot or a cropped one based on how long the page is. If it's very long, it might be best to crop it.

Alternatively, you can use a tool like [FireShot](https://getfireshot.com/) to take the screenshot. FireShot has a free option, so you don't need to purchase it.

Then crop/optimize/edit your image however you like, add it to your project, and update the file path in the image above.

**Note: Delete this note and the paragraphs above when you add your screenshot. If you prefer not to add a screenshot, feel free to remove this entire section.**

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

# Frontend Mentor - Bento grid solution

This is a solution to the [Bento grid challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/bento-grid-RMydElrlOj). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

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

- View the optimal layout for the interface depending on their device's screen size

### Screenshot

![](./bento.png)


### Links

- Live Site URL: [Add live site URL here](https://esther-bento-grid.netlify.app/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flex
- CSS Grid


### What I learned

While working on this project, I learned the importance of:
- Combining CSS Grid and Flexbox to create flexible layouts.
- Using media queries to ensure responsiveness across different devices.
- Managing pseudo-elements like `::after` to enhance design while keeping it adaptable for mobile screens.

Example code snippet demonstrating the use of CSS Grid for layout:

```css
.grid-container {
    display: grid;
    grid-template-columns: 1fr 1fr 1fr 1fr;
    grid-template-rows: auto;
    grid-template-areas:"item1 item2 item2 item6"
                        "item1 item4 item5 item6"
                        "item3 item8 item7 item7";
    gap: 27px;
    padding: 80px 160px;
    background-color: #f5f5f5;
    position: relative;
}

### Continued development

In the future, I aim to:

- Improve accessibility by incorporating ARIA landmarks and better keyboard navigation.
- Explore more advanced CSS techniques like animations and transitions to enhance the UI/UX.

### Useful resources

- [CSS-Tricks](https://css-tricks.com/) - This resource was invaluable for understanding CSS Grid.
- [MDN Web Docs - Media Queries](https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_media_queries/Using_media_queries) - Helped refine my responsive design approach.

## Author

- Website - [Esther AJAYI](https://esther-bento-grid.netlify.app/)
- Frontend Mentor - [@esther-must](https://www.frontendmentor.io/profile/esther-must)
- Twitter - [@adexdainty92](https://x.com/adexdainty92)

## Acknowledgments

A big thank you to Frontend Mentor for creating these challenges. They’ve been instrumental in helping me sharpen my skills.

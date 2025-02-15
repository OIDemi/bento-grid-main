# Frontend Mentor - Bento grid solution

This is a solution to the [Bento grid challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/bento-grid-RMydElrlOj). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Table of contents

- [Overview](#overview)

  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)

**Note: Delete this note and update the table of contents based on what sections you keep.**

## Overview

Bento Grid layout using CSS Grid.

### The challenge

Users should be able to:

- View the optimal layout for the interface depending on their device's screen size

### Screenshot

![Bento Grid](./assets/images/Bento%20Grid.png)

### Links

- Solution URL: [Github](https://github.com/OIDemi/bento-grid-main)
- Live Site URL: [Add live site URL here](https://oidemi.github.io/bento-grid-main/)

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow

### What I learned

This challenge really pushed me to my limit. I learnt the basics of CSS Grid including grid-template-areas.
To see how you can add code snippets, see below:

```css
.grid-container {
  grid-template-columns: repeat(4, 1fr);
  grid-template-areas:
    "create social social schedule"
    "create manage posting schedule"
    "content manage posting schedule"
    "content audience followers followers";
  grid-template-rows: 1fr 50px 0.7fr;
}
```

### Continued development

-Continuous practice with CSS Grid

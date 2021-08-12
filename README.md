# Frontend Mentor - Stats preview card component solution

This is a solution to the ![Stats preview card component challenge on Frontend Mentor](./design/desktop-preview.jpg). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)

## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size

### Screenshot

[Desktop version](./design/desktop-design.jpg)
[Mobile version](./design/mobile-design.jpg)

### Links

- [Solution URL](https://github.com/TMraz/Stats_preview_card_component.github.io)

- [Live Site URL](https://tmraz.github.io/Stats_preview_card_component.github.io/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- CSS Grid
- Mobile-first workflow
- [Styled Components](./css/main.css) - For Desktop style
- [Styled Components](./css/mobile.css) - For Mobile style

### What I learned

Snippets, see below:

```css
/* === color overlay === */
header::before {
    content: "";
    display: block;
    position: absolute;
    top: 0;
    bottom: 0;
    left: 0;
    right: 0;
    width: auto;
    height: auto;
    background: var(--color-span);
    opacity: .5;
}
```

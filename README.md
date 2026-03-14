# Frontend Mentor - Product preview card component solution

This is a solution to the [Product preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/product-preview-card-component-GO7UmttRfa). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
  - [AI Collaboration](#ai-collaboration)
- [Author](#author)

## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover and focus states for interactive elements

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox

### What I learned

This is my first build a RWD website, so it's kind of hard to startTT, I learned a lot like how to adjust the flex:

```css
.product-page{
  background-color: var(--color-White);
  display: flex;
  flex-direction: row;
  justify-content: center;
  align-items: stretch;
  border-radius: 10px;
  width: min(600px, 90%);
  max-width: 600px;

}
.product-page .product-image{
  flex: 1;
  height: 100%;
}
.product-page .information{
  flex: 0 0 300px;
}
```

### Continued development

I still struggle with how big should the width be and how to set the image in a good size, and why it should be flex:0 0 300px, I will try to get familiar with those things later ><!!

### AI Collaboration
GitHub Copilot

## Author

- Frontend Mentor - [@yoyo](https://www.frontendmentor.io/profile/3706188)

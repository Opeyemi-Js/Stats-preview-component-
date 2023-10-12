# Frontend Mentor - Stats preview card component solution

This is a solution to the [Stats preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/stats-preview-card-component-8JqbgoU62). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
- [Author](#author)

## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size

### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)
- Live Site URL: [Add live site URL here](https://your-live-site-url.com)

## My process

### Built with

- Semantic HTML5 markup
- Flexbox
- Mobile-first workflow

### What I learned
While coding this challenge i learnt the
difference way to apply an overlay effect on image
in css. I was able to know about three ways to achieve the effect which are:

- Using background-blend-mode property.
- Using the pseudo-element(::after)
- Linear-gradient Function.

Below are the css code used to achieve the overlay effect.

```css
.image-overlay{
  width: 100%;
  height: 20rem;
  background-image: url("./images/image-header-mobile.jpg");
  background-color: var(--accent);
  background-position: center;
  background-size: cover;
  background-blend-mode: multiply;
  border-radius: 1rem 1rem 0 0;
}
```

### Continued development
  I will keep learning and building projects/challenges to enhance my frontend skills.
  
## Author
- Twitter - [@Opeyemi_Js](https://www.twitter.com/Opeyemi_Js)

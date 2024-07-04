# Frontend Mentor - NFT preview card component solution

This is a solution to the [NFT preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/nft-preview-card-component-SbdUL_w0U). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Links](#links)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
- [Author](#author)

## Overview

First attempt at BEM. I'm not sure how this helps with writing less code, since it doesn't seem very reusable to me (unless I'm doing it wrong, which is entirely possible). 
But the fact that it doesn't rely on nesting is good, so even if I add or remove a container later on the style I applied still holds. 

For some reason the blue ::before element that appears when you hover the image is slightly bigger than it should on chrome, but not on firefox, so if I fix its height to be 98% (perfect on chrome) it's slightly too short on firefox. Go figure.

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover states for interactive elements

### Links

- Solution URL: [https://www.frontendmentor.io/solutions/nft-card-with-bem-OXmOelF2a8](https://www.frontendmentor.io/solutions/nft-card-with-bem-OXmOelF2a8)
- Live Site URL: [https://tortaruga.github.io/nft-card/](https://tortaruga.github.io/nft-card/)

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Mobile-first workflow
- BEM 

### What I learned

So, apparently I can't add a ::before pseudoelement to an img tag? That's a bummer.

### Continued development

I'll keep practicing this BEM! (alexis mateo style) until it hopefully starts to make sense to me.

## Author

- Frontend Mentor - [@tortaruga](https://www.frontendmentor.io/profile/tortaruga)

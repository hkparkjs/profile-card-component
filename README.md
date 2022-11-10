# Frontend Mentor - Profile card component solution

This is a solution to the [Profile card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/profile-card-component-cfArpWshJ). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Useful resources](#useful-resources)
- [Author](#author)

## Overview

### The challenge

- Build out the project to the designs provided

### Screenshot

![](./screenshot-desktop.png)
![](./screenshot-mobile.png)


### Links

- Solution URL: [https://github.com/hkparkjs/profile-card-component](https://github.com/hkparkjs/profile-card-component)
- Live Site URL: [https://park-profile-card-component.netlify.app/](https://park-profile-card-component.netlify.app/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Mobile-first workflow

### What I learned

- How to set a position of background images
```css
body {
  (...)
  background-color: var(--dark-cyan);
  background-image: url('./images/bg-pattern-top.svg'), url('./images/bg-pattern-bottom.svg');
  background-positon: top -374px right 52vw, top 50vh left 50vw;
  background-repeat: no-repeat;
}
```

### Useful resources

- [MDN - background-position](https://developer.mozilla.org/en-US/docs/Web/CSS/background-position) - This helped me for setting a location of background images.

## Author

- Frontend Mentor - [@hkparkjs](https://www.frontendmentor.io/profile/hkparkjs)
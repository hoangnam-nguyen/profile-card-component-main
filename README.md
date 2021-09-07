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
- [Author](#author)


## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size

### Screenshot

![](./images/screenshot_desktop.png)
![](./images/screenshot_mobile.png)


### Links

- Solution URL: [https://github.com/hoangnam-nguyen/profile-card-component-main](https://github.com/hoangnam-nguyen/profile-card-component-main)
- Live Site URL: [https://hoangnam-nguyen.github.io/profile-card-component-main/](https://hoangnam-nguyen.github.io/profile-card-component-main/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Mobile-first workflow


### What I learned

- Create horizontal line by pseudo-element:

```css
.info::after {
    content: '';
    display: block;
    width: 35rem;
    height: 1.5px;
    background-color: var(--clr-neutral-gray);
    opacity: 0.25;
}
```

- Add two background images and background-color. Adjust image size and position, all within `background`:

```css
body {
    background:
        url('images/bg-pattern-bottom.svg') 65rem 35rem no-repeat,
        url('images/bg-pattern-top.svg') -30rem -50rem no-repeat;
    background-color: var(--clr-primary-cyan);
    background-blend-mode: overlay;
}
```


## Author

- GitHub - [Nguyen Hoang Nam](https://github.com/hoangnam-nguyen)
- Frontend Mentor - [@hoangnam-nguyen](https://www.frontendmentor.io/profile/hoangnam-nguyen)
- CodePen - [@hoangnam-nguyen](https://codepen.io/hoangnam-nguyen)



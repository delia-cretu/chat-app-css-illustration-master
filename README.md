# Frontend Mentor - Chat app CSS illustration solution

This is a solution to the [Chat app CSS illustration challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/chat-app-css-illustration-O5auMkFqY). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

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

## Overview

### The challenge

Users should be able to:

- View the optimal layout for the site depending on their device's screen size
- See hover states for all interactive elements on the page

### Screenshot

![](./screenshot.jpg)

### Links

- Solution URL: https://github.com/delia-cretu/chat-app-css-illustration-master
- Live Site URL: https://delia-cretu.github.io/chat-app-css-illustration-master/

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties

### What I learned

I was proud that I figured out how to make the arrow and the 3-point menu figures on the top of the phone screen using div's:

```css
.header-arrow {
  background-color: transparent;
  border-top: 2.5px solid white;
  border-left: 2.5px solid white;
  width: 7px;
  height: 7px;
  position: absolute;
  left: 17px;
  top: 38px;
  transform: rotate(-45deg);
}

.header-menu {
  border-left: 2px dotted white;
  width: 8px;
  height: 8px;
  position: absolute;
  right: 12px;
  top: 38px;
}
```

It was a challenge to make the background purple shapes using CSS only and utilising the properties of the border-radius function but I was thrilled to figure out this solution:

```css
.purple-shape1 {
  border-radius: 0 0 50% 50% / 0 0 40% 40%;
}
```

```css
.purple-shape1 {
  border-radius: 60% 35% 0 0 / 40% 10% 0 0;
}
```

I learned that in order to use vertical-align with span element I needed to do the following:

```css
.button-time {
  display: inline-block;
  height: 20px;
  vertical-align: middle;
}
```

### Continued development

I have more to learn about the following:

- using the position function correctly and efficiently
- using basic CSS tools to draw different shapes

### Useful resources

- https://www.sitepoint.com/setting-css3-border-radius-with-slash-syntax/ - This resource really helped me understand how to use border-radius with slash syntax.

```

```

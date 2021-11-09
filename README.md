# Frontend Mentor - Profile card component solution

This is a solution to the [Profile card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/profile-card-component-cfArpWshJ). 

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

- Build out the project to the designs provided

### Screenshot

![desktop-design](https://user-images.githubusercontent.com/58538880/140856939-4b2153e2-e5ba-4158-acbd-6a97bfc3abb6.jpg)
![mobile-design](https://user-images.githubusercontent.com/58538880/140856944-a678be55-dd88-4186-ac91-c230cdd4b2a6.jpg)


### Links

- Live Site URL: [Live Demo](https://rluna15.github.io/profile-card-component/)

## My process

### Built with

- HTML5
- Sass
- Gulp (Compile Sass)

### What I learned
Working with multiple background images was something that I've never done before and manipulating the position around the element was interesting to learn.

```css
@use "../utilities/" as *;

.bg {
  width: 100vw;
  height: 100vh;
  background-color: $Dark-cyan;
  background-image: url("../../../images/bg-pattern-top.svg"),
    url("../../../images/bg-pattern-bottom.svg");
  background-repeat: no-repeat, no-repeat;
  background-position: right 50vw bottom 50vh, left 50vw top 50vh;
  @include center-flex;
}

```

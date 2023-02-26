# Frontend Mentor - Chat app CSS illustration solution

This is a solution to the [Chat app CSS illustration challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/chat-app-css-illustration-O5auMkFqY). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
- [Author](#author)

## Overview

### The challenge

Users should be able to:

- View the optimal layout for the component depending on their device's screen size
- **Bonus**: See the chat interface animate on the initial load

### Links

- Solution URL: [https://www.frontendmentor.io/solutions/chat-app-css-illustration-NGJMP_pvSo](https://www.frontendmentor.io/solutions/chat-app-css-illustration-NGJMP_pvSo)
- Live Site URL: [https://seranela.github.io/chat-app-css-illustration/](https://seranela.github.io/chat-app-css-illustration/)

## My process

### Built with

- HTML5
- CSS
- Flexbox
- Mobile-first workflow

### What I learned

I was wondering if I could create the capsule effect simply by using a sized `div` with the `border-radius` trick. It didn't seem to work for an elongated large div. I ended up using `clip-path: path()` along with `transform` to get the desired look.

I used CSS instead of JavaScript to create the effect of chat messages popping up on the screen by using the `animation-delay` property and `id`'s with a sequencing of delay values.

## Author

- Frontend Mentor - [@seranela](https://www.frontendmentor.io/profile/seranela)
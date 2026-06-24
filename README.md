# Frontend Mentor - Social Links Profile Solution

This is a solution to the [Social links profile challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/social-links-profile-UG32l9m6dQ). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
- [Author](#author)

---

## Overview

### The challenge

Users should be able to:

- See hover and focus states for all interactive elements on the page

### Screenshot

![Social Links Profile Solution](./screenshot.jpg)

### Links

- Solution URL: [Add your solution URL here](https://github.com/Otaku2Phoenix/Social-Link-Profile)
- Live Site URL: [Add your live site URL here](https://otaku2phoenix.github.io/Social-Link-Profile/)

---

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Mobile-first workflow

### What I learned

This was my first time centering a card both vertically and horizontally using flexbox on the body:

```css
body {
  display: flex;
  align-items: center;
  justify-content: center;
  min-height: 100vh;
}
```

I also learned how to make a circular avatar image using `border-radius: 50%`:

```css
.card img {
  width: 88px;
  height: 88px;
  border-radius: 50%;
  object-fit: cover;
}
```

And how to use CSS custom properties to store colors in one place:

```css
:root {
  --green: hsl(75, 94%, 57%);
  --grey-900: hsl(0, 0%, 8%);
}
```

### Continued development

In future projects I want to focus on:

- Getting more comfortable with flexbox and CSS Grid
- Writing cleaner, more organized HTML
- Improving my understanding of responsive design

---

## Author

- Frontend Mentor - [@yourusername](https://www.frontendmentor.io/profile/yourusername)

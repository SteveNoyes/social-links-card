## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [Highlight](#highlight)

## Overview

### The challenge

Users should be able to:

- See hover and focus states for all interactive elements on the page

### Screenshot

![Desktop View](./asset/images/Screenshot 2024-08-18 211758.png)

### Links

- Solution URL: [https://github.com/SteveNoyes/social-links-card](https://github.com/SteveNoyes/social-links-card)
- Live Site URL: [https://stevenoyes.github.io/social-links-card/](https://stevenoyes.github.io/social-links-card/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow

### Highlight

```html
<div class="card-wrapper">
  <div class="info-content">
    <img src="./assets/images/avatar-jessica.jpeg" alt="Card Avatar">
    <h2>Jessica Randall</h2>
    <h3>London, United Kingdom</h3>
    <p>"Front-end developer and avid reader."</p>
  </div>
  <div class="card-button-list">
    <button>GitHub</button>
    <button>Frontend Mentor</button>
    <button>LinkedIn</button>
    <button>Twitter</button>
    <button>Instagram</button>
  </div>
</div>
```
```css
:root {
  --green: hsl(75, 94%, 57%);
  --black: hsl(0, 0%, 0%);
  --white: hsl(0, 0%, 100%);
  --grey-700: hsl(0, 0%, 20%);
  --grey-800: hsl(0, 0%, 12%);
  --grey-900: hsl(0, 0%, 8%);
  --border-radius: 11px;
}
```
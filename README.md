# Frontend Mentor - QR Code Component Solution

This is my solution to the [QR code component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/qr-code-component-i92MgR2Uwh). Building this project allowed me to reinforce my skills in responsive layout design, CSS reset practices, and modern alignment techniques.

## Table of Contents

- [Overview](#overview)
  - [The Challenge](#the-challenge)
  - [Links](#links)
- [My Process](#my-process)
  - [Built With](#built-with)
  - [What I Learned](#what-i-learned)
- [Author](#author)

## Overview

### The Challenge

Users should be able to:
- View the optimal layout for the component depending on their device's screen size
- Experience smooth hover feedback on the card

### Links

- Solution URL: [GitHub Repository](https://github.com/your-username/qr-code-component)
- Live Site URL: [Netlify Live Demo](https://your-site-name.netlify.app)

## My Process

### Built With

- Semantic HTML5 markup
- CSS custom properties & Google Fonts (Outfit)
- Flexbox for centering and structured layout
- Mobile-first, fluid responsive design (`max-width` and relative units)

### What I Learned

In this challenge, I practiced writing clean, predictable layout structures. A key concept I focused on was applying `box-sizing: border-box` to manage card dimensions accurately without layout shifts caused by padding.

```css
* {
  box-sizing: border-box;
  margin: 0;
  padding: 0;
}

.card {
  max-width: 320px;
  width: 90%;
  padding: 15px;
}
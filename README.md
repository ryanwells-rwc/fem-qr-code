# Frontend Mentor - QR code component solution

This is a solution to
the [QR code component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/qr-code-component-iux_sIO_H).
Frontend Mentor challenges help you improve your coding skills by building
realistic projects.

## Table of contents

- [Overview](#overview)
    - [Screenshot](#screenshot)
    - [Links](#links)
- [My process](#my-process)
    - [Built with](#built-with)
    - [What I learned](#what-i-learned)
    - [Continued development](#continued-development)
    - [Useful resources](#useful-resources)
- [Author](#author)
- [Acknowledgments](#acknowledgments)

## Overview

### Screenshot

![Screenshot](./images/screenshot.png)

### Links

- Solution URL: [Github](https://github.com/ryanwells-rwc/fem-qr-code)
- Live Site URL: [Netlify](https://rwc-fem-qr-code.netlify.app)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Mobile-first workflow

### What I learned

I learned how to use CSS custom properties to create a reusable theme for my
project.  I also used flexbox to position elements in a responsive way.

```css
/* Fonts */
:root {
  --fs-15: calc(15 / 16 * 1rem);
  --fs-22: calc(22 / 16 * 1rem);

  --font-size-h1: var(--fs-22);
  --font-size-p: var(--fs-15);
}

/* Colors */
:root {
  --c-white: hsl(0, 0%, 100%);
  --c-slate-900: hsl(218, 44%, 22%);
  --c-slate-500: hsl(216, 15%, 48%);
  --c-slate-300: hsl(212, 45%, 89%);

  --color-main-bg: var(--c-slate-300);
  --color-h1: var(--c-slate-900);
  --color-p: var(--c-slate-500);
}
```

```css
.qr-code {
  display: flex;
  align-items: center;
  justify-content: center;
  height: 100vh;
```

### Continued development

I plan to continue working with flexbox and grid to build layouts for more 
complex projects.

### Useful resources

- [coder-coder.com](https://coder-coder.com) - Great resource for learning 
  CSS, semantic HTML, and accessibility.

## Author

- Website - [ryanwells.io](http://ryanwells.io)
- Frontend
  Mentor - [@ryanwells-rwc](https://www.frontendmentor.io/profile/ryanwells-rwc)
- GitHub - [@ryanwells-rwc](https://github.com/ryanwells-rwc)

## Acknowledgments

Thanks to [Coder Coder](https://www.youtube.com/@TheCoderCoder) for 
providing some great resources for learning CSS and semantic HTML.
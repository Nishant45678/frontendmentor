# Frontend Mentor - QR code component solution

This is a solution to the [QR code component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/qr-code-component-iux_sIO_H). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
- [Author](#author)



## Overview

### Screenshot

![](./screenshot.png)


### Links

- Solution URL: [Click here]( https://nishant45678.github.io/QR-code-component/)


## My process

### Built with

- CSS custom properties
- Flexbox
- Mobile-first workflow



### What I learned


I learned to use CSS variables (:root custom properties) to store common values like colors. This improved code maintainability by allowing me to change colors in one place, which cascades across the whole stylesheet.


```
:root {
  --white: hsl(0, 0%, 100%);
  --slate-300: hsl(212, 45%, 89%);
  --slate-500: hsl(216, 15%, 48%);
  --slate-900: hsl(218, 44%, 22%);
}
```
Flexbox was incredibly useful for centering the entire card vertically and horizontally within the viewport, making the layout responsive and visually appealing on different screen sizes.

```
.card-body {
  min-height: 100vh;
  display: flex;
  justify-content: center;
  align-items: center;
}
```


## Author

- Website - [Nishant]()
- Frontend Mentor - [@Nishant45678](https://www.frontendmentor.io/profile/Nishant45678)



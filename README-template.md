# Frontend Mentor - QR code component solution

This is a solution to the [QR code component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/qr-code-component-iux_sIO_H). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Useful resources](#useful-resources)
- [Author](#author)


## Overview

### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)
- Live Site URL: [Add live site URL here](https://your-live-site-url.com)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flex


### What I learned

I learned some methods to center the card horizantally and vertically. Those are 1. Using flexbox, justify-content, align-items and setting height 
to viewport height for outer div so that the card can be centered vertically.

```html
<div class="flex-container">
    <div class="container">
      <img src="images/image-qr-code.png" alt="qr code of frontend mentor">

      <h2>Improve your front-end skills by building projects</h2>

      <p> Scan the QR code to visit Frontend Mentor and take your coding skills to the next level</p>
    </div>
  </div>
`````

```css
.flex-container {
    display: flex;
    height: 100vh;
    justify-content: center;
    align-items: center;
}
````

### Useful resources

- [Hubspot](https://blog.hubspot.com/website/center-div-css) - This helped me for centering the card horizantally and vertically.
- [CSS Tricks](https://css-tricks.com/centering-css-complete-guide/ - This is an amazing article which helped me finally understand XYZ. I'd recommend it to anyone still learning this concept.



## Author

[@WasimAkramS]

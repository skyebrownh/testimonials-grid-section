# Frontend Mentor - Testimonials grid section solution

This is a solution to the [Testimonials grid section challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/testimonials-grid-section-Nnw6J7Un7). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Useful resources](#useful-resources)
- [Author](#author)

## Overview

### The challenge

Users should be able to:

- View the optimal layout for the site depending on their device's screen size

### Screenshot

![Live Site Screenshot](./screenshot.png)

### Links

- [Solution URL](https://www.frontendmentor.io/solutions/pure-htmlcss-with-css-grid-and-media-queries-WlZSU1eg8)
- [Live site URL](https://skyebrownh.github.io/testimonials-grid-section/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- CSS Grid
- Mobile-first workflow

### What I learned

During this challenge, I was able to get more experience working with CSS Grid in a more complex layout.

I also learned how to select all elements of a specific class except the first:

```css
.parent > .child ~ .child {
  /* this will select all elements within parent with the class "child" except the very first one */
}
```

### Useful resources

- [CSS Grid (CSS Tricks)](https://css-tricks.com/snippets/css/complete-guide-grid/) - The ultimate CSS Grid guide.
- [CSS Background Position (W3Schools)](https://www.w3schools.com/cssref/pr_background-position.asp) - Reference for how to work with % values in background position (I used this to properly position the quotation image of the first testimonial).
- [box-shadow.dev](https://box-shadow.dev/) - I can't make a good box shadow without this tool.
- [First Element with Class Selector (Stack Overflow)](https://stackoverflow.com/questions/2717480/css-selector-for-first-element-with-class) - There is not a native way to select the first element with a specific class in CSS3. This post describes a slight workaround that can be used to select all but the first element of a class.

## Author

- Frontend Mentor - [@skyebrownh](https://www.frontendmentor.io/profile/skyebrownh)
- Twitter - [@skyebrownh](https://www.twitter.com/skyebrownh)
- GitHub - [@skyebrownh](https://www.github.com/skyebrownh)

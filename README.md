# Frontend Mentor - Order summary card solution

This is a solution to the [Order summary card challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/order-summary-component-QlPmajDUj). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
  - [Useful resources](#useful-resources)
- [Author](#author)

## Overview

### The challenge

Users should be able to:

- See hover states for interactive elements

### Links

- Solution URL: (https://github.com/moon-sheep/order-summary-challenge.git)
- Live Site URL: (https://moon-sheep.github.io/order-summary-challenge/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox

### What I learned

1. Column flex direction

First time using flex-direction: column. It's relatively easy and self-explanatory until I needed to center a div. I tried all the justify/align options but they weren't applying. Did some research and realized I overlooked the column direction while my goal is inline-block. Once I got that, the paragraph finally aligned center properly.

```css
text-align: center;
display: inline-block;
```

### Continued development

1. Rem/em vs px

I knew their function and rough measurements but I didn't understand when to use rem/em and px. A lot of articles explain different scenarios and for a beginner, it was very confusing. For a while, I was tempted to go the easy answer and stick with rem for font size and px for everything else. 

Then I found a good article comparing how to use each unit with different elements. And to keep in mind a general principle: "Should this value scale up as the user increases their browser's default font size?" I realized using rem/em/px is more reliant on intuition regarding accessibility but this was a good starting point in hopefully practicing that thinking more. Which I did for this challenge.

```css
max-width: 100%;
width: 21.5rem;
height: 50px;
```

```css
font-size: calc(12rem / 16);
```

### Useful resources

- (https://www.joshwcomeau.com/css/surprising-truth-about-pixels-and-accessibility/) - This explained the principles of when to use the proper CSS units. It has visual examples too which is great. 

## Author

- moon.sheep


# Frontend Mentor - Blog preview card solution

This is a solution to the [Blog preview card challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/blog-preview-card-ckPaj01IcS). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)

**Note: Delete this note and update the table of contents based on what sections you keep.**

## Overview

### The challenge

Users should be able to:

- See hover and focus states for all interactive elements on the page

### Screenshot

![](./screenshot.jpg)


### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)
- Live Site URL: [Add live site URL here](https://your-live-site-url.com)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow



### What I learned
- `max-width:41ch` means can only have 41 characters per line **(excluding the spacing)**
- `background-image`, `background-position` 
- `line-height` value same as it's `height` can causing the text to be vertically centered,
- margin collapse - No double spacing even using `margin-block`
-  The text is centered because the .attribution container spans the full width of its parent element (due to width: 100%;), and the text inside the block element is horizontally centered by default when no text-align property is specified. By default, browsers apply text-align: center to block elements like `<div>` in some scenarios, particularly when there is no overriding text-align specified for that element or its parent.
- Why Use rem?
Scalability:
rem units are relative to the root element's font size (default is 16px in most browsers).
If a user changes the browser's font size for accessibility, rem units adjust automatically, maintaining proportional scaling.
Consistency:

Using rem allows you to create a consistent sizing scale for fonts, paddings, margins, etc., that adapts based on the root size.
Responsive Design:

It’s easier to make your layout responsive when you define everything in relative units like rem because adjusting the root font size adjusts all rem-based values.


# Frontend Mentor - Four card feature section solution

This is a solution to the [Four card feature section challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/four-card-feature-section-weK1eFYK). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
  - [Useful resources](#useful-resources)
- [Author](#author)
- [Acknowledgments](#acknowledgments)

**Note: Delete this note and update the table of contents based on what sections you keep.**

## Overview

### The challenge

Users should be able to:

- View the optimal layout for the component depending on their device's screen size


### Screenshot

![](./images/screenshot.png)

### Links

- Solution URL: [Solution](https://github.com/AlexdelCarmen/article-preview)
- Live Site URL: [Live site](https://alexdelcarmen.github.io/article-preview/)

## My process

Began by creating the HTML structure for the component, then I styled, first for mobile devices.  Once the mobile layout was done, I created the JS script to show/hide the social media icons upon pressing the share icon.  lastly I created the media query to create the desktop layout.  
### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Mobile-first workflow
- Vanilla JavaScript. 

### What I learned

Thanks to Lucas at FrontEndMentor I started using a different set of styles to keep the components centered and the images responsive:

```css

body {
  min-height: 100vh;
  display: flex;
  align-items: center;
  justify-content: center;
  flex-direction: column;
  font-family: var(--font-family);
  font-size: var(--mid-size);
  background-color: var(--light-gray-blue);
}

.preview-img {
  display: block;
  object-fit: cover;
  max-width: 100%;
  width: 375px;
  border-radius: 15px 15px 0 0;
}

```

### Continued development

Still got to practice more the responsive layouts and what 

- [W3Schools article on multiple backgrounds on an HTML element](https://www.w3schools.com/css/) - General CSS reference.


## Author

- Website - [Github Profile](https://github.com/AlexdelCarmen)
- Frontend Mentor - [@AlexdelCarmen](https://www.frontendmentor.io/profile/AlexdelCarmen)
- Twitter - [@AlekBorchov](https://twitter.com/AlekBorchov)

## Acknowledgments

To [Lucas](https://www.frontendmentor.io/profile/correlucas), thanks for the great tips.  

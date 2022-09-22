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

- View the optimal layout for the site depending on their device's screen size


### Screenshot

![](./images/screenshot.png)

### Links

- Solution URL: [Solution](https://github.com/AlexdelCarmen/article-preview)
- Live Site URL: [Live site](https://alexdelcarmen.github.io/article-preview/)

## My process

As usual, I created the HTML structure first, next I added some custom CSS styles, then proceeded to style the mobile layout for the website.  I ended with making a simple media query to support desktop layouts.  
### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Mobile-first workflow
- Vanilla JavaScript. 

### What I learned

Kept using what I learned back in the article preview challenge and Lucas' tips to make sure the layout was looking good.  

```css

body {
  padding: 0;
  margin: 0;
  min-height: 100vh;
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
  background-color: var(--light1);
  font-family: var(--main-font);
  font-size: var(--para-size);
  color: var(--dark2);
}

.card-img {
    display: block;
    object-fit: cover;
    max-width: 100%;
    align-self: flex-end;
}

```

### Continued development

Still got to practice more my responsive layouts.  

- [W3Schools article on multiple backgrounds on an HTML element](https://www.w3schools.com/css/) - General CSS reference.


## Author

- Website - [Github Profile](https://github.com/AlexdelCarmen)
- Frontend Mentor - [@AlexdelCarmen](https://www.frontendmentor.io/profile/AlexdelCarmen)
- Twitter - [@AlekBorchov](https://twitter.com/AlekBorchov)

## Acknowledgments

To [Lucas](https://www.frontendmentor.io/profile/correlucas), thanks for the great tips.  

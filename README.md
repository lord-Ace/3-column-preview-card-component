# Frontend Mentor - 3-column preview card component solution

This is a solution to the [3-column preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/3column-preview-card-component-pH92eAR2-). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

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


## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover states for interactive elements

### Screenshot

![desktop view](images/Web%20capture_1-5-2023_152730_127.0.0.1.jpeg)
![Active states](images/Web%20capture_1-5-2023_152851_127.0.0.1.jpeg)
![mobile view](images/Web%20capture_1-5-2023_153423_127.0.0.1.jpeg)

### Links

- Solution URL: [label](index.html)
- Live Site URL: (https://3-column-preview-card-component-68fwaf20c-lord-ace.vercel.app)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- css media querry

### What I learned
I learned how to use multiple classes on an element, how to create responsive webpages based on screensize and how to use the :hover pseudo class

Using multiple classes on an element
```html
<div class="card suv">
  <img src="./images/icon-suvs.svg" alt="SUV">
  <div class="text">
    <h2>SUVs</h2>
    <p>
      Take an SUV for its spacious interior, power, and versatility. Perfect for your next family vacation 
      and off-road adventures.          
    </p>
    <a href="#" class="link"><button>learn more</button></a>
  </div>
  <div class="card luxry">
  <div class="card sedan">
```
```css
.card{
  height: 23rem;
  width: 15em;
} 
.suv{
  background-color: hsl(184, 100%, 22%);
  padding: 30px;
}
```

using media querry
```css
 @media screen and (max-width: 480px)
```

:hover pseudo class
```css
a button:hover{
  cursor: pointer;
  border: 2px solid hsl(0, 0%, 95%);
  color: hsl(0, 0%, 95%);
  background-color: unset;
}
```

### Continued development

I want to continue on css media querries to make my websites 100% responsive 👍

### Useful resources

- [free code camp](https://www.freecodecamp.org/news/css-media-queries-breakpoints-media-types-standard-resolutions-and-more/) - This helped me learn how to use media querries. I really liked this pattern and will use it going forward.

## Author

- Website - [Ashinze Emmanuel](https://www.your-site.com)
- Frontend Mentor - [@lord-Ace](https://www.frontendmentor.io/profile/lord-Ace)

## Acknowledgments

Id like to thank freecodecamp.org for giving out free lectures on media querry and other programming related courses

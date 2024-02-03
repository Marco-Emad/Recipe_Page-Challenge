# Frontend Mentor - Recipe page solution

This is a solution to the [Recipe page challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/recipe-page-KiTsR8QQKm). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
- [Author](#author)

## Overview

### Screenshot

![Screenshot 2024-02-03 093934](https://github.com/Marco-Emad/Recipe_Page-Challenge/assets/56565607/127bf2f5-0ec8-421f-9de2-58f1824a9f67)
![Screenshot 2024-02-03 093955](https://github.com/Marco-Emad/Recipe_Page-Challenge/assets/56565607/d1578c66-9f6e-4d19-b012-4f5d0b45c72f)


### Links

- Solution URL: [Click Here to see my Solution](https://www.frontendmentor.io/solutions/recipe-page-component-challenge-ctoL3H0rIG)
- Live Site URL: [Click Here to see the Live Site](https://marco-emad.github.io/Recipe_Page-Challenge/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid

### What I learned

I faced some challenges in CSS especially because there are many aspects doesn't work well with some HTML tags for example
img tag if you try to border-radius and add a padding-top the circular of the top edges break and not like the bottom edge,
so i had to contain the image inside a div tag and style the div instead with the padding like the snippet provided.

```html
    <div class="recipe-img">
      <img class="image"  src="./assets/images/image-omelette.jpeg" alt="omeletteImg">
    </div>
```
```css
 .recipe-img {
    padding: 1.5rem;
    padding-bottom: 0;
 }
.image { 
    width: 100%; 
    height: 100%; 
    object-fit: cover; 
    display: block;
    border-radius: 10px;
  }
```

## Author

- Frontend Mentor - [@Marco-Emad](https://www.frontendmentor.io/profile/Marco-Emad)

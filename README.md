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
  - [Continued development](#continued-development)
- [Author](#author)

**Note: Delete this note and update the table of contents based on what sections you keep.**

## Overview

### The challenge

Testimonials grid section

### Screenshot

   ## Desktop Screenshot  ![](./testimonials/Screenshots/Desktop%20Screenshot.jpeg) 
   ## Mobile Screenshot  ![](./testimonials/Screenshots/Mobile%20Screenshot.jpeg) 



### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)
- Live Site URL: [Add live site URL here](https://tk-ls97.github.io/testimonials/)

## My process

I started by using flexbox to postion the inner elements of the containers and then when I was satisfied with the overall styling in CSS and structure in HTML, I then moved to deal with CSS grid alone. Which made it a less frustrating workflow. 



### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- SCSS


### What I learned

In this challenge I got to learn how CSS grid works, and while it has quite a number of properties, it was relatively simple to learn and I look forward to improving my knowledge on it, since it is such a powerful tool.


In grid I learned how to use "grid-template-columns" to section containers or divs and I like how you can use fractions instead of pixels.

```css
.testimonials{
  grid-template-columns:1fr 1fr 1fr 1fr;
}
```

I also learned how to span divs to a desired length in CSS grid, whether it be rows or columns. The browser (Microsoft Edge) also had dev tools to display the grid-column and grid-row numbers so that there is no confusion.

```css
.card:nth-of-type(1){
    grid-column: 1/3;  /* spanned from grid column point 1 to point 3  */
}

.card:nth-of-type(4){
    grid-column: 2/4;
    grid-row:2;
    
}

.card:nth-of-type(5){
    grid-column: 4;
    grid-row:1/3;
}
```

### Continued development

I will continue using and learning CSS grid for future projects to enhance my knowledge of it. 


## Author

- Frontend Mentor - [@TK-LS97](https://www.frontendmentor.io/profile/TK-LS97)


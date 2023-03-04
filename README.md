# Frontend Mentor - Order summary card solution

This is a solution to the [Order summary card challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/order-summary-component-QlPmajDUj). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

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


## Overview

### The challenge

Users should be able to:

- See hover states for interactive elements

### Screenshot

![](./screenshot-mobile.png)
![](./screenshot-desktop.png)

### Links

- Solution URL: [My Solution](shashikantdev3/FrontendMentor-order-summary-component-main)
- Live Site URL: [Live Preview](https://shashikantdev3.github.io/FrontendMentor-order-summary-component-main/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow

### What I learned

I have implemented the box shadow effect.

For code snippets, see below:

```html
  <div class="button">
      <button type="button" class="order__payment-button">Proceed to Payment</button>
      <button type="button" class="order__cancel-button">Cancel Order</button>
     </div>
```
```css
.order__payment-button{
  border: none;
  text-decoration: none;
  text-align: center;
  padding: 0.5rem;
  border-radius: 0.5rem;
  color: var(--clr-white);
  background-color: var(--clr-bright-blue);
  font-weight: bold;
  box-shadow: 0 5px 15px var(--clr-bright-blue);
}

```

## Author

- Website - [Add your name here](https://www.your-site.com)
- Frontend Mentor - [@yourusername](https://www.frontendmentor.io/profile/yourusername)
- Twitter - [@yourusername](https://www.twitter.com/yourusername)


# Frontend Mentor - E-commerce product page solution

This is a solution to the [E-commerce product page challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/ecommerce-product-page-UPsZ9MJp6).

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
-

## Overview

### The challenge

Users should be able to:

- A responsive E-commerce web page that works on all devices despite their height and width.
- Hove state for all interactive elements on the pages.
- A lightbox gallery will be open when the user will click on the product image.
- Users can switch images by clicking thumbnail images.
- When the user click (+), and add to the cart, items will be added to the cart.
- User can also see the cart by just clicking the cart item or hovering over the cart, moreover, the user can also delete
  items from the cart by just clicking the delete icon inside the cart.

### Screenshot

![](/screenshot.png)

### Links

- Code: [GitHub](https://github.com/Naveed89-tech/E-CommercePage)
- Live Site URL: [ecommerceshosestore](https://ecommerceshosestore.netlify.app/#)
- Portfolio_Website: [Portfolio_Website](https://naveedtechs.netlify.app/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Javascript

### What I learned

During developing this E-commerce page, I face many challenges like how I will overlay the background, different navigation for different screen sizes like if a user is seeing the page on a desktop or laptop, different navigation style will be projected. Moreover, when users see the same page on their mobile device, a different experience will face. How to add items into the cart, remove items from the cart, remove the cart from the screen by just click outside the cart, these were all difficulties I face. But I have learned so many new things.

```css
.img-container {
  position: absolute;
  background-color: transparent;
  box-shadow: 0 0.6rem 0.7rem 0.3rem rgba(0, 0, 0, 0.3);
  margin: 0 auto;
  width: 45rem;
  height: 50rem;
  top: 18%;
  left: 52%;
  transform: translate(-52%);
  z-index: 1;
  opacity: 1;
  border-radius: 2rem;
  opacity: 1;
}
```

```js
window.addEventListener("click", function (e) {
  const click = e.target.closest(".cart-container");
  const cartBtn = e.target.closest(".cart--show");
  const subScript = e.target.closest(".cartContainer");

  if (click || cartBtn) {
    false;
  } else {
    filled.classList.remove("showCart");
    empty.classList.remove("showCart");
  }
});
```

### Continued development

I will more focus on the javascript and CSS parts. In CSS animation and responsiveness(media queries). Javascript for clean and concise code.

### Useful resources

- (https://css-tricks.com/) - This helped me for css part.
- (https://github.com/jonasschmedtmann) - His course of javascript help me lot to better understanding of
  DOM in javascript.

## Author

- Twitter - [@Naveed_Tech_T](https://twitter.com/Naveed_Tech_T)
- Linkedin - [@muhammad-naveed](https://www.linkedin.com/in/muhammad-naveed-857600231/)
- Website - [Naveed](https://naveedtechs.netlify.app/)

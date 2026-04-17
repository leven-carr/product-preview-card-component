# Frontend Mentor - Product preview card component solution

This is a solution to the [Product preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/product-preview-card-component-GO7UmttRfa). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

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

- View the optimal layout depending on their device's screen size
- See hover and focus states for interactive elements

### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)
- Live Site URL: [Add live site URL here](https://your-live-site-url.com)

## My process

Set up steps: Create styles.css, link it in the head of the html, link the font in the head as well. Move the provided styles to styles.css and delete the style tag. Write the custom variables and the universal reset in styles.css.

Working on the HTML: Create a main element to hold the content, and give it the flex-container class in order to position the card. Create an article element for the card and give it the flex-container class. The article.card has two direct children: the image, and a div which is a flex-container to hold the rest of the elements. These include a paragraph, h1, another paragraph, a div to contain the prices, and lastly, outside the prices div, the add to cart button.

Styling: Set overall styles for the body, set the broad flex-container rules, and set styles for the card. Then work down the card, styling elements from top to bottom. I did the media queries last, and had a bit of trouble figuring out how to make it work. My mobile design breaks at 632px and I was overcomplication how to make the image grow properly with the card, because of how I had set the max-width of the card. I finally realized I need to change the card's max-width to stop using calc() for it at that breakpoint; once I did that it became much simpler to adapt the design.

### Built with

HTML and CSS (including flexbox); no CSS frameworks or JS

### What I learned

This challenge was a learning experience for me building from a mobile-first perspective. I also learned how to use aspect-ratio, object-fit, and object-position for images, and I learned the letter-spacing property.

### Continued development

In the future I want to continue working on designing from a mobile-first perspective. This was the first time I had really tried to do that and I struggled with overcomplicating my media queries.

### Useful resources

- [Responsive images](https://web.dev/learn/design/responsive-images) - This web.dev article was very helpful for learning how to use properties such as aspect-ratio, object-fit, and object-position to position the product image correctly.

## Author

- Frontend Mentor - [@leven-carr](https://www.frontendmentor.io/profile/leven-carr)
- GitHub - [@leven-carr](https://github.com/leven-carr)

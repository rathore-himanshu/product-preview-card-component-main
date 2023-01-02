# Frontend Mentor - Product preview card component

![Design preview for the Product preview card component coding challenge](./design/desktop-preview.jpg)

## Welcome! 👋

# Frontend Mentor - Product preview card component solution

This is a solution to the [Product preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/product-preview-card-component-GO7UmttRfa). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Table of contents

-   [Overview](#overview)
    -   [The challenge](#the-challenge)
    -   [Screenshots](#screenshots)
    -   [Links](#links)
-   [My process](#my-process)
    -   [Built with](#built-with)
    -   [What I learned](#what-i-learned)
-   [Author](#author)
-   [Acknowledgments](#acknowledgments)

## Overview

### The challenge

Users should be able to:

-   View the optimal layout depending on their device's screen size
-   See hover and focus states for interactive elements

### Screenshots

![](./screenshots/mobile-screenshot.png)
![](./screenshots/desktop-screenshot.png)

### Links

-   Solution URL: [solution url](https://www.frontendmentor.io/solutions/product-preview-card-component-CPnSm5vZN7)
-   Live Site URL: [live site URL](https://himanshu-frontend-mentor-challenge-1.netlify.app/)

## My process

### Built with

-   Semantic HTML5 markup
-   CSS custom properties
-   Flexbox
-   CSS Grid
-   Mobile-first workflow

### What I learned

I learned how we can use responsiveness on images using srcset ans sizes attributes.

```html
<picture class="product_img">
    <source
        srcset="images/image-product-desktop.jpg"
        media="(min-width: 600px)"
    />
    <img src="images/image-product-mobile.jpg" alt="Perfume image" />
</picture>
```

If you want learn more about it, I'd recommend checking out [Responsive Images - MDN Web Docs](https://developer.mozilla.org/en-US/docs/Learn/HTML/Multimedia_and_embedding/Responsive_images) to learn more.

## Author

-   Frontend Mentor - [@rathore-himanshu](https://www.frontendmentor.io/profile/rathore-himanshu)
-   Twitter - [@\_tashurathore](https://www.twitter.com/@_tashurathore)

## Acknowledgments

[Kevin Powell](https://www.youtube.com/watch?v=B2WL6KkqhLQ&t=2000s)

**Have fun building!** 🚀

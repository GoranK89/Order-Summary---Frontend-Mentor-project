# Frontend Mentor - Order summary card solution

This is a solution to the [Order summary card challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/order-summary-component-QlPmajDUj). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

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
- [Acknowledgments](#acknowledgments)


## Overview

### The challenge

Users should be able to:

- See hover states for interactive elements

### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)
- Live Site URL: [Add live site URL here](https://your-live-site-url.com)

## My process

### Built with

- Semantic HTML5 markup
- CSS
- Flexbox

### What I learned

This project was smoother to do compared to the NFT one. In this project I got more familiar with:
- combining background images with a regular color background
- more much nedeed flexbox experience
- dividing html properly for a smoother css styling
- experimenting with hover effects and shadows


```html
<h1>Some HTML code I'm proud of</h1>

A simple solution to align the two middle paragraphs easily in the CSS styling later

<section id="pricing" role="region">
  <img src="images/icon-music.svg" alt="music symbol">
  <div id="AnnualPlanContainer">
    <p><b>Annual Plan</b></p>
    <p id="price">$59.99/year</p>
  </div>
  <a href="#"><b>Change</b></a>
</section>

```
```css
#AnnualPlanContainer {   
    display: flex;
    flex-direction: column; /* puts Annual Plan and $59.99/year in a column */
    gap: 5px;
    margin: 0 50px 0 0; /* adjusted the container to move a bit left */
}
```


### Continued development

At the current point I feel like I'm abusing the ID tags too much, for larger projects it will become an issue. CSS organising needs work, like grouping together selectors that use identical declarations. 
All in all these small practice projects were fun and already a big learning experience, looking forward to the next ones!


### Useful resources

- [W3 scools](https://www.w3schools.com/) - It is still my go to, excellent resources.
- [CSS-tricks](https://css-tricks.com/snippets/css/a-guide-to-flexbox/) - The graphics are just amazing for visualising the box model.
- [Box Shadow CSS Generator](https://html-css-js.com/css/generator/box-shadow/) - Was quite practical to see how shadows respond in CSS.


## Acknowledgments

Frontend Mentor is an amazing for developing skills!

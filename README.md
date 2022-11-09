# Product-Summary-Page
 A simple product summery page built with HTML and CSS

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

- View the optimal layout depending on their device's screen size
- See hover states for interactive elements

## My process
I began by looking at examples of this site to design it as accurately as I could. 
Seeing as the HTML was already provided, I began styling the site from the most general selectors to the most specific.
I then began working on the aspects of this challenge focusing on concepts I was not familiar with.

### Built with

- Semantic HTML5 markup
- CSS custom properties

### What I learned

```html
<!--adding external fonts from google-->
  <link rel="preconnect" href="https://fonts.googleapis.com">
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
  <link href="https://fonts.googleapis.com/css2?family=Fraunces:opsz@9..144&family=Montserrat&display=swap" rel="stylesheet">

<!--adding icon to a button-->
<button type="button"><img src="..\frontend mentor\product-preview-card-component-main\images\icon-cart.svg"> Add to Cart</button>
```
```css
/*adding breakpoints according to devices*/

    @media only screen
      and (max-width: 375px){
        #product{
          width: 100vw;
        }
      }
```

### Continued development

I definitely plan on learning more about media queries as this project was essentially my first exposure to them and the topic of breakpoints. I also want to learn to get more comfortable using pseudoslectors and learning more about semantic HTML.


### Useful resources

- [WW3](https://www.w3schools.com/css/css_font_google.asp) - This helped me with learning how to add external google fonts to my site. 
- [LambdaTest](https://www.lambdatest.com/blog/css-media-queries-for-responsive-design/) - This article helped me understand media queries and breakpoints. I'd recommend it to anyone still learning this concept.

## Author

- Github - [Mahlako Mogoane](https://www.your-site.com)
- Frontend Mentor - [@yourusername](https://www.frontendmentor.io/profile/yourusername)

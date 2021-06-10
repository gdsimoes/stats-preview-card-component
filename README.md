# Frontend Mentor - Stats preview card component solution

This is a solution to the [Stats preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/stats-preview-card-component-8JqbgoU62). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Table of contents

-   [Overview](#overview)
    -   [The challenge](#the-challenge)
    -   [Screenshot](#screenshot)
    -   [Links](#links)
-   [My process](#my-process)
    -   [Built with](#built-with)
    -   [What I learned](#what-i-learned)
    -   [Continued development](#continued-development)
    -   [Useful resources](#useful-resources)
-   [Author](#author)
-   [Acknowledgments](#acknowledgments)

## Overview

### The challenge

Users should be able to:

-   View the optimal layout depending on their device's screen size

### Screenshot

![Screenshot of the website on desktop](./screenshot.png)

### Links

-   Solution URL: <https://github.com/gdsimoes/stats-preview-card-component>
-   Live Site URL: <https://gdsimoes.github.io/stats-preview-card-component>

## My process

### Built with

-   Semantic HTML5 markup
-   CSS custom properties
-   Media Queries
-   Flexbox
-   Mobile-first workflow

### What I learned

This project allowed me to apply my knowledge of semantic HTML and how to create responsive web pages. Furthermore, while building it, I improved my flexbox skills, and I am delighted with the results.

But I also learned some new things in this project. The main one was how to apply the multiply blend mode to images (creating the nice pink effect we can see on the screenshot):

```css
img {
    mix-blend-mode: multiply;
}
```

Another technique that I will surely use in other projects is how to avoid the background color obscuring the rounded corners. To do that, we need to avoid the inner content overflow:

```css
main {
    overflow: hidden;
}
```

### Continued development

I am confident in my ability to create responsive web pages using flexbox, and in my next project, I plan to take my CSS Grid skills to the same level.

### Useful resources

-   [MDN - mix-blend-mode](https://developer.mozilla.org/en-US/docs/Web/CSS/mix-blend-mode) - MDN, as usual, was the best place to learn about a particular property.
-   [Stack Overflow - border-radius + background-color == cropped border](https://stackoverflow.com/questions/6312067/border-radius-background-color-cropped-border) - When CSS throws you a curveball, Stack Overflow is the right place to go for help, and it wasn't different in this case.

## Author

-   Website - <https://gdsimoes.com>
-   Frontend Mentor - [@gdsimoes](https://www.frontendmentor.io/profile/gdsimoes)
-   LinkedIn - [Guilherme Dias Simoes](https://www.linkedin.com/in/gdsimoes)

## Acknowledgments

I would like to thank [Rodrigo Barbosa](https://github.com/Rod-Barbosa) for inspiring me to start working on Frontend Mentor challenges and telling me about the multiply blend mode. I was lost trying to change the design images, and I'm glad he pointed me in the right direction.

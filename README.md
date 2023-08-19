# Stats preview card component solution

This is a solution to the [Stats preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/stats-preview-card-component-8JqbgoU62).

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

- View the optimal layout depending on their device's screen size

### Screenshot

![Project preview](design/project-preview.png)

### Links

- [Solution on frontendmentor.io](https://www.frontendmentor.io/solutions/stats-preview-card-component-dhAaDssNNB)
- [Live preview](https://piwkoo.github.io/stats-preview-card-component/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Mobile-first workflow
- BEM methodology

### What I learned

I learned how to connect image with background color to create overlay on this image without the necessity of using pseudo-elements.

To see how you can add code snippets, see below:

```css
.card__img {
  background: url(images/image-header-mobile.jpg), var(--accent);
  background-blend-mode: multiply;
}
```

### Continued development

As always I want to sharpen my skills by creating a lot of different project. It doesn't matter how small it is because every single line of code can help in the future. Especially when we work with libraries or frameworks like React, Vue or Angular and create single components like in this project which we can later reuse.

### Useful resources

- [Mozilla developer](https://developer.mozilla.org/en-US/docs/Web/CSS/background-blend-mode) - As always mozilla documentation is really handy when it comes to web development. This time it helped me better understand how I can manipulate background using blend-mode. 

## Author

- Github - [@PiwkoO](https://github.com/PiwkoO)
- Frontend Mentor - [@PiwkoO](https://www.frontendmentor.io/profile/PiwkoO)

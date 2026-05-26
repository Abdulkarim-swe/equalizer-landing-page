# Frontend Mentor - Equalizer landing page solution

This is a solution to the [Equalizer landing page challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/equalizer-landing-page-7VJ4gp3DE). 

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
- [Author](#author)

## Overview

### The challenge

Users should be able to:
- View the optimal layout depending on their device's screen size
- See hover states for interactive elements

### Links

- Solution URL: [GitHub Repository](https://github.com/abdulkarim-swe/equalizer-landing-page)
- Live Site URL: [Live Website](https://abdulkarim-swe.github.io/equalizer-landing-page/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties (Variables)
- Flexbox
- Desktop-first workflow

### What I learned

This was a major milestone for me as it was my first time translating a professional Figma design file into a fully responsive webpage. The biggest engineering lesson I learned during this project was avoiding "The Fixed Size Trap." 

Initially, I relied heavily on fixed `width` and `height` for my containers to match the design perfectly:

```css
/* Old approach */
.container {
  width: 500px;
  height: 300px;
}
```

However, I realized this breaks the responsive nature of the web. I refactored my approach to let the content dictate the size, utilizing `max-width` and trusting Flexbox to handle the layout naturally.

### Continued development

In future projects, I plan to continue refining my CSS architecture. My goal is to write more modular code, reduce repetition (DRY principle), and eventually transition into using CSS preprocessors like Sass or utility-first frameworks like Tailwind CSS once my vanilla CSS foundation is unbreakable.

## Author

- **Abdulkarim**
- Role: Software Engineering & Student
- GitHub - [@abdulkarim-swe](https://github.com/abdulkarim-swe)
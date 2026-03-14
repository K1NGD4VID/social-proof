# Frontend Mentor - Social proof section solution

This is a solution to the [Social proof section challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/social-proof-section-6e0qTv_bA). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

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
  - [AI Collaboration](#ai-collaboration)
- [Author](#author)

## Overview

### The challenge

Users should be able to:

- View the optimal layout for the section depending on their device's screen size

### Screenshot

![Social proof section screenshot](https://i.postimg.cc/26DYgccp/social-proof-screenshot.png)

### Links

- Solution URL: [GitHub Repository](https://github.com/Fuhad015/social-proof)
- Live Site URL: [Live Site](https://social-proof-three-sage.vercel.app/)
- image gallery: [Gallery](https://postimg.cc/gallery/JnyqCdd)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow
- Vanilla CSS

### What I learned

I reinforced my skills in building responsive layouts using CSS Grid and Flexbox with CSS. I also practiced implementing a staggered layout for both the rating boxes and the testimonial cards using margin offsets and transforms on larger screens.

```css
/* Example of staggered layout using CSS */
@media (min-width: 1024px) {
  .rating-1 {
    align-self: flex-start;
  }
  .rating-2 {
    align-self: center;
  }
  .rating-3 {
    align-self: flex-end;
  }

  .card-1 {
    transform: translateY(0);
  }
  .card-2 {
    transform: translateY(16px);
  }
  .card-3 {
    transform: translateY(32px);
  }
}
```

### Useful resources

- [MDN Web Docs - CSS](https://developer.mozilla.org/en-US/docs/Web/CSS) - The official documentation is always my go-to resource for finding the right CSS properties.
- [Google Fonts](https://fonts.google.com/) - Used for the League Spartan font.

### AI Collaboration

- **Tools used:** Google AI Studio (Gemini 3.1 Pro), Front-end Mentor
- **How it was used:** I used the AI to help write the vanilla CSS with the custom color palette, and generate the staggered layout logic.

I used front-mentor solution improvemen to improve my code

## Author

- Adesanya Fuhad

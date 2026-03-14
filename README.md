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

_(Screenshot would be placed here)_

### Links

- Solution URL: [GitHub Repository](https://github.com)
- Live Site URL: [Live Site](https://your-live-site-url.com)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow
- Pure Vanilla CSS (No frameworks)

### What I learned

I reinforced my skills in building responsive layouts using CSS Grid and Flexbox with pure CSS. I also practiced implementing a staggered layout for both the rating boxes and the testimonial cards using margin offsets and transforms on larger screens.

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

### Continued development

I want to continue focusing on writing clean, maintainable CSS architectures and mastering advanced CSS features, such as custom properties and complex responsive designs without relying on frameworks.

### Useful resources

- [MDN Web Docs - CSS](https://developer.mozilla.org/en-US/docs/Web/CSS) - The official documentation is always my go-to resource for finding the right CSS properties.
- [Google Fonts](https://fonts.google.com/) - Used for the League Spartan font.

### AI Collaboration

- **Tools used:** Google AI Studio (Gemini 3.1 Pro)
- **How it was used:** I used the AI to help scaffold the HTML structure and write the vanilla CSS with the custom color palette, and generate the staggered layout logic. The AI also assisted in writing this README file.
- **What worked well:** The AI was excellent at quickly translating the design requirements (colors, typography, layout) into functional HTML and CSS code.

## Author

- Frontend Mentor - [@yourusername](https://www.frontendmentor.io/profile/yourusername)

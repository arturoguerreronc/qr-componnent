# Frontend Mentor - QR code component solution

This is a solution to the [QR code component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/qr-code-component-iux_sIO_H). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Table of contents

  - [Overview](#overview)
    - [Screenshot](#screenshot)
    - [Links](#links)
  - [My process](#my-process)
    - [Built with](#built-with)
    - [What I learned](#what-i-learned)
    - [Continued development](#continued-development)
    - [Useful resources](#useful-resources)
  - [Author](#author)
  - [Acknowledgments](#acknowledgments)

## Overview

### Screenshot

![QR component main](./images/image-qr-component.png)

### Links

- Solution URL:
- Live Site URL: [Github Pages](https://arturoguerrero.me/qr-component/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Mobile-first workflow

### What I learned

I learned how to create a fully responsive card component that works seamlessly across mobile and desktop devices. I focused on using flexible units like percentages and `max-width` to ensure the layout adapts to any screen size. Additionally, I improved the accessibility of the project by adding descriptive `alt` text to the QR code image.

```html
<div class="image-container">
  <img src="images/image-qr-code.png" alt="QR code to visit Frontend Mentor" />
</div>
```

```css
.card {
  width: 100%;
  max-width: 320px;
  /* ... */
}

.image-container {
  width: 100%;
  aspect-ratio: 1;
  /* ... */
}
```

### Continued development

I want to continue focusing on responsive design and learning more about CSS Grid for more complex layouts.

### Useful resources

- [Frontend Mentor](https://www.frontendmentor.io) - This platform helped me practice my skills with realistic projects.
- [MDN Web Docs](https://developer.mozilla.org/en-US/) - This is an amazing reference for HTML and CSS concepts.
- [A Complete Guide to Flexbox](https://css-tricks.com/snippets/css/a-guide-to-flexbox/) - This article helped me understand how to use Flexbox for centering the component.
- [Web Content Accessibility Guidelines (WCAG)](https://www.w3.org/WAI/standards-guidelines/wcag/) - Essential for ensuring the project is accessible to all users.
- [Google Fonts](https://fonts.google.com/Outfit) - Used for the 'Outfit' font family in this project.

## Author

- Website - [Arturo Guerrero](https://github.com/arturoguerreronc)
- Frontend Mentor - [@arturoguerreronc](https://www.frontendmentor.io/profile/arturoguerreronc)

## Acknowledgments

Thanks to Frontend Mentor for providing this challenge.

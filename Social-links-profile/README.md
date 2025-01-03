# Social links profile

This is my solution to the [Social links profile challenge](https://www.frontendmentor.io/challenges/social-links-profile-UG32l9m6dQ) on Frontend Mentor. The challenge helped me practice responsive design, semantic HTML, and CSS techniques.

![Frontend Mentor](https://img.shields.io/badge/FrontendMentor-Challenge-blue) ![Custom Badge](https://img.shields.io/badge/Level-Newbie-blue) [![Netlify Status](https://api.netlify.com/api/v1/badges/64e3749d-5ee9-46e4-a1c4-e66d42975fd3/deploy-status)](https://app.netlify.com/sites/astro-qr-component/deploys) ![Astro](https://img.shields.io/badge/Astro-v5.0.3-blue?logo=astro&logoColor=white) ![Node.js](https://img.shields.io/badge/Node.js-v20.17.0-green?logo=node.js&logoColor=white)

## Table of Contents

- [Overview](#overview)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [Process](#process)
  - [Built With](#built-with)
  - [Challenges and Solutions](#challenges-and-solutions)
  - [Retrospective](#retrospective)
- [Resources](#resources)
- [Author](#author)

---

## Overview

### Screenshot

![Social links profile](../Social-links-profile/src/assets/images/preview.jpg)

### Links

- [Solution URL](https://github.com/JoelBuenrostro/FM-Web-Examples/tree/main/QR-Component)
- [Live Demo](https://astro-qr-component.netlify.app)

---

## Process

### Built With

- **Semantic HTML5:** Proper use of elements like `<main>`, `<section>`, `<h1>`, and `<p>` to ensure accessibility and semantic correctness.
- **CSS Flexbox:** For creating a flexible layout that adapts to different screen sizes.
- **Responsive Design:** Implemented with relative units (`rem`, `%`) and media queries for optimal viewing on devices ranging from 320px to large screens.
- **Google Fonts:** Integrated the "Outfit" font family with weights 400 and 700.
- **Astro Framework:** Used for component structure and easy project management.

### Challenges and Solutions

1. **Ensuring Responsiveness:**
   Fixed layout dimensions caused issues on smaller screens. I resolved this by using relative units like `%` and `rem` and incorporating `media queries` to adjust styles for various breakpoints.

2. **Maintaining Accessibility:**
   Added descriptive `alt` attributes for images and used `aria-labelledby` in the `<section>` to associate it with its title, enhancing screen reader navigation.

3. **Footer Placement:**
   Ensured the footer stays at the bottom of the page using `flexbox` for the layout, allowing the main content to occupy available space without affecting the footer's position.

4. **Height Consistency:**
   Maintained a fixed height of 497px for the QR card on large screens, with responsive adjustments for smaller devices using `max-height` and media queries.

### Retrospective

I am proud of creating a fully responsive and accessible design. If I were to redo this project, I would explore adding subtle animations for a more dynamic user experience and potentially refactor the styles using a CSS preprocessor like SASS for better scalability.

---

## Resources

- [Frontend Mentor Style Guide](./QR-Component/style-guide.md) - Guidelines for typography and color palette.
- [MDN Web Docs](https://developer.mozilla.org/) - For understanding HTML and CSS best practices.
- [Google Fonts](https://fonts.google.com/specimen/Outfit) - "Outfit" font integration.

---

## Author

- Frontend Mentor - [@JoelBuenrostro](https://www.frontendmentor.io/profile/JoelBuenrostro)
- GitHub - [JoelBuenrostro](https://github.com/JoelBuenrostro)
- Instagram - [@joel_buenrostro](https://www.instagram.com/joel_buenrostro/)

Feel free to share feedback or suggestions for improvement. Happy coding!

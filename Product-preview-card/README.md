# Product preview card

## Table of contents

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

![Product preview card preview](../Product-preview-card/public/assets/desktop-preview.jpg)

![Product preview card active states](../Product-preview-card/public/assets/active-states.jpg)

### Links

- [Solution URL](https://github.com/JoelBuenrostro/FM-Web-Examples/tree/main/Product-preview-card)
- [Live Demo](https://product-preview-card-sample.netlify.app/)

---

## Process

### Built With

- Astro
- HTML5
- CSS3
- Mobile-first, responsive design
- Semantic HTML

### Challenges and Solutions

- Build errors with Astro: incompatible Node versions or missing dependencies. Fix: use a recommended Node version (for example Node 18+), remove `node_modules` and reinstall, and verify `package.json`.
- Broken asset paths in production: images or fonts missing after build. Fix: place static files under `public/`, use correct relative paths or `new URL('./path', import.meta.url)` in Astro, and check the `base` option if applicable.
- Responsiveness issues at certain sizes: elements overflow or shift. Fix: review breakpoints (`@media`), test with devtools across devices, and use fluid units (`rem`, `%`, `min()`/`clamp()`).

### Retrospective

- What went well: implemented a responsive, semantic product preview card using Astro and modern CSS; layout and styles match the design closely.
- What could be improved: optimize image formats and font loading, enhance accessibility details (ARIA attributes, keyboard support), and reduce CSS specificity where possible.
- Next steps: add a CI build check, implement image optimization (WebP/AVIF + srcset), and run accessibility audits with Lighthouse or Axe.

## Resources

- [Frontend Mentor Style Guide](./style-guide.md) - Guidelines for typography and color palette.
- [MDN Web Docs](https://developer.mozilla.org/) - For understanding HTML and CSS best practices.
- [Astro Docs](https://docs.astro.build/en/getting-started/)

---

## Author

- Frontend Mentor - [@JoelBuenrostro](https://www.frontendmentor.io/profile/JoelBuenrostro)
- GitHub - [JoelBuenrostro](https://github.com/JoelBuenrostro)
- Instagram - [@joel_buenrostro](https://www.instagram.com/joel_buenrostro/)

Feel free to share feedback or suggestions for improvement. Happy coding!

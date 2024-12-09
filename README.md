# Frontend Mentor - QR Code Component Solution

This is my solution for the [QR code component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/qr-code-component-iux_sIO_H). This was a great opportunity for polishing my front-end development skills while focusing on clean code and accessibility.

![Project Screenshot](./preview.jpg)

### Links

- Solution URL: [Frontend Mentor Solution](https://github.com/uixcem/frontendmentor-qr)
- Live Site URL: [Live Project](https://qrcodesolutionfronetendmentor.netlify.app/)

## My Process

### Built With

- Semantic HTML5 markup
- CSS custom properties
- CSS Flexbox & Grid
- BEM Methodology
- Mobile-first workflow
- Focus on accessibility

### What I Learned

While this was a relatively simple project, it was a great opportunity to reinforce best practices and focus on writing clean, maintainable code. Here are some key aspects I implemented:

```html
<!-- Semantic HTML structure -->
<main class="container">
  <article class="card" role="article">
    <div class="card__image">
      <img
        src="./images/qr-code.png"
        alt="QR code to Frontend Mentor website"
      />
    </div>
  </article>
</main>
```

```css
/* CSS Variables for maintainability */
:root {
  --bg-color: #d5e1ef;
  --card-color: #fff;
  --text-color: #333;
  --border-radius: 2rem;
}

/* Responsive design approach */
.card {
  max-width: 32rem;
  width: 100%;
}
```

### Useful Resources

- [CSS Grid Guide](https://css-tricks.com/snippets/css/complete-guide-grid/) - An excellent reference for CSS Grid.
- [BEM Methodology](https://getbem.com/) - Helped me maintain a clear and consistent naming convention.
- [A11Y Project](https://www.a11yproject.com/) - Great resource for accessibility best practices.

## Author

- Website - [Cem Kaplan](https://www.cemkaplan.me)
- Frontend Mentor - [@uixcem](https://www.frontendmentor.io/profile/uixcem)
- Twitter - [@uixcem](https://www.twitter.com/uixcem)

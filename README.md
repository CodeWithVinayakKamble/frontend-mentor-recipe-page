# Frontend Mentor - Recipe Page

## Built With

- Semantic HTML5 (`<article>`, `<section>`, `<aside>`)
- Vanilla CSS
- CSS Custom Properties (Variables)
- Strict BEM Naming Convention (e.g., `recipe-page__img-wrapper`)
- Flexbox (Used for vertical rhythm and centering)
- Mobile-First Workflow
- `clamp()` for fluid typography
- Desktop View Adjusment Done By `Media Query`
- Advanced CSS Pseudo-selectors (`::marker`, `:last-child`)

## What I Learned

- **Fluid Typography with `clamp()`:** How to make font sizes scale seamlessly between mobile and desktop using
  `clamp()`, eliminating the need for excessive typography media queries.

- **The "Padding Swap" Technique:** How to structure an HTML wrapper to keep images touching the screen edge on mobile, and using a media query to transfer that padding to the outer container to "push" the image inward on desktop screens.
- **Modern List Styling:** Using the modern `::marker` pseudo-element to apply custom colors and font weights strictly to list bullet points and numbers, without affecting the paragraph text.

- **Vertical Rhythm:** Using Flexbox and the `gap` property on the main container to evenly space out major layout sections (Title, Callouts, Ingredients, etc.) instead of relying on repetitive margins.

- **Overriding Browser Defaults:** Learning how the browser's "User Agent Stylesheet" applies hidden defaults (like `font-weight: 700` to `<th>` elements) and how to manually override them for a pixel-perfect design.

## Author

- Challenge by Frontend Mentor
- Coded by **Vinayak Kamble**

# Carla Quartieri – Portfolio

A minimal portfolio website showcasing my posters and graphics made in Photoshop, created for fun in my spare time.

A single page built with plain HTML, CSS and JavaScript: no frameworks and no dependencies to install.

## Features

- **Light/dark mode**, which follows the system theme and remembers the visitor's choice
- **Two languages** (Italian/English) with an animated transition between texts
- **Gallery of 10 works**: 3 visible at first and 7 behind a "Show more" button
- **Responsive**: designed for desktop, tablet and mobile
- **Accessibility**: color palette with checked contrast ratios and designed with color-blind users in mind, visible keyboard focus, support for the "reduce motion" preference
- Links to my Ko-fi shop and contacts

## Project structure

```
.
├── index.html      # the page (HTML, CSS and JS in a single file)
├── favicon.png     # browser tab icon
├── images/         # profile photo and artwork images
└── README.md
```

> To publish on GitHub Pages, the main file must be named `index.html`.

## Run locally

Nothing to install: just open `index.html` in a browser.

## Deploy with GitHub Pages

1. Upload the files to a GitHub repository.
2. Go to **Settings → Pages**.
3. Under **Source**, choose the `main` branch and the `/ (root)` folder.
4. After a few minutes the site will be live at `https://<username>.github.io/<repository-name>/`.

## Customization

- **Colors**: CSS variables in `:root` (light theme) and `:root[data-theme="dark"]` (dark theme), at the top of the file.
- **Bilingual text**: the `testi` object in the script, with `it` and `en` keys. Every translatable element has a `data-i18n` attribute matching a key.
- **Works**: each work is a `<div class="lavoro">` block with an image, a title and a category. Images use a vertical A4 ratio (210×297).
- **Photo and logo**: photo in `images/`, circular initials logo in the navbar.

## Notes

- Some artwork images are hosted on Ko-fi: if they are removed from there, they disappear from the site. For safety, they can be downloaded into the `images/` folder.
- Font: [DM Sans](https://fonts.google.com/specimen/DM+Sans) from Google Fonts.

## License

The posters and graphics are works by Carla Quartieri, all rights reserved. The artworks depict characters and universes owned by their respective rights holders. The page code may be reused as a starting point for your own portfolio.

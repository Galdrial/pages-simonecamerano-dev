# Simone Camerano Personal Website

This repository contains the personal website of Simone Camerano, Full Stack Developer. The site is published via GitHub Pages and includes both Italian and English versions.

## Project Structure

- `index.html` — Italian home page
- `about_page/`, `contact_page/`, `cv_page/`, `projects_page/` — Main pages in Italian
- `en/` — Folder with English versions of the pages
- `assets/` — Static resources (CSS, SCSS, images, files)
  - `css/` — Compiled stylesheets
  - `sass/` — Custom SCSS sources and Bootstrap
  - `img/` — Images and favicon
  - `files/` — Downloadable files (e.g. CV)
- Bootstrap 5 customized via SCSS
- Contact form with EmailJS integration

## Main Features

- Responsive navigation with multilingual menu
- CSS-only visual effects and JS animations for button feedback
- Improved accessibility (aria-label, rel, target)
- Contact form with email sending via EmailJS
- English version accessible from every page

## How to Publish on GitHub Pages

1. Make sure all files are in the root of the `master` branch.
2. Go to GitHub > Settings > Pages and select the root of the `master` branch.
3. The public URL will be: `https://galdrial.github.io/pages-simonecamerano-dev/`

## How to Compile Styles

1. Edit SCSS files in `assets/sass/`
2. Compile to CSS using a tool like `sass` or VS Code Live Sass Compiler
3. Generated CSS goes in `assets/css/`

## Best Practices Followed

- External links use `rel="noopener noreferrer"` and `target="_blank"`
- Descriptive `aria-label` attributes for navigation
- Semantic and responsive HTML structure
- Clear comments and clean code

## Author

Simone Camerano — [LinkedIn](https://www.linkedin.com/in/simone-camerano-474363212/) — [GitHub](https://github.com/Galdrial)

## License

This project is distributed under the MIT license.

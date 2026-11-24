# Gallery

A responsive image gallery page with a header, category sidebar, image grid, and footer. Built with plain HTML and CSS, and hosted on GitHub Pages.

**Live demo:** https://assemkaram.github.io/Gallery/

## Features

- Responsive layout that adapts from desktop to phone
- Header with logo and navigation links
- Sidebar with a category list (moves above the gallery on small screens)
- Responsive image grid that fits as many columns as the screen allows
- Lazy-loaded images for faster loading on mobile
- Footer


## Project Structure

```
Gallery/
├── index.html      # Page structure and gallery images
├── style.css       # Layout, colors, and responsive rules
└── Gallery/        # <!-- Describe what this folder contains -->
```

## Getting Started

Clone the repository and open the page in a browser. No build step or installation is needed:

```bash
git clone https://github.com/assemkaram/Gallery.git
cd Gallery
open index.html        # macOS
# or: xdg-open index.html (Linux) / start index.html (Windows)
```

## Customization

- **Images:** Replace the `src` values in `index.html`. Add `alt` text that describes each image.
- **Categories:** Edit the list inside `<aside>` in `index.html`.
- **Colors:** Change the `rgb(...)` values in `style.css`. The header, footer, and sidebar use the main colors.
- **Image shape:** Change `aspect-ratio: 4 / 3` in `style.css` to `1 / 1` for squares or `16 / 9` for wide images.

## Responsive Breakpoints

| Screen width | Layout |
|---|---|
| Above 768px | Sidebar on the left, gallery on the right |
| 768px and below | Single column: header, categories, gallery, footer |
| 430px and below | Tighter spacing |

## Deployment

The site is served by GitHub Pages from the `main` branch. Pushes to `main` update https://assemkaram.github.io/Gallery/.

To enable Pages on a fork: **Settings → Pages → Deploy from a branch**, then select `main` and `/ (root)`.

## Contributing

1. Fork the repository.
2. Create a branch: `git checkout -b feature/your-feature`
3. Commit and push your changes.
4. Open a pull request.


## Author

[@assemkaram](https://github.com/assemkaram)

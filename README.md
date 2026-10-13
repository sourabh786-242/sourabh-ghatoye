# Saurabh Ghatoye Website

## Shared styling

The seven connected HTML pages load the shared root-level `style.css` file after the Tailwind CDN script. Tailwind configuration remains page-local; `style.css` contains the shared design tokens, browser defaults, glass surfaces, ambient backgrounds, mesh artwork, reveal and pre-loader motion, reduced-motion support, FAQ transitions, and the contact/insights page-specific effects.

Each page identifies its original visual variant on `<body>` with `data-page`:

| Page | `data-page` |
| --- | --- |
| `index.html` | `index` |
| `about.html` | `about` |
| `seo-services.html` | `seo` |
| `smm-services.html` | `smm` |
| `projects.html` | `portfolio` |
| `insights.html` | `insights` |
| `contact.html` | `contact` |

Keep these values when changing a page so its page-specific backgrounds and animation timing continue to match the existing design.
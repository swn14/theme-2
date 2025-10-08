# Theme 2 - Modern Astro Website Template

A clean, modern website template built with Astro and styled using Pico CSS. This is the second theme in a collection of pre-made templates designed for quick website development.

## Features

- **Clean & Modern Design**: Minimalist aesthetic with Pico CSS classless styling
- **Fully Responsive**: Mobile-first design that works on all devices
- **Fast Performance**: Built with Astro for optimal loading speeds
- **Accessible**: Semantic HTML with proper accessibility features
- **Easy Customization**: Well-organized component structure for quick modifications

## Styling with Pico CSS

This theme uses **Pico CSS v2** (classless version), which provides:

- **Zero Configuration**: No CSS classes needed - just write semantic HTML
- **Automatic Dark Mode**: Built-in dark/light theme switching
- **Accessibility First**: WCAG compliant with proper focus states and contrast
- **CSS Variables**: Easy theming with CSS custom properties
- **Small Footprint**: Lightweight framework (~10KB gzipped)
- **Modern Features**: CSS Grid, Flexbox, and modern CSS properties

Pico CSS automatically styles HTML elements, making it perfect for content-focused websites. The classless approach means you get beautiful styling without writing CSS classes.

## Project Structure

```text
/
├── public/
│   ├── favicon.svg
│   └── styles.css          # Custom styles (extends Pico CSS)
├── src/
│   ├── components/
│   │   ├── Footer.astro    # Site footer component
│   │   ├── MobileNav.astro # Mobile navigation
│   │   └── TopNav.astro    # Main navigation
│   ├── layouts/
│   │   ├── Home.astro      # Homepage layout
│   │   └── SinglePage.astro # Internal page layout
│   └── pages/
│       ├── index.astro     # Homepage
│       ├── about/
│       │   └── index.astro # About page
│       └── contact/
│           └── index.astro # Contact page
└── package.json
```

## Getting Started

1. **Clone or download** this theme

2. **Install dependencies**:

   ```sh
   npm install
   ```

3. **Start development server**:

   ```sh
   npm run dev
   ```

4. **Open your browser** to `http://localhost:4321`

## Commands

All commands are run from the root of the project, from a terminal:

| Command                   | Action                                           |
| :------------------------ | :----------------------------------------------- |
| `npm install`             | Installs dependencies                            |
| `npm run dev`             | Starts local dev server at `localhost:4321`      |
| `npm run build`           | Build your production site to `./dist/`          |
| `npm run preview`         | Preview your build locally, before deploying     |
| `npm run astro ...`       | Run CLI commands like `astro add`, `astro check` |
| `npm run astro -- --help` | Get help using the Astro CLI                     |

## Customization

### Colors & Theming

Pico CSS uses CSS custom properties for theming. You can override the default colors in `public/styles.css`:

```css
:root {
  --pico-primary: #your-brand-color;
  --pico-background-color: #your-bg-color;
}
```

### Adding Content

- Edit `src/pages/index.astro` to modify the homepage
- Add new pages in the `src/pages/` directory
- Customize components in `src/components/`
- Update layouts in `src/layouts/`

### Mobile Navigation

The theme includes a responsive mobile navigation component that automatically adapts to smaller screens.

## Learn More

- [Astro Documentation](https://docs.astro.build) - Learn about Astro features
- [Pico CSS Documentation](https://picocss.com) - Explore Pico CSS capabilities
- [Pico CSS GitHub](https://github.com/picocss/pico) - Source code and examples

## License

This theme is open source and available under the MIT License.

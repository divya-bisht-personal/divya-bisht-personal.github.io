# Divya Bisht - Portfolio Site

A minimal, modern single-page portfolio website built for GitHub Pages.

## Quick Start

### Local Development

1. Open `index.html` in your browser to view the site locally
2. Make edits to the HTML, CSS, or JS files
3. Refresh the browser to see changes

### Deploy to GitHub Pages

1. Create a new repository on GitHub (e.g., `divyabisht.github.io` for a user site, or `portfolio` for a project site)

2. Initialize git and push:
   ```bash
   git init
   git add .
   git commit -m "Initial commit"
   git branch -M main
   git remote add origin https://github.com/YOUR_USERNAME/YOUR_REPO.git
   git push -u origin main
   ```

3. Enable GitHub Pages:
   - Go to your repository on GitHub
   - Navigate to Settings > Pages
   - Under "Source", select "Deploy from a branch"
   - Select "main" branch and "/ (root)" folder
   - Click Save

4. Your site will be live at:
   - User site: `https://YOUR_USERNAME.github.io`
   - Project site: `https://YOUR_USERNAME.github.io/REPO_NAME`

## Customization

### Update Personal Information

Edit `index.html` to update:
- Social media links (GitHub, LinkedIn, Email)
- About section content
- CV/Experience timeline
- Portfolio projects

### Add Your CV

1. Place your CV PDF in the `assets/` folder
2. Name it `divya-bisht-cv.pdf` (or update the link in `index.html`)

### Modify Colors

Edit the CSS variables in `css/styles.css`:

```css
:root {
    --color-light-sage: #CCDCDB;
    --color-soft-mint: #A1D8B5;
    --color-fresh-green: #4CB572;
    --color-deep-teal: #135E4B;
}
```

## File Structure

```
portfolio-site/
├── index.html          # Main HTML structure
├── css/
│   └── styles.css      # All styles + animations
├── js/
│   └── main.js         # Smooth scroll + animations
├── assets/
│   └── (CV PDF, images)
└── README.md           # This file
```

## Features

- Responsive design (mobile-first)
- Smooth scroll navigation
- Fade-in animations on scroll
- Active navigation highlighting
- Clean, minimal aesthetic
- No build step required

## Browser Support

Works in all modern browsers:
- Chrome, Firefox, Safari, Edge (latest versions)
- Mobile browsers (iOS Safari, Chrome for Android)

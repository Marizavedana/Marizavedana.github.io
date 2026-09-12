# Portfolio Images

This folder is for storing images of your mosaic artwork.

## Organization Structure

Recommended folder structure for organizing your images:

```
images/
├── portfolio/
│   ├── geometric-harmony.jpg
│   ├── natures-palette.jpg
│   ├── abstract-waves.jpg
│   ├── cultural-fusion.jpg
│   ├── botanical-studies.jpg
│   └── luminescence.jpg
├── about/
│   └── artist-portrait.jpg
└── process/
    └── studio-shots/
```

## How to Add Your Images

1. **Upload images** to this folder via GitHub's web interface or Git command line
2. **Recommended formats**: JPG or PNG for best web performance
3. **Image size**: Aim for 800x600px or larger for good quality
4. **File naming**: Use descriptive, lowercase names with hyphens (e.g., `geometric-harmony.jpg`)

## Updating Your Portfolio

Once you've uploaded images, update the `index.html` file to replace the emoji placeholders:

**Before:**
```html
<div class="portfolio-image">🎨</div>
```

**After:**
```html
<img src="images/portfolio/geometric-harmony.jpg" alt="Geometric Harmony" class="portfolio-image">
```

You'll also need to update the CSS for the `.portfolio-image` class to display images properly instead of the gradient background.

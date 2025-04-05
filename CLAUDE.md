
# Guidelines for The Vayu Naturals Website

## Project Overview
- Static HTML website for essential oils and natural products
- Uses vanilla JavaScript, CSS, and HTML (based on "Herbalist" template)

## Development Commands
- No build system - static site served directly
- Preview: Open index.html in browser or use a local server tool like `python -m http.server`
- Validate HTML: https://validator.w3.org/
- Validate CSS: https://jigsaw.w3.org/css-validator/

## Code Style Guidelines
- **HTML**: Semantic tags, proper indentation, accessibility attributes
- **CSS**: BEM naming convention (block__element--modifier)
- **JavaScript**:
  - Modular approach (see js/modules directory)
  - ES6 syntax with named exports
  - Minify JS with suffix .min.js for production

## File Structure
- Category content in /category/ directory
- Images in /img/ directory
- Keep JS modules in /js/modules/
- CSS files in /css/ directory

## Best Practices
- Optimize images before adding to /img/
- Maintain mobile responsiveness
- Test across browsers (Chrome, Firefox, Safari)
- Use semantic HTML for SEO

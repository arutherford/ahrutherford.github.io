# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Repository Status

This is Adam Rutherford's personal GitHub Pages site with a modern, interactive landing page.

## Architecture

### Technology Stack
- Pure HTML/CSS/JS (no build process required)
- Modern CSS with CSS Grid/Flexbox
- Vanilla JavaScript for interactions
- SVG graphics for animated elements

### File Structure
- `index.html` - Main landing page with parallax effects and animated SVG elements
- Interactive elements respond to mouse movement
- Responsive design with mobile optimizations

### Deployment
- Deploys automatically via GitHub Pages from the main branch
- No build step required - static files served directly

## Development

### Local Development
```bash
# Serve locally (optional)
python -m http.server 8000
# or
npx serve .
```

### Key Features
- Gradient text effects with CSS background-clip
- Floating SVG shapes with CSS animations
- Mouse-responsive parallax effects
- Smooth gradient orbs with blur effects
- Mobile-responsive design
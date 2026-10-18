# Agent Guidelines for RRARSC Website

This document provides guidance for AI agents working on this codebase.

## Project Overview

A static website for Reigate and Redhill Artistic Roller Skating Club (RRARSC), a roller skating club based in Surrey, UK.

## Technology Stack

- Pure HTML5
- Pure CSS (no frameworks)
- No JavaScript build process
- Hosted on GitHub Pages

## Key Files

- `docs/index.html` - Single-page site with all content
- `docs/styles.css` - All styling, using CSS custom properties for theming
- `docs/assets/` - Images including logo and photos

## Photos

The site uses a fun, family-friendly visual style with:
- **Polaroid-style photos** - Use classes `fun-photo` with `tilt-left`, `tilt-right`, `tilt-left-more`, or `tilt-right-more`
- **Photo backgrounds** - Sections have photo backgrounds with colour overlays for readability
- **Photo pile effect** - The About and Performances sections have overlapping photos using `photo-pile` with `pile-1` through `pile-6` classes
- **Hero photo rows** - Rows of Polaroid photos at the top and bottom of the hero section (hidden on smaller screens)
- **Highlight boxes with images** - Use `highlight-box-with-image` class with `highlight-box-image` and `highlight-box-content` divs

To add more photos:
1. Add images to `docs/assets/`
2. Use the `fun-photo` class with a tilt modifier
3. Good sources: Facebook page photos, skating sessions, performances, disco nights

## Design Principles

- Mobile-first responsive design
- Accessible (skip links, semantic HTML, ARIA labels, keyboard navigation)
- Clean, modern look with the club's blue/red colour scheme
- No external dependencies (except Google Maps link)

## Content Guidelines

- The club name is "**Reigate and Redhill**" (not "Redhill and Reigate")
- The club **no longer competes** - focus is on skating for enjoyment
- Barry Bridger is the Head Coach and main contact
- All sessions require **pre-booking** via text/email
- Sessions are at The Hawthorns School Sports Hall, Bletchingley

## Reference Materials

The `ref/` directory contains:
- `old-website/` - Legacy site content for reference
- `newsletter-2026-03/` - Newsletter with detailed club information

These are not published to the live site.

## Colour Scheme

Defined as CSS custom properties in `styles.css`:
- Primary (blue): `#1e5a8a`
- Primary light: `#a5c6e7`
- Accent (red): `#ca0000`

## Testing

Open `docs/index.html` in a browser. Test:
- Desktop and mobile viewport sizes
- Navigation scroll behaviour (should clear sticky header)
- All external links (Facebook, Google Maps, GB Skate Artistic)

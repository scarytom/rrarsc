# RRARSC Website

Website for Reigate and Redhill Artistic Roller Skating Club.

## Live Site

The site is hosted on GitHub Pages: [https://YOUR_USERNAME.github.io/rrarsc/](https://YOUR_USERNAME.github.io/rrarsc/)

## Structure

```
rrarsc/
├── docs/               # Published site (GitHub Pages source)
│   ├── index.html      # Main page
│   ├── styles.css      # Stylesheet
│   ├── assets/         # Images and logo
│   └── .nojekyll       # Bypass Jekyll processing
└── ref/                # Reference materials (not published)
    ├── old-website/    # Legacy site for reference
    └── newsletter-2026-03/
```

## Development

This is a static site using pure HTML5 and CSS. No build process required.

To preview locally, open `docs/index.html` in a browser, or use a local server:

```bash
cd docs
python -m http.server 8000
```

Then visit http://localhost:8000

## Deployment

The site deploys automatically via GitHub Pages when changes are pushed to the `master` branch.

GitHub Pages settings:
- Source: Deploy from a branch
- Branch: master
- Folder: /docs

## Contact

Barry Bridger - Head Coach  
Phone: 07944 281862  
Email: barrybridger87@gmail.com

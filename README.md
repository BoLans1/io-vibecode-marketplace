# iO VibeCode Marketplace

A static HTML/CSS mockup of an internal marketplace where iO colleagues can discover, share, and download vibecoded software projects -- built with [Bonzai](https://bonzai.io), iO's own AI platform.

## Live Demo

**[https://bolans1.github.io/io-vibecode-marketplace/](https://bolans1.github.io/io-vibecode-marketplace/)**

## Overview

| Page | Description |
|------|-------------|
| **index.html** | Overview page with hero, search bar, project cards, FAQ accordion, and an "Add project" modal form |
| **ads-app.html** | Detail page for the *Ads App* -- an advertising management SaaS platform |
| **traveling-salesman.html** | Detail page for the *Traveling Salesman Solver* -- a route-optimization workflow |
| **beacon.html** | Detail page for *Beacon* -- a website step-recorder and dataLayer inspector |

## Brand and Design

- **Colors:** iO Blue `#0000d2`, Black `#242424`, Beige `#e1cfbf`, White `#ffffff`
- **Font:** [Manrope](https://fonts.google.com/specimen/Manrope) via Google Fonts
- **Responsive:** fully responsive down to mobile (480px)
- **CSS-only:** no JavaScript framework, no build step

## File Structure

```
index.html                   Main overview / marketplace page
ads-app.html                 Ads App detail page
traveling-salesman.html      Traveling Salesman Solver detail page
beacon.html                  Beacon detail page
css/styles.css               All shared styles (271 lines)
brand assets/iO_Avatar.svg   Favicon / brand mark
Images/Headers/              Project banner images
Images/Personen/             Creator / contact portrait photos
initial_prompt.md            Original prompt used to generate the site
README.md                    This file
```

## Running Locally

No build step required -- just open `index.html` in your browser.

## How It Was Made

This entire site was vibecoded -- generated through conversational AI prompting. See `initial_prompt.md` for the original brief (in Dutch).

## License

Internal iO project -- not licensed for external use.
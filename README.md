# duncanrose.com

Simple domain ownership verification page that redirects to a non-profit website.

## Changing the Redirect Target

Edit `index.html` and update the URL in two places:
1. The `content` attribute in the `<meta http-equiv="refresh">` tag
2. The `href` attribute in the `<a>` tag in the body

## Non-Profit Redirect Options

Here are some popular non-profit organizations you can redirect to:

### Education & Knowledge
- **Wikipedia**: `https://en.wikipedia.org/wiki/Main_Page`
- **Internet Archive**: `https://archive.org`
- **Project Gutenberg**: `https://www.gutenberg.org`
- **Khan Academy**: `https://www.khanacademy.org`

### Open Source & Technology
- **Mozilla Foundation**: `https://foundation.mozilla.org`
- **Electronic Frontier Foundation**: `https://www.eff.org`
- **Free Software Foundation**: `https://www.fsf.org`

### Humanitarian & Social
- **Doctors Without Borders**: `https://www.doctorswithoutborders.org`
- **Red Cross**: `https://www.redcross.org`
- **UNICEF**: `https://www.unicef.org`
- **World Wildlife Fund**: `https://www.worldwildlife.org`

### Research & Science
- **NASA**: `https://www.nasa.gov`
- **National Science Foundation**: `https://www.nsf.gov`
- **Smithsonian**: `https://www.si.edu`

## Setup

1. Enable GitHub Pages in repository settings
2. Configure DNS:
   - CNAME record: `duncanrose.com` → `DuncanRose.github.io`
   - Or A records pointing to GitHub Pages IPs

## Purpose

Demonstrates domain ownership without revealing personal information.

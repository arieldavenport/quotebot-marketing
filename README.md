# QuoteBot Marketing Website

## Overview
This repository contains the marketing website for QuoteBot, the SOW generator for ScopeStack.

## Features
- Simple, fast-loading marketing site with 3 pages
- Tailwind CSS for styling (no build step)
- Dark mode support
- Mobile-responsive design

## Setup
1. Clone the repository:
   ```bash
   git clone https://github.com/arieldavenport/quotebot-marketing.git
   ```

2. Navigate to the project directory:
   ```bash
   cd quotebot-marketing
   ```

3. Deploy to Cloudflare Pages:
   - Go to Cloudflare Pages dashboard
   - Connect your GitHub repository
   - Select this repository
   - The deployment will be handled automatically via GitHub Actions

## Deployment
The site is automatically deployed to Cloudflare Pages using the GitHub Actions workflow in `.github/workflows/deploy.yml`.

## Customization
- Edit the HTML files in the root directory to customize content.
- Add more screenshots to the `static` folder as needed.

## License
This project is licensed under the MIT License.
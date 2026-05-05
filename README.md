# Clinique Pasteur Tunis

Single-page demo web app for an AI-assisted digital health platform.

## What's included

- `index.html`: landing page, chatbot demo, dashboard, and specialist showcase
- `.nojekyll`: helps GitHub Pages serve the repo as a plain static site

## Improvements in this version

- safer startup when external chart assets fail to load
- dashboard tabs now switch real KPI and summary content
- cleaner chatbot flow without duplicate user messages

## Publish on GitHub Pages

1. Push this repository to GitHub.
2. In the repository settings, open `Pages`.
3. Set the source to deploy from the default branch root.
4. GitHub will publish `index.html` automatically.

## Notes

- The page still uses CDN-hosted Tailwind and Chart.js.
- This project is set up as a static site, so no build step is required.

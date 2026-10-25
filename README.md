# Manamer

A responsive, bilingual corporate website for Manufacturas Americanas Cía. Ltda.

## Run and build

Requires Node.js 20 or newer. No npm dependencies.

- `npm run check`: JavaScript syntax validation.
- `npm run build`: copies public assets into dist/.
- Preview: `python3 -m http.server 8080 --directory public`.

## Deploy to Vercel

Import this GitHub repository into a new Vercel project. Keep the repository root as the root directory. The included vercel.json sets the framework to Other, build command to npm run build and output directory to dist. Pushes to main can deploy automatically through Vercel's GitHub integration.

Connect manamer.com only after the replacement is reviewed. Preserve existing mail-related DNS records. The current domain has not been changed.

## Content and functionality

Spanish and English content, keyboard-accessible brand dialogs, mobile navigation, direct phone contact and map links. Assets and factual company information originate from the existing manamer.com homepage, retrieved October 25, 2026. Editorial wording is a proposed redesign. Corporate destinations are preserved from that site and have not been authenticated or independently verified. No contact form backend or job-application system is implied; contact and careers use the published company phone number.

Original secondary pages returned 404 responses. Existing company, brands, careers and contact paths redirect to the corresponding new sections on Vercel. Brand paths redirect to their detail dialogs.

## Editing

Content: public/index.html; styling: public/style.css; language toggle and brand details: public/app.js; photography: public/assets/. Fonts use Google Fonts with system fallbacks. Confirm brand portfolio and contact details with Manamer before switching its domain. Photography remains subject to the original owner's rights.


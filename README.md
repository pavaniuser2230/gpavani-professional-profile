# G Pavani Portfolio

This project is a responsive React + Vite personal portfolio for G Pavani, built to showcase AI/ML learning, research direction, customer experience work, project experience, and professional presence.

## Local development

```bash
npm install
npm run dev
```

Then open the local Vite URL shown in the terminal.

## Production build

```bash
npm run build
```

## Deployment

This portfolio is configured for Netlify-friendly deployment. The repository includes a `netlify.toml` file and a `public/_redirects` rule so the React app routes correctly when deployed.

### Recommended Netlify setup

1. Push the project to GitHub.
2. Import the repository in Netlify.
3. Keep the build command as `npm run build`.
4. Keep the publish directory as `dist`.
5. Deploy the site and confirm the live URL.
6. Update the canonical URL and verification tag in the site metadata after the final production domain is selected.

## Content updates

The main profile content is stored in `src/data/content.js` so the portfolio can be updated without changing the page layout.

## Notes

- The website intentionally avoids inventing unverified credentials or dates.
- Any certificate or document links should be added only after the actual file or confirmed source is available.
- Update the Google verification value and final site URL when the live production domain is confirmed.

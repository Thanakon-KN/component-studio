# Component Studio

Static, non-AI UI mockup for viewing a source website and selecting components to compose a page preview.

## Current scope

- Responsive mockup with a URL input, live website preview, and six sample components.
- The preview loads the entered URL in an iframe when the source website permits embedding.
- Filter, search, select/deselect, preview, and export-button interactions run in the browser.
- Component detection and code export are demo interactions; the page does not capture screenshots or parse the live website yet.
- No AI service or backend is used.

For reliable previews of sites that block iframe embedding, a production version will need a browser capture service (for example, a Playwright-based backend). Component suggestions can still use deterministic DOM rules without AI.

## Publish with GitHub Pages

1. Put the files in the root of a GitHub repository.
2. In the repository, open **Settings → Pages**.
3. Set the source to **Deploy from a branch**, select `main` and `/ (root)`, then save.
4. GitHub Pages will show the public site URL in the same Pages settings section after deployment.

The entry page is `index.html` and the project is static-hosting ready.

# NeurIPS 2026 Collective Appeal — GitHub Pages site

This folder is ready to publish as a static site.

## Files
- `index.html` — the full website
- `assets/procedure-cycle.png` — procedure illustration used on the page
- `.nojekyll` — keeps GitHub Pages serving the static files as-is

The public package intentionally contains **no appeal PDF, no Appendix A submission list, and no deadline graphics**.

## Publish on GitHub Pages

1. Create a new GitHub repository.
2. Upload everything in this folder to the repository root.
3. Go to **Settings → Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**.
5. Select the `main` branch and `/ (root)`.
6. Save. GitHub will show the public site URL after deployment.

No build step, npm, framework, or external dependency is required.

## Editing
All page text and styling live inside `index.html`.

The site is structured for public sharing:
- a fast factual overview of what the collective appeal alleges,
- a clear statement of what the appeal is *not* arguing,
- the principal procedural questions,
- the requested relief,
- and direct links to the NeurIPS materials cited by the appeal.

Claims about what occurred are framed as statements made by the appellants unless independently reflected in the linked NeurIPS sources.

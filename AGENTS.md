# AGENTS.md

## Scope

This repository contains the public home for the iPhoto2 photo-product family, plus shared privacy and support pages. FoodPhotos is the first iPhoto2 product.

## File Contract

Keep the repository intentionally small. The permitted files are:

- `README.md`
- `AGENTS.md`
- `index.html`
- `privacy.html`
- `support.html`

Do not add generated assets, package manifests, lockfiles, build output, JavaScript files, CSS files, or framework configuration without explicit approval.

## Implementation Rules

- Use semantic HTML5.
- Use Tailwind CSS through the pinned browser CDN package.
- Do not add a build process.
- Do not add client-side JavaScript except the Tailwind CSS browser CDN script.
- Do not add cookies, analytics, tracking, forms, accounts, advertising, or network integrations.
- Keep every page responsive and keyboard accessible.
- Preserve visible focus states and sufficient color contrast.
- Keep all source text, documentation, identifiers, comments, and commit messages in English.
- Pin every external dependency to an exact version.

## Content Rules

- Use `iPhoto2` as the product-family name and `FoodPhotos` as the first product name.
- Keep one shared privacy policy and one shared support page for all iPhoto2 products.
- Add future products to the home page and the relevant support section. Do not create separate privacy or support pages.
- Require every iPhoto2 product to follow the shared privacy model: on-device processing, no iPhoto2 account, and no personal photo content or analysis results sent to iPhoto2.
- Do not claim that FoodPhotos uploads, copies, edits, caches, or deletes original photos.
- State that FoodPhotos location access is used only for map presentation and not for classification.
- Do not promise recognition accuracy or production readiness.
- Confirm that `support@iphoto2.com` is operational before production deployment.

## Validation

Before pushing a change:

1. Serve the repository with a simple static HTTP server.
2. Open all three pages on desktop and mobile viewports.
3. Verify navigation and email links.
4. Verify that no local file or route returns an error.
5. Verify that the repository still contains only the permitted files.

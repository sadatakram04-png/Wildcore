# PANELVERSE PRO MAX — Manhwa Catalog Update

Arabic RTL mobile-first PWA for discovering Korean-origin manhwa through the public MangaDex API.

## Catalog behavior
- Discovers Korean-origin titles (`originalLanguage=ko`) from MangaDex, including works without Arabic chapters.
- Uses paginated loading (30 titles per request) with a Load More control rather than limiting discovery to the first page.
- Search, status, content-rating, sorting, and client-side genre filters.
- The detail page separately lists Arabic-translated chapters when the source has them.
- Reader loads chapter pages directly from MangaDex@Home; this app does not host or re-upload chapter images.

## Important limits
- “All manhwa” means the available Korean-origin catalog exposed by MangaDex, not every manhwa published anywhere on the internet.
- Arabic chapter availability varies by title and translation group. A title can appear in the catalog while having no Arabic chapters.
- Catalog updates are fetched when the app is opened/refreshed; there is no background polling while the app is closed.
- Favorites and reading history are stored locally in the browser. No accounts or cloud sync.
- Respect MangaDex terms, contributor credits, and removal requests. Do not bypass paywalls/DRM or rehost copyrighted chapters.

## Deploy
Upload the contents of this folder to the root of your GitHub Pages repository, replacing the previous version, then commit the changes.


Branding update: added `panelverse-logo.png`, applied the artwork to the header, and refreshed the PWA icons.

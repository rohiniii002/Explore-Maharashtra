# Explore Maharashtra — Complete Website

A responsive multi-page tourism website for discovering Maharashtra.

## Files
- `index.html` — homepage, searchable destinations, category filters and trip planner
- `destination.html?id=...` — destination detail page template (each card opens a dedicated URL)
- `favourites.html` — saved destinations
- `styles.css` — responsive styling, typography, color palette and animations
- `app.js` — destination data, search, filters, favourites, detail pages and itinerary generation

## Run locally
Open `index.html` in a browser. Internet access is needed for Google Fonts and remote Unsplash images.

## Publish on GitHub Pages
1. Create a public repository.
2. Upload all five files (`index.html`, `destination.html`, `favourites.html`, `styles.css`, `app.js`) to the repository root.
3. Open **Settings → Pages**.
4. Choose **Deploy from a branch**, branch `main`, folder `/(root)`, and save.
5. Wait for the published URL to appear.

## Functional notes
- Destination search and category filters work in the browser.
- Destination cards open detail pages with highlights, travel tips, best time to visit and map links.
- Favourites are stored in browser localStorage on the current device/browser.
- Trip planner generates a sample itinerary and supports copying it where browser clipboard permissions allow.
- Newsletter is a front-end demo and does not send or store email addresses.
- Map buttons open a Google Maps search, not an embedded/live booking service.
- Image URLs are external and may be illustrative; check destination-specific imagery and current travel details before publishing.

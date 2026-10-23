[Uploading README.md…]()
# Wardrobe – My Closet

A responsive, browser-based closet organizer hosted as a static website on GitHub Pages.

## Features
- Add clothing and accessories with a photo, name, type, size, and color
- Categories include tops, bottoms, dresses, outerwear, shoes, bags, and accessories
- Search and sort items
- Mark items as needing a wash; they move into the bottom-left wash basket and return to the closet when marked washed
- Favorite items
- Build, date, save, edit, and delete outfit collections
- Swipe a card left to remove it, with undo
- Custom background image and light/dark appearance
- JSON backup and restore for wardrobe items
- Responsive mobile layout

## Run locally
Open `index.html` in a modern browser.

## Publish with GitHub Pages
1. Upload `index.html`, `README.md`, and `LICENSE` to the repository root.
2. Open **Settings → Pages**.
3. Select **Deploy from a branch**, branch `main`, folder `/ (root)`, and save.

## Privacy and storage
Wardrobe items, photos, favorites, outfits, and background settings are stored in the browser's local storage. They are not uploaded to a server. Browser data is local to that browser/device; use the backup feature to transfer wardrobe items. **Cross-device cloud sync and user accounts are not implemented**; those require configuring a separate backend service such as Firebase or Supabase and setting up authentication/security rules.

## License
MIT. See `LICENSE`.

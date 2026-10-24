[Uploading README.md…]()
# Wardrobe ("my closet")

A playful closet organizer that runs entirely in your browser. No account, no server, no internet needed. The whole app is one HTML file.

## Features
- Built for phones and desktop: a touch-friendly phone layout with its own background, and the full layout on bigger screens
- Swipe left or right (or use the arrows or keyboard arrow keys) to flip through your clothes, with a whoosh sound
- Add clothes with a photo, name, type, size and color
- **Add to wash**: the item flies into the trash can, the can wiggles and the cat gets scared. Tap the can to see the wash list and mark items as washed
- **Add to fav**: the item flies into the heart. The Favorites button shows only favorites
- Search and category tabs
- Plan outfits (with a shuffle button) and create collections
- Click sounds, background music (bring your own songs), light and dark mode
- Custom background picture
- Save and load a JSON backup

## Use it
Download `index.html` and open it in any browser. That's all.

Your closet is stored in your own browser (localStorage and IndexedDB). Nothing is uploaded anywhere. Use "Save backup" in the menu (the blue circle) to keep a copy.

## Music
No song is included. Tap the ♪ button, choose one or more audio files from your device, and they will loop. Your choice is remembered in your browser. Browsers block sound until you interact with the page, so music starts on your first tap.

## Host it free on GitHub Pages
1. Create a new public repository on GitHub.
2. Upload `index.html`, `LICENSE` and `README.md`.
3. Go to Settings, then Pages. Under "Build and deployment", choose "Deploy from a branch", select `main` and `/ (root)`, then save.
4. After a minute, your site is live at `https://YOUR-USERNAME.github.io/REPO-NAME/`.

## Contributing
No build step and no dependencies. Fork it, change it, and open a pull request.

## Credits
Fonts: Gochi Hand and Patrick Hand SC from Google Fonts (loaded online, with fallbacks offline).

## License
MIT. See `LICENSE`. Replace "Your Name" in `LICENSE` and at the top of `index.html` with your own name.

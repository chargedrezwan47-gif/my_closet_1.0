# Wardrobe – My Closet

A simple, responsive closet organizer that runs entirely in your browser. It needs no account, server, or external dependencies.

## Features

- Add clothes with a photo, name, type, size, and color
- Search, filter by type, and sort items
- Mark items that need washing and filter the “To wash” list
- Swipe a card left to remove it, with undo
- Choose a custom background picture
- Save and load a JSON backup
- Light and dark mode

## Run locally

Open `index.html` in a modern web browser.

Your closet data is stored in this browser using `localStorage`; it is not uploaded to a server. Data is browser- and site-specific, so use **Save backup** to keep a copy before clearing browser data or moving to another browser/device.

## Publish with GitHub Pages

1. Create a public repository on GitHub.
2. Upload `index.html`, `LICENSE`, and `README.md` to the repository root.
3. Open **Settings → Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**.
5. Select the `main` branch and the `/ (root)` folder, then save.
6. Wait for the deployment to finish. Your site will be available at `https://YOUR-USERNAME.github.io/REPOSITORY-NAME/`. Replace the placeholders with your GitHub username and repository name.

## Contributing

Fork the repository, make your changes, and open a pull request. The app is contained in one HTML file and has no external dependencies.

## License

This project is distributed under the MIT License. See [`LICENSE`](LICENSE). Update the copyright holder placeholder in `LICENSE` before publishing.

# GoldenDragonInk Plus

A GitHub Pages-ready multi-book reading website by Sreekar Swarna.

## Features
- Multiple books and title/genre search
- WebNovel-style online chapter reader
- Table of contents and previous/next chapter navigation
- Browser-saved reading progress and homepage Continue Reading cards
- Chapter bookmarks
- Adjustable text size and sepia reading mode
- Responsive dark-and-gold design

## Add books and chapters
Edit `books.js`. Add a new object to the `BOOKS` array with a unique `id`, title, author, genres, cover path, description, and `chapters`. Each chapter uses `{ title: "Chapter title", content: ["Paragraph one.", "Paragraph two."] }`. Upload the matching cover image to the path specified in `cover`.

Replace all sample chapter text before publishing.

## Publish on GitHub Pages
1. Create a public GitHub repository, e.g. `GoldenDragonInk`.
2. Upload the contents of this folder to the repository root. `index.html` must be at the root.
3. Open Settings → Pages.
4. Choose Deploy from a branch, branch `main`, folder `/(root)`, then Save.
5. After deployment, the URL will usually be `https://YOUR-USERNAME.github.io/GoldenDragonInk/`.

Progress and bookmarks are stored locally in the reader's browser. They do not sync across devices and there are no accounts, comments, or cloud backups. Do not upload private drafts to a public repository; only publish content you own or have permission to share.

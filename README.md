# Sabay Homepage CSS Clone

An HTML and CSS recreation of a Khmer news homepage, practicing Flexbox, article grids, image overlays, and hover interactions.

This is a frontend learning project inspired by Sabay. It includes category navigation, featured news panels, video and article sections, and a footer. News links are mostly placeholders; there is no news API, CMS, or backend.

## Clone and preview

Install Git. Python 3 is useful for a local preview server; no Node.js dependencies or build step are required.

```sh
git clone https://github.com/PANHARO/css_clone_sabay.git
cd css_clone_sabay
python -m http.server 8000
```

If your system uses `python3`, use `python3 -m http.server 8000`. Open `http://localhost:8000` in a browser and stop the server with Ctrl+C when finished. You can also open `index.html` directly for a simple preview.

Internet access is needed for the external Khmer fonts and Font Awesome icons. The page's images and main CSS are stored locally in the repository.

## Project structure

| Path | Purpose |
| --- | --- |
| `index.html` | Homepage sections, navigation, and article markup |
| `CSS/style.css` | Layout, typography, overlays, and hover styles |
| `Image/` | Local images used by the page |

## Customize it

- Edit headings, article titles, and links in `index.html`.
- Change layout, spacing, colors, and hover behavior in `CSS/style.css`.
- Add replacement images under `Image/` and update the corresponding paths.
- Keep folder and filename case consistent when hosting on a case-sensitive server.

The current layout contains fixed widths and heights and is best treated as a desktop layout exercise. Check smaller screens before describing a customized version as fully responsive. Navigation and article links need real destinations before use as a live news site.

## Contributing and attribution

Fork the repository, clone your fork, and create a branch with `git switch -c your-change`. Preview your edits in a browser before opening a pull request.

Sabay branding and referenced content belong to their respective owners. This repository is an educational layout recreation; it does not represent an official Sabay website. Replace third-party branding and content as appropriate for your own published project.

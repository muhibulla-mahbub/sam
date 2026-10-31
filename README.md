# Muhibulla Mahbub (SAM): Personal Website

Personal website of Muhibulla Mahbub, based in Dhaka, Bangladesh.
Plain HTML, CSS and JavaScript. No build step, no dependencies.

## Pages

| File | Page |
| --- | --- |
| `index.html` | Home |
| `about.html` | About |
| `contact.html` | Contact |

## Structure

```
.
├── index.html
├── about.html
├── contact.html
├── *.png          # logos
├── loading.webm   # loading screen video
├── loading.mp4    # same video for Safari / older iPhones
├── README.md
├── LICENSE
├── .gitignore
└── .nojekyll
```

## Run locally

Open `index.html` in a browser, or run `python3 -m http.server 8000` and visit http://localhost:8000

## Publish on GitHub Pages

1. Push all files to a GitHub repository (keep `index.html` in the root).
2. Settings → Pages → Deploy from a branch → `main` / `(root)` → Save.
3. The site goes live at `https://<username>.github.io/<repository>/`.

## Editing

Each page keeps its text, links and images in a `CONFIG` object near the top of its `<script>`.

## License

All rights reserved. See [LICENSE](LICENSE).

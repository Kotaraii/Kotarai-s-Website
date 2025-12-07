Static export of the GitHub Gems Gallery

This folder contains a lightweight, standalone HTML+CSS copy of the main page from the React project.

Files:
- `index.html` — the page
- `styles.css` — styles used by the page

Notes:
- The avatar uses an inline SVG placeholder. If you want the original profile image, copy `src/assets/profile.png` into this folder and replace the SVG in `index.html` with an `<img>` referencing `assets/profile.png`.

To preview locally with PowerShell (Windows):

```pwsh
# from repository root
cd 'c:\Users\Banksy\Downloads\github-gems-gallery-main\static-site'
# Start a simple static server if you have Python 3
python -m http.server 5173
# then open http://localhost:5173 in your browser
```

You can also open `index.html` directly in your browser, but some browsers restrict loading local fonts or resources when opened via file://.
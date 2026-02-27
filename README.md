# dynamic-cv

A simple editable HTML-based curriculum vitae (CV) that you can preview locally or publish via GitHub Pages.

The project includes a dark-themed live editor with a print-friendly stylesheet so that the **PDF export is black text on white** for easy resume parsing.

## Preview locally

```bash
cd /workspaces/dynamic-cv
python3 -m http.server 8000
```

Then open `http://localhost:8000/index.html` in your browser.

## GitHub Pages

GitHub Pages will serve `index.html` by default. A `.nojekyll` file is included to prevent Jekyll from processing Markdown, which ensures the HTML file is used instead of the README.

To publish, enable Pages in your repository settings and choose the `main` branch / root.

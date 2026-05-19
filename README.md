# things

A minimalistic, semantic content writer for the web — or wrapped as a native macOS app via [Nativefier](https://github.com/nativefier/nativefier).

**Live app → [ross-allchorn.github.io/things](https://ross-allchorn.github.io/things)**

---

## Features

- WYSIWYG rich text editing (bold, italic, underline, strikethrough, headings, lists, blockquote, HR)
- Block format selector: Paragraph, H1–H4, Code block
- Auto-saves to `localStorage` on every keystroke (restored on next visit)
- Word count in the status bar
- Download your content as a self-contained **HTML** file or **Markdown** file
- Light & dark mode via `prefers-color-scheme`
- Single file — zero dependencies, no build step

## Usage

### In the browser

Open `index.html` directly, or visit the GitHub Pages URL above.

### As a macOS desktop app

```bash
npx nativefier --name "Writer" https://ross-allchorn.github.io/things
```

## Deployment

The app is deployed to GitHub Pages from the `main` branch root. No build step required — `index.html` is served directly.

## License

See [LICENSE](LICENSE).

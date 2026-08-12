# SAMPAKA Website

Static HTML5/CSS3/Vanilla JavaScript website for Samahang Pangkasaysayan ng Bulacan (SAMPAKA).

## Files

- `index.html` — complete single-page website
- `style.css` — responsive visual system
- `script.js` — mobile navigation, reveal animation, year, archive placeholder interaction
- `images/` — place actual SAMPAKA logo and archival images here

## Add the real SAMPAKA logo

The supplied SAMPAKA logo is installed at `images/sampaka-logo.png` and is used in the header, hero, and footer. To replace it later, keep the same filename or update the image path in `index.html`.

```html
<img src="images/sampaka-logo.png" alt="Samahang Pangkasaysayan ng Bulacan (SAMPAKA)">
```

Use the same relative path in the desktop header, mobile navigation, hero if desired, and footer.

## Replace image placeholders

Use semantic `<img>` elements with meaningful `alt` text. Example:

```html
<img src="images/heritage-place.jpg" alt="Description of the actual historical or heritage image">
```

Keep the image paths relative (`images/...`) so GitHub Pages can serve them.

## GitHub Pages

1. Create or open the repository for `sampakabulacan.github.io`.
2. Put `index.html` at the repository root.
3. Add `style.css`, `script.js`, and the `images/` directory at the root.
4. Commit and push the files.
5. In GitHub repository Settings → Pages, publish from the appropriate branch/root.
6. The intended canonical site is `https://sampakabulacan.github.io/`.

No framework or build step is required.

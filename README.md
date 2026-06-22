# assets/images/

This folder is for any images you want hosted directly in this repo rather than
pulled from an external URL.

**Currently unused** — the About section's portrait image in `index.html` loads
from an external Squarespace CDN link. If that link ever breaks, or you want
faster/more reliable image loading, here's how to switch to a local image:

1. Save your image into this folder, e.g. `assets/images/vaishali-portrait.jpg`
2. In `index.html`, find this line (in the About section):
   ```html
   <img src="https://images.squarespace-cdn.com/..." alt="Portrait of Vaishali Sharma">
   ```
3. Replace the `src` value with the local path:
   ```html
   <img src="assets/images/vaishali-portrait.jpg" alt="Portrait of Vaishali Sharma">
   ```
4. Commit and push — the image will now load directly from this repo.

You can do the same for the brand card/poster images, the MAG logo, or any
future blog/shop product images.

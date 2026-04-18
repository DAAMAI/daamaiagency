# DAAM Agency — Website

Live at: **daamaiagency.com**

---

## Folder structure

```
daamaiagency/
├── index.html          ← the whole website
├── README.md           ← this file
└── images/
    ├── work-01.png     ← feature slot / River / Beauty
    ├── work-02.jpeg    ← slot 2 / Still Water / Fashion
    ├── work-03.jpg     ← slot 3 / Flow / Ecom (needs real image)
    ├── work-04.jpg     ← slot 4 / Tide / Product (needs real image)
    ├── work-05.jpg     ← slot 5 / Ocean / Beauty (needs real image)
    └── work-06.jpg     ← slot 6 / Rain / Fashion (needs real image)
```

---

## How to edit the site

1. Go to the repo on github.com
2. Click `index.html`
3. Click the **pencil icon** (top-right of the code view)
4. Use **Ctrl+F** (Windows) or **Cmd+F** (Mac) to find what you want to change
5. Edit directly in the browser
6. Scroll to bottom → type a short message → click green **Commit changes** button
7. Site updates live in ~1 minute

---

## Quick edit cheat sheet

Press Ctrl+F / Cmd+F inside the editor and search for these terms to jump to the right spot:

| To change... | Search for | Notes |
|---|---|---|
| Feature image (slot 1) | `work-01.png` | Replace filename or upload new image with same name |
| Slot 2 image | `work-02.jpeg` | Same logic |
| Slots 3–6 images | `unsplash` | Will find 4 placeholder URLs to replace |
| Hero headline | `A.I. creative` | Top of page |
| Location line | `Hudson Valley` | NYC · Chicago · LA · London |
| "made by hand…" | `made by hand` | Handwritten note in hero |
| Contact email | `daamaiagency@gmail.com` | Used in nav Contact link |
| Instagram link | `instagram.com` | Used in nav |
| Category (Beauty/Fashion/etc) | `work-cat` | One per card, 6 total |
| Hover water names (River/Tide…) | `work-name` | One per card, 6 total |
| Rust accent color | `--rust:` | Hex value `#b4522a` |
| Blue dot in DA footer logo | `#6f94a7` | Hex value |
| "Get in touch" label | `Get in touch` | |
| "Let's make something" | `Let's make` | |

---

## How to upload a new image

**Easiest way (GitHub website):**

1. Go to the `images` folder in your repo
2. Click **Add file → Upload files**
3. Drag your new image in
4. **Important**: name it exactly as the HTML expects (e.g., `work-03.jpg`). Rename on your computer before uploading.
5. Click **Commit changes**
6. Wait ~1 minute → live

**To replace an existing image:**

1. Click the existing image in the `images` folder
2. Click the trash icon → Commit changes
3. Upload the new one with the same filename
4. Commit again

---

## Image size guidelines

- Keep images **under 500KB** each
- JPEG for photos, PNG only if you need transparency
- Good widths: 1600px (feature card), 1000px (portrait slots)
- Compress before uploading: [tinypng.com](https://tinypng.com) or [squoosh.app](https://squoosh.app)

---

## If something breaks

Every edit is saved in GitHub's history. To undo:

1. Go to your repo
2. Click the **commits** link (top of file list)
3. Find a working version
4. Copy the old code, paste it back, commit

You can't lose anything. Edit freely.

---

## Launch checklist

- [x] Site code finalized
- [x] Domain owned (daamaiagency.com via GoDaddy)
- [ ] Upload to GitHub repo
- [ ] Enable GitHub Pages in repo settings
- [ ] Point GoDaddy DNS at GitHub (4 A records + 1 CNAME)
- [ ] Enable "Enforce HTTPS" in Pages settings
- [ ] Replace slot 3–6 images with real campaigns
- [ ] Share the live URL with the world

---

**Built with care. Made by hand, moved by machine.**

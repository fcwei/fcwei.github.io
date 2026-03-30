# Fuchuan Wei - GitHub Pages Homepage

A lightweight academic homepage that can be deployed directly on GitHub Pages.

## Files

- `index.html` — the whole homepage in a single file
- `assets/` — put your CV PDF, profile photo, or other files here

## How to deploy on GitHub Pages

### Option A: personal site (recommended)
1. Create a repository named `YOUR_USERNAME.github.io`
2. Upload everything in this folder to the repository root
3. Go to **Settings → Pages**
4. Under **Build and deployment**, choose:
   - **Source**: Deploy from a branch
   - **Branch**: `main` / `/root`
5. Wait a minute and open `https://YOUR_USERNAME.github.io/`

### Option B: project site
1. Create any repository, for example `homepage`
2. Upload these files
3. Go to **Settings → Pages** and enable deployment from `main` / `/root`
4. Your site will usually be at `https://YOUR_USERNAME.github.io/homepage/`

## Important note about search engines

This template currently includes:

```html
<meta name="robots" content="noindex, nofollow" />
```

That means search engines are asked **not** to index the site.

- Keep it if you want the site online but harder to find from search.
- Remove it when you want normal indexing.

## Quick edits you probably want to make

Open `index.html` and update:

- your email
- your CV link
- your profile photo
- your research description
- your publication list

## Suggested extra files

You may want to add:

- `assets/cv.pdf`
- `assets/profile.jpg`

Then replace the placeholder text and links in `index.html`.

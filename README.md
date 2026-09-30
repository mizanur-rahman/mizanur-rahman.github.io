# Mizanur Rahman — Personal Website

A minimal academic/industry website designed for GitHub Pages.

## Philosophy

The site intentionally avoids a generic "AI portfolio" look. It is built around:
- short biography
- news / updates
- experience
- awards
- selected publications

It uses no framework and requires no build step.

## Local test

Run:

```bash
python -m http.server 8000
```

Then visit:

```text
http://localhost:8000
```

You can also open `index.html` directly.

## Add your profile photo

The website is already configured for your photo.

Simply place your picture here:

```text
assets/profile.jpg
```

That is all you need to do. You do **not** need to edit the HTML.

Recommended:
- Filename: `profile.jpg`
- Square or nearly square image
- Professional headshot
- At least 500 × 500 pixels

The website crops the image into a circle automatically.

If `profile.jpg` is not present, the website automatically shows the `MR` placeholder instead.
## Awards

The Awards section is intentionally not populated with guessed information.
Replace the explanatory sentence with your confirmed awards and years.

## Scholar metrics

The homepage currently contains the Scholar metrics you provided:
- Citations: 1,278
- h-index: 14
- i10-index: 17

These are static numbers. Update them periodically, or remove the metrics block if you prefer not to maintain it.

## Free GitHub Pages deployment

Create a repository named:

```text
mizanur-rahman.github.io
```

Then push these files to `main`.

In GitHub:

**Settings → Pages → Deploy from a branch → main → /root**

Site:

```text
https://mizanur-rahman.github.io/
```

# Naveen Raj A: portfolio

A plain HTML, CSS site. No build step, no dependencies.

```
index.html
assets/
  img/    photos, UI/UX screens, video posters
  video/  demo reels (MP4)
netlify.toml
```

## Edit
- Text: open `index.html` and change the words.
- Colours: change `--accent` value on the `.root` element (default `#2F54FF`).
- Photos or videos: replace the files in `assets/` and keep the same file names.
- Anchoring videos: change the YouTube links and the video IDs inside the `#anchoring` section.

## Host on Netlify
1. Push this folder to a GitHub repository.
2. On Netlify choose Add new site, then Import an existing project, then pick the repository.
3. Leave the build command empty and set the publish directory to `.` (a dot). `netlify.toml` already says this.
4. Deploy. Every push to GitHub redeploys the site.

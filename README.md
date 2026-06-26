# Luxeongrid Portfolio — Two-Folder Upload

## Folder layout

```text
index.html
.nojekyll
.gitignore
graphics/   ← all portfolio images + video preview posters
videos/     ← all 15 MP4 videos
```

## Upload to GitHub

1. Extract this ZIP on your computer.
2. Open your GitHub repository.
3. Upload **all four items** directly to the repository root:
   - `index.html`
   - `.nojekyll`
   - `graphics` folder
   - `videos` folder
4. Commit the upload. Do not upload the ZIP itself and do not place these items inside another parent folder.
5. Vercel redeploys automatically after GitHub receives the commit.

Every URL in `index.html` points only to `graphics/` or `videos/`.

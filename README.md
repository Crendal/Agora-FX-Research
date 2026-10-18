# AGORA FX Research Portfolio — Seong Kyu Lee

A single-file, dependency-free HTML portfolio for sharing in applications. Includes searchable and filterable publication cards, verified individual AGORA LinkedIn links and clearly marked company-feed placeholders where the direct URL was not recoverable.

## View locally
Double-click `index.html` in Chrome, Edge, or Firefox. No installation required.

## Publish to GitHub Pages
1. Sign in to GitHub, create a **public** repository, for example `agora-fx-research`.
2. Upload `index.html` to the repository root. (You can also upload this README.)
3. Go to **Settings → Pages → Build and deployment**, select **Deploy from a branch**, choose `main` and `/ (root)`, and save.
4. When published, your portfolio should be at `https://YOUR-USERNAME.github.io/agora-fx-research/` (substitute your username/repository).
5. Add that URL to the Projects/Research section of your CV or your personal LinkedIn.

## Data and accuracy
The `archiveData` script tag within `index.html` holds the self-contained JSON array. To append a missing AGORA FX post, copy an existing entry, change the period/title/summary/URL/edition, and keep the JSON valid. Use `linktype: "direct"` only for a confirmed post permalink, `linktype: "repost"` for a confirmed repost, or `linktype: "feed"` for a company-feed link. **The index is not guaranteed to include every historical post.** AGORA Weekly Market Review is a collaborative publication; author credit for individual weekly FX sections has not been externally verified in each case.

## Attribution
Content descriptions are short independent summaries of AGORA public LinkedIn posts, with links to the publisher. This is a portfolio index, not a republication of copyrighted PDF slides. Only AGORA With Lens #5 was independently confirmed as explicitly crediting Seong Kyu Lee.

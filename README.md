# walkerjd.github.io

Personal academic website for Jeffrey D. Walker — hosted with GitHub Pages at https://walkerjd.github.io

## Structure

```
index.html        The entire site — one self-contained page (inline styles).
assets/
  marmoset.jpeg     Hero watercolor
  headshot-1.png    About-section portrait
  JWalker_CV.pdf    Downloadable CV
.nojekyll          Tells GitHub Pages to serve files as-is (skip Jekyll).
```

## How to edit

Everything is plain HTML with inline styles — open `index.html` and edit directly.
Common edits:

- **Add a publication** — copy one `<div class="pub-row">…</div>` block in the Publications
  section, paste it above the others, and update the year / title / author line / DOI link.
- **Update the CV** — replace `assets/JWalker_CV.pdf` with a new file of the same name.
- **Change the headshot framing** — adjust `object-position` on the `#about` portrait `<img>`
  (currently `91.6% 31.2%`).
- **Add Google Scholar / ORCID** — in the Contact section's "Elsewhere" column, add
  `<a href="…" target="_blank" …>Google Scholar</a>` links and remove the "coming soon" note.

## Publishing changes

Commit to the `main` branch (or upload edited files via GitHub's web UI).
GitHub Pages rebuilds automatically; the live site updates within a minute or two.

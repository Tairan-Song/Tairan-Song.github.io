# Tairan Song — Academic Website

Personal academic website of **Tairan Song**, a Ph.D. student at Michigan State University working in the Medical Imaging and Data Integration (MIDI) Lab.

Research interests include medical image analysis, radiomics, and graph-based representation learning for renal mass characterization from CT.

**[Visit the website](https://tairan-song.github.io/)** · [Curriculum vitae](materials/TairanSong_CV.pdf) · [RSNA slides](materials/RSNA_TS_AA.pdf)

## About the site

The website brings together publications and manuscripts, conference presentations, education, training, teaching, and contact information.

It is a static site built with HTML, CSS, and a small Google Analytics script. There is no package installation or build step. The layout adapts to desktop and mobile screens.

## Repository structure

```text
.
├── index.html                 # Page content, styles, and analytics
├── figures/                   # Profile photo and university logos
├── materials/
│   ├── TairanSong_CV.pdf       # Public CV
│   └── RSNA_TS_AA.pdf         # RSNA presentation slides
└── README.md
```

## Local preview

From the repository root, start a static server with Python 3:

```bash
python3 -m http.server 8000 --bind 127.0.0.1
```

Open the server address in a browser. Changes to `index.html` appear after refreshing the page. Stop the server with `Ctrl+C`.

## Updating the website

- **Page content and appearance:** edit `index.html`; styles are in its `<style>` block.
- **Images:** keep profile photos, logos, and other figures in `figures/`.
- **CV and presentation materials:** keep public documents in `materials/`. Use PDF for browser viewing and update every reference when renaming a file.
- **Publications:** maintain accurate author order, publication years, and acceptance status. The main publication entries retain the longer author lists.
- **Conference presentations:** use the `Oral` or `Poster` label. Where applicable, show the first three authors, an ellipsis, and the final author; place the venue and resource links to the right on desktop.
- **Author styling:** wrap `Song, T.` in `<span class="author-self">Song, T.</span>` for bold black text. Preserve Sabrina's preferred citation name, `Noyes, S. L.`.

Presentation PDFs open in a new tab without forcing a download:

```html
<a href="materials/RSNA_TS_AA.pdf" target="_blank" rel="noopener noreferrer">Slides</a>
```

Before publishing, check desktop and mobile layouts, author names, dates, images, and all CV and presentation links.

## Hosting

The website is hosted on **GitHub Pages**. Its entry point is `index.html` at the repository root. Publishing settings are managed under **Settings → Pages** in GitHub.

## Contact

[songtai1@msu.edu](mailto:songtai1@msu.edu) · [GitHub](https://github.com/Tairan-Song) · [LinkedIn](https://www.linkedin.com/in/tairan-s/)

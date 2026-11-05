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

Edit `index.html` to update the page. Store images in `figures/` and documents in `materials/`, and keep file links up to date.

## Hosting

The website is hosted on **GitHub Pages**. Its entry point is `index.html` at the repository root. Publishing settings are managed under **Settings → Pages** in GitHub.

## Contact

[songtai1@msu.edu](mailto:songtai1@msu.edu) · [GitHub](https://github.com/Tairan-Song) · [LinkedIn](https://www.linkedin.com/in/tairan-s/)

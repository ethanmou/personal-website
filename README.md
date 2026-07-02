# Xingyun Mou Personal Academic Website

This repository contains a lightweight static personal academic website for GitHub Pages.
It uses only HTML and CSS, with no JavaScript frameworks, build tools, analytics, or
external CSS dependencies.

## File Structure

```text
index.html
research.html
bio.html
writing.html
assets/profile.jpg
assets/styles.css
files/README_CV.txt
README.md
```

## Customization

- Update the name, program, institution, biography, and research descriptions directly in
  the HTML files.
- Replace placeholder external links for LinkedIn and Google Scholar with the correct
  profile URLs.
- Replace the placeholder profile photo at `assets/profile.jpg` with the final photo.
  The homepage already points to this path.
- Add the CV PDF at `files/Xingyun_Mou_CV.pdf`. The navigation and homepage CV links
  already point to this file.

If `files/Xingyun_Mou_CV.pdf` is not present, the CV links may be broken until the PDF is
uploaded.

## Deployment With GitHub Pages

To deploy as a user site, create or use a repository named:

```text
ethanmou.github.io
```

Commit these files to the repository's main branch. In the repository settings, enable
GitHub Pages and select the main branch as the publishing source. If configured correctly,
GitHub Pages should automatically serve the site from the main branch.

If you instead use the repository `personal-website`, GitHub Pages can still host the site
as a project page when Pages is enabled for that repository.

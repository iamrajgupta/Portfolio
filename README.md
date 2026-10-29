# Raj Gupta — Portfolio

Responsive, multi-page portfolio built with plain HTML, CSS and JavaScript. No build step or package installation is required.

## Pages

Home · Experience · Education · Work · Skills · Certifications · Gallery · Contact

## Run locally

Open `index.html` in a modern browser. Keep the `assets` folder beside the HTML pages so photos, videos, graphics and certificates load correctly.

## Upload to GitHub

Upload the contents of this folder to a new GitHub repository. The optimized portfolio videos and all other assets in this package are below GitHub's 25 MiB per-file browser-upload limit. The two large source videos were converted to web-ready H.264 copies; the site keeps their existing asset paths. The original full-resolution videos are in the separate `outputs/portfolio-website` folder and are not needed for this upload package.

You can upload through GitHub's **Add file → Upload files** page, or use Git from this folder after creating an empty repository:

```bash
git init
git add .
git commit -m "Add Raj Gupta portfolio"
git branch -M main
git remote add origin https://github.com/USERNAME/REPOSITORY.git
git push -u origin main
```

Replace `USERNAME/REPOSITORY` with the repository path. If a remote already exists, use `git remote set-url origin https://github.com/USERNAME/REPOSITORY.git` instead of `git remote add origin ...`.

## Publish with GitHub Pages

1. Open the repository's **Settings → Pages**.
2. Select **Deploy from a branch**, choose `main` and `/(root)`, then save.
3. After deployment completes, open the URL shown in Pages settings.

## Contact form

The contact form opens a prefilled email draft addressed to `graj00636@gmail.com`. It does not store submissions on a server; visitors send their message through their mail app.

## Project files

```text
index.html
experience.html
education.html
work.html
skills.html
certifications.html
gallery.html
contact.html
styles.css
portfolio.js
graphics-list.js
assets/
```

The site uses three colors: deep blue, lime and warm white. Google Fonts need an internet connection; local system fonts are used as fallbacks.


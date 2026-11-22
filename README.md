# Nazia Nishat Tonni — Portfolio (GitHub Pages)

Static site: HTML5, CSS3, vanilla JS. No build step, no backend, no paid services. Fonts (Inter) are self-hosted.

## Files and where they go
Everything goes in the **root of your repository** (not inside an extra folder):

```
index.html  about.html  experience.html  hr-projects.html
business-analysis.html  research.html  skills.html  cv.html
project-*.html          (10 planned project outlines, set to noindex)
project-template.html   (copy this to add a new project)
404.html  favicon.svg  robots.txt  sitemap.xml  .nojekyll
css/styles.css          (colours and spacing live in :root at the top)
js/main.js
assets/Nazia-Nishat-Tonni-CV.pdf   <- replace with your CV, same filename
assets/img/og-image.png     (social preview image)
assets/fonts/*.woff2
```

All links are relative, so the site works at `https://USERNAME.github.io/` and at `https://USERNAME.github.io/REPO-NAME/`.

## Deploy (step by step)
1. Create a GitHub account if needed. Click **New repository**.
2. **Root site:** name it exactly `YOUR-USERNAME.github.io`. **Project site:** any name, e.g. `portfolio`. Set it **Public**.
3. On the empty repo page choose **uploading an existing file**. Unzip this folder and drag **all its contents** in (include the hidden `.nojekyll` file if your system shows it; the site also works without it). Commit.
4. Go to **Settings → Pages**. Under **Build and deployment** set Source = **Deploy from a branch**, Branch = **main**, folder = **/ (root)**. Save.
5. Wait 1–3 minutes. The URL appears at the top of the Pages screen.

## Required edits after deploying (find and replace across all files)
| Find | Replace with |
|---|---|
| `https://tonninazianishat-lab.github.io/NaziaTonni/` | Root site: `https://USERNAME.github.io/`  Project site: `https://USERNAME.github.io/REPO-NAME/` |
| `your.email@example.com` | your real email |
| `https://www.linkedin.com/in/YOUR-LINKEDIN-HANDLE/` | your LinkedIn URL |
| `/REPO-NAME/` in `404.html` | Root site: `/`  Project site: `/REPO-NAME/` |

Tip: in GitHub press `.` on the repo to open the web editor, which has find-and-replace across files. Or use VS Code (Ctrl/Cmd+Shift+H).

## Updating content
- Edit the `.html` files directly (the GitHub pencil icon works). Yellow `[PLACEHOLDER: ...]` text marks missing facts: search the project for `PLACEHOLDER` and `editor-note` until none remain.
- Delete every `editor-note` box before publishing.
- New project: copy `project-template.html`, rename it, fill it in, remove its `noindex` meta tag, add a card on `hr-projects.html` or `business-analysis.html`, and add the URL to `sitemap.xml`.
- Change a project status by swapping the badge class: `status--planned`, `status--progress`, `status--done`, `status--employer`.
- CV: replace `assets/Nazia-Nishat-Tonni-CV.pdf` (keep the filename).

## Notes
- Project pages are set to `noindex` while they are placeholders, so search engines do not list empty pages.
- Contact is by email and LinkedIn (no form, since there is no backend).
- Check your own site with a keyboard (Tab through it) and at phone width before sharing.

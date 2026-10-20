# Titus Velpula portfolio site

A plain HTML and CSS website. No build step, no framework: open a file, change the text, save.

```
portfolio-site/
├── index.html      Home page
├── projects.html   Projects page
├── styles.css      All colours, fonts and layout
└── assets/         Your CV PDF and screenshots go here
```

## Before you publish

Search the files for `EDIT:` to find every spot that needs you:

1. **CV:** put your general CV in `assets/` named `Titus_Velpula_CV.pdf`.
2. **GitHub link:** in `index.html`, replace `YOUR-USERNAME`, or delete that line.
3. **Screenshots:** save images in `assets/` and swap each grey placeholder for an `<img>` (the comment above each group shows how).
4. **Report links:** in `projects.html`, uncomment each "View report" line and paste the link.
5. **"Updated" date** in the Currently section of `index.html`.

## Preview on your computer

Double-click `index.html` to open it in your browser.

## Editing

- **Text:** find it in `index.html` or `projects.html` and type over it.
- **Colours or fonts:** change the values at the top of `styles.css`.
- **A new project:** copy one `<article class="project">...</article>` block in `projects.html` and edit it.

## Publish free on GitHub Pages

1. Create a new **public** repository on GitHub (for example `portfolio`).
2. Upload these files (Add file > Upload files, or `git push`).
3. In the repository: **Settings > Pages**. Under "Build and deployment", set Source to **Deploy from a branch**, choose `main` and `/ (root)`, and save.
4. After a minute or two the site is live at `https://YOUR-USERNAME.github.io/portfolio/`.

From then on, every change you commit goes live within a couple of minutes.

## Connect your own domain

1. Buy the domain from any registrar.
2. In the repository: **Settings > Pages > Custom domain**, enter your domain (for example `titusvelpula.com`) and save. GitHub adds a `CNAME` file to the repo.
3. At your registrar, add the DNS records GitHub's documentation lists for your setup (A records for a root domain like `titusvelpula.com`, or a CNAME record for `www`). The exact values are in GitHub's guide: "Managing a custom domain for your GitHub Pages site".
4. Once DNS has updated, tick **Enforce HTTPS** in Settings > Pages.

## Note on the telecare PDF

The RAG project links to the PDF still hosted on the old Wix site, and the RAG notebook downloads it from the Wix Projects page. If you close the Wix site, put the PDF in `assets/`, update the link in `projects.html`, and update the notebook to download from the new address.

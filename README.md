# CASE Consultants Website

This repository contains a modern static website for **CASE Consultants**, a structural engineering consultancy specializing in earthquake, fire, blast, seismic resilience, retrofit strategies, peer review, and performance-based engineering.

## Live Website

After GitHub Pages is enabled, the site will be available at:

```text
https://YOUR-GITHUB-USERNAME.github.io/YOUR-REPOSITORY-NAME/
```

For example:

```text
https://k-mosalam.github.io/case-consultants-website/
```

## Repository Structure

```text
case-consultants-website/
│
├── index.html
├── README.md
└── assets/
    ├── images/
    └── documents/
```

At the moment, the website can work with only `index.html` and `README.md`. The `assets/` folder is optional but recommended for future images, logos, PDFs, and project graphics.

## Suggested Assets Folder

Use the `assets/` folder to keep files organized:

```text
assets/images/      project photos, logo, background images
assets/documents/   brochures, capability statements, PDFs
assets/icons/       service icons or small graphics
```

Recommended image names:

```text
assets/images/case-logo.png
assets/images/hero-structural-engineering.jpg
assets/images/project-effect-building.jpg
assets/images/project-atc-training.jpg
assets/images/project-masonry-retrofit.jpg
```

Then update image links inside `index.html`, for example:

```css
url('assets/images/hero-structural-engineering.jpg')
```

## How to Publish with GitHub Pages

1. Create a new GitHub repository, for example:

   ```text
   case-consultants-website
   ```

2. Upload these files:

   ```text
   index.html
   README.md
   ```

3. Go to the repository on GitHub.

4. Click:

   ```text
   Settings → Pages
   ```

5. Under **Build and deployment**, choose:

   ```text
   Source: Deploy from a branch
   Branch: main
   Folder: / (root)
   ```

6. Click **Save**.

7. Wait about 30–60 seconds. GitHub will show the live website link.

## Updating the Website

To update the webpage directly on GitHub:

1. Open `index.html` in the repository.
2. Click the pencil icon.
3. Make edits.
4. Scroll down and click **Commit changes**.

To update from your computer using Git:

```bash
git add index.html README.md
git commit -m "Update CASE website"
git push origin main
```

## Notes

The first version of this page uses content adapted from the current CASE Consultants website and removes unrelated placeholder/template sections. Before making this the official website, review the contact information, project descriptions, and any images for accuracy and ownership.

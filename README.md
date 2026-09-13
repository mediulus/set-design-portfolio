# Set design portfolio

A simple static site for Megan Diulus's set design work. It publishes with GitHub Pages, same idea as [Personal-Website](https://mediulus.github.io/Personal-Website/).

Live site: https://mediulus.github.io/set-design-portfolio/

## Add a project

1. Put photos or drawings in `assets/` (`.jpg`, `.png`, or `.webp`).
2. Open `index.html` and change the card title, caption, and image `src`.
3. Open the matching file in `projects/` and replace the placeholder text and image.

To add a fourth project, copy one of the files in `projects/`, then add another card on the homepage.

## Publish updates

After you change files:

```bash
git add .
git commit -m "Update portfolio work"
git push
```

GitHub Pages usually refreshes in a minute or two.

# Set design portfolio

A simple static site for Meg Diulus's set design work. It publishes with GitHub Pages, same idea as [Personal-Website](https://mediulus.github.io/Personal-Website/).

Live site: https://mediulus.github.io/set-design-portfolio/

## Preview locally

From the project folder, run:

```bash
python3 -m http.server 8000
```

Open http://localhost:8000/ in your browser, or go directly to
http://localhost:8000/projects/project-1.html for Home Invasion.
Refresh the browser after saving changes. Press Ctrl+C in the terminal to stop the server.
This is a static HTML/CSS site, so no build or package installation is needed.

## Add a project

1. Put photos or drawings in `assets/` (`.jpg`, `.png`, or `.webp`).
2. Replace an `IMAGE 1` highlight on the homepage and the matching project page.
3. To add another project, copy a file in `projects/` and add a link under the Projects dropdown in the top nav.

## Publish updates

After you change files:

```bash
git add .
git commit -m "Update portfolio work"
git push
```

GitHub Pages usually refreshes in a minute or two.

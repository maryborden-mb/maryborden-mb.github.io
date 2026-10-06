# Mary Borden Portfolio

This repository is a static Jekyll portfolio for `maryborden-mb.github.io`. It is intentionally kept at the repository root so GitHub Pages can publish it directly from the `main` branch and `/ (root)`.

## Update the site

The visible pages are Markdown files with YAML front matter:

- `index.md` — home page
- `about.md` — about page, skills, leadership, volunteer work, and selected projects
- `experience.md` — work experience
- `contact.md` — contact options

Shared structure lives in `_layouts/` and `_includes/`. Site-wide styling is in `assets/css/style.css`. Replace or expand the copy with supplied biography, projects, and additional details as desired; do not add claims that cannot be verified.

## Publish with GitHub Pages

1. Push the repository to GitHub with the default branch named `main`.
2. In the repository settings, open **Pages**.
3. Set the source to **Deploy from a branch**.
4. Choose `main` and `/ (root)`, then save.

GitHub Pages will build the Jekyll site automatically. The configured user-site URL is `https://maryborden-mb.github.io`.

## Preview locally

Install Ruby and Bundler, then install Jekyll:

```bash
gem install jekyll bundler
jekyll serve --livereload
```

Open `http://127.0.0.1:4000/`. If you use a GitHub Pages-compatible environment, use its supported Jekyll version and plugins.

## Run Lighthouse

With the site running locally, run Lighthouse against the home page:

```bash
npx lighthouse http://127.0.0.1:4000/ --view
```

Check the home page and the other navigation destinations at both a narrow viewport around 375px and a desktop viewport around 1280px. The target is at least 90 in Performance, Accessibility, Best Practices, and SEO.

## Technical choices and assumptions

- The site uses semantic HTML, Markdown content, reusable Jekyll layouts/includes, and one small CSS file.
- It has no backend, database, CMS, contact-form service, analytics tracker, or unnecessary JavaScript.
- The public email address is intentionally omitted because it was not approved.
- `maryborden-mb` is used as the GitHub username because it is part of the requested GitHub Pages hostname.
- Biography, education, and experience content are based on the supplied résumé. Skills, leadership, volunteer work, projects, and some personal details currently have clearly marked placeholders until supplied.
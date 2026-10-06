# Mary Borden Portfolio — Build Plan

## Goal

Create a publish-ready personal portfolio for `maryborden-mb.github.io` as a static Jekyll site. The repository root will contain the complete site so GitHub Pages can publish from the `main` branch and `/ (root)` without a separate build application.

## Site structure

- **Home** — concise introduction and clear paths to About, Work Experience, and Contact.
- **About** — biography and professional focus from supplied source content.
- **Work Experience** — chronological experience entries using only supplied employers, roles, dates, responsibilities, and achievements.
- **Contact** — a simple contact section without a public email address unless approved later; no backend contact form.
- Shared navigation, skip link, and footer across all pages.

## Visual direction

- Light-only theme.
- Simple, readable, aesthetically pleasing layout with no unnecessary decoration.
- Single-column responsive design for phone and desktop widths.
- Strong semantic structure and accessible color contrast.
- Readable typography with a restrained type scale and comfortable line length.

## Technical approach

- Jekyll with Markdown pages and YAML front matter.
- Reusable `_layouts` and `_includes`; content kept separate from design.
- Plain HTML and CSS with minimal JavaScript, if any.
- `_config.yml` configured for `url: "https://maryborden-mb.github.io"` and an empty `baseurl`, with URL filters used for internal links.
- SEO metadata, sitemap, favicon, and a README covering content updates, local preview, GitHub Pages publishing, and Lighthouse checks.
- No backend, database, CMS, blog, contact-form service, analytics tracker, framework app, `package.json`, or nested website folder.

## Content status

The supplied résumé is the source for the current About, Education, and Work Experience content. The LinkedIn URL was not fetched. Missing portfolio details such as projects, additional skills, and a personal introduction remain clearly marked or omitted. No achievements, employers, clients, metrics, or projects were invented.

The Contact page will not expose an email address based on the current preference.

## Assumptions to confirm

- `maryborden-mb` is the correct GitHub username because it appears in the requested GitHub Pages hostname.
- Initial portfolio content should focus on About and Work Experience; projects can be added later when supplied.
- A public email address should remain omitted unless you explicitly change that preference.

## Verification

Before delivery, verify that the repository root contains `index.md`, `_config.yml`, `_layouts`, `_includes`, assets, and all other website files; confirm internal navigation and GitHub Pages compatibility; and check the layout at 375px and 1280px widths. Run the available build and quality checks, including Lighthouse when the site is available to preview.
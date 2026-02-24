# My Personal Website

A personal academic portfolio and blog, built with [Jekyll](https://jekyllrb.com/) and the [**al-folio**](https://github.com/alshedivat/al-folio) theme. The site is hosted on [GitHub Pages](https://pages.github.com/) and serves as my online home for my writings.

---

## About The Site

This repository is taken from **al-folio** Jekyll theme. I did not build the theme from scratch—I used the template as a starting point and customized it with my own content, configuration, and styling. All credit for the underlying design, layout, and functionality goes to the al-folio project and its contributors (see [Credits &amp; Template](#credits--template) below).

What’s in this site:

- **About** — Short bio, research interests, and a bit about what I’m up to.
- **Blog** — Technical and non-technical posts (e.g. Git, OOP, PMP).
- **CV / Resume** — Experience, education, and skills (backed by `assets/json/resume.json`).
- **News** — Announcements (e.g. papers, milestones) in a compact feed.
- **Publications** — Bibliography powered by Jekyll Scholar and BibTeX.

---

## Credits & Template

This site is built on the **[al-folio](https://github.com/alshedivat/al-folio)** Jekyll theme by [Maruan Al-Shedivat](https://github.com/alshedivat) and contributors. The theme’s design is based on [***folio**](https://github.com/bogoli/-folio) by [Lia Bogoev](https://github.com/bogoli).

- **al-folio**: [https://github.com/alshedivat/al-folio](https://github.com/alshedivat/al-folio)
- **\*folio**: [https://github.com/bogoli/-folio](https://github.com/bogoli/-folio)

The footer on the live site also states: *“Powered by Jekyll with al-folio theme. Hosted by GitHub Pages.”*

I used this template to get a professional, academic-style site up quickly and then customized content and config for my own use. If you like the look and structure, consider forking [al-folio](https://github.com/alshedivat/al-folio) and following their docs for setup and customization.

---

## Tech Stack

- **Static site generator:** [Jekyll](https://jekyllrb.com/)
- **Theme:** [al-folio](https://github.com/alshedivat/al-folio) (Liquid layouts, Sass, JS)
- **Hosting:** [GitHub Pages](https://pages.github.com/)
- **Optional:** Jekyll Scholar (publications), Jekyll Feed, pagination, search, and various plugins listed in `_config.yml`

---

## Running Locally

If you want to run this site on your machine (e.g. to preview changes):

1. **Clone the repo**

   ```bash
   git clone https://github.com/Baka-14/Baka-14.github.io.git
   cd Baka-14.github.io
   ```
2. **Install Ruby and Bundler** (if not already installed). Then:

   ```bash
   bundle install
   ```
3. **Serve the site**

   ```bash
   bundle exec jekyll serve
   ```

   Open [http://localhost:4000](http://localhost:4000) in your browser.

For more detailed setup (Ruby version, plugins, Docker, etc.), see the official [al-folio documentation](https://github.com/alshedivat/al-folio#installation).

---

## Repository Structure (High Level)

- **`_config.yml`** — Site title, URL, theme options, plugins, and feature flags.
- **`_pages/`** — About, blog index, CV, 404, etc.
- **`_posts/`** — Blog posts (Markdown).
- **`_layouts/`**, **`_includes/`** — Theme layout and reusable snippets (from al-folio).
- **`_sass/`**, **`assets/`** — Styles, scripts, images, and data (e.g. `resume.json`).
- **`_projects/`**, **`_news/`** — Project and news items.

Content you’d typically edit: `_config.yml`, `_pages/about.md`, `_posts/`, `assets/json/resume.json`, and project/news files.

---

## License & Usage

The **al-folio** theme is distributed under the [MIT License](https://github.com/alshedivat/al-folio/blob/master/LICENSE). My own content (posts, copy, images) is mine; the design and code structure come from the template. If you reuse this repo as a base, keep the theme’s license and attribution in mind and credit al-folio and *folio as appropriate.

---

*This site is a customized instance of the al-folio template. Thanks to everyone who builds and maintains open-source themes like this.*

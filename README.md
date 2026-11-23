# My Portfolio

A one-page portfolio site built with Jekyll and GitHub Pages, using the **Cayman** theme.

## How to put it online (about 10 minutes, all in the browser)

1. **Create a GitHub account** at <https://github.com> if you don't already have one.
2. **Create a new repository** (the **+** in the top right → *New repository*).
   - Name it exactly **`your-username.github.io`**, using your real GitHub username.
   - Set it to **Public** and click **Create repository**.
3. **Upload the files.** On the empty repo page, click **"uploading an existing file"**.
   Drag in `_config.yml`, `index.md`, and `README.md`, then click **Commit changes**.
4. **Turn on Pages** (it's usually on already for `*.github.io` repos):
   *Settings → Pages → Build and deployment → Source: "Deploy from a branch" → Branch: `main` / `(root)` → Save.*
5. **Wait 1–2 minutes**, then visit **`https://your-username.github.io`**.
   You can follow the build in the repo's **Actions** tab (a green check means it's live).

## Editing your site

- Open any file on GitHub, click the ✏️ pencil icon, make changes, then **Commit changes**. The site rebuilds automatically within a minute or two.
- `_config.yml` holds your name and tagline (shown in the big header) and the theme.
- `index.md` holds everything else on the page, written in Markdown.
- To add a photo or résumé, upload `me.jpg` / `resume.pdf` with **Add file → Upload files**, then un-comment the matching line in `index.md`.

## Changing the theme

In `_config.yml`, swap `theme: jekyll-theme-cayman` for one of the other built-in themes listed there
(for example `jekyll-theme-minimal` or `jekyll-theme-slate`). You can preview them at
<https://pages.github.com/themes/>.

Themes from jekyllthemes.io that aren't built in can usually be used with
`remote_theme: owner/repo-name` plus `plugins: [jekyll-remote-theme]`; check the theme's own README for what it needs.

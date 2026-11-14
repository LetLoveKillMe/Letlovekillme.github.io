# Design Portfolio

A single-file portfolio site (`index.html`). No build step, no dependencies.

## Edit
- **Text and links:** open `index.html` in GitHub (pencil icon) and replace anything in [BRACKETS].
- **Accent color:** change `--accent` near the top of the file (`:root{--accent:#FCB886}`).
- **Palette:** copper `#894329`, teal `#12727D`, light teal `#5FB8C4`, peach `#FCB886`, background `#0E1416`.
- **Project images:** replace a tile's decorative `<div aria-hidden="true">...</div>` with
  `<img src="images/project-one.jpg" alt="Describe the project" style="width:100%;aspect-ratio:4/3;object-fit:cover;border-radius:4px">`
  and upload the image to an `images/` folder.
- **Links:** change each tile's `href="#work"` to its case study URL; set the email in the `mailto:` link and the social links in the footer.

## Host with GitHub Pages
1. Create a new repository and upload `index.html` and this README.
2. Settings > Pages > Source: "Deploy from a branch", branch `main`, folder `/ (root)`. Save.
3. Your site goes live at `https://<username>.github.io/<repo>/` in a minute or two.

## Custom domain
1. In Settings > Pages, enter your domain under "Custom domain" and save.
2. At your registrar, add DNS records:
   - Apex domain (`example.com`): four `A` records to `185.199.108.153`, `185.199.109.153`, `185.199.110.153`, `185.199.111.153`
   - `www`: a `CNAME` record pointing to `<username>.github.io`
3. Once DNS propagates, tick "Enforce HTTPS".

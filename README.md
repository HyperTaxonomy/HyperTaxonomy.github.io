# hypertaxonomy.org

Source for **[hypertaxonomy.org](https://hypertaxonomy.org)** — the landing site
for the HyperTaxonomy Suite of WordPress plugins.

This is the GitHub organization (user) Pages repository for the
[HyperTaxonomy org](https://github.com/HyperTaxonomy), served at the apex domain
`hypertaxonomy.org`.

## What's here

- `index.md` — the suite landing page (hero, plugin cards, ecosystem diagram, getting started).
- `vision.md` — the essay on the ideas behind the suite.
- `_config.yml` — Jekyll / Just-the-Docs configuration (apex domain, no `baseurl`, sidebar links to each plugin's docs).
- `_sass/color_schemes/hypertaxonomy.scss` — the site's color scheme (Just-the-Docs light base).
- `_sass/custom/custom.scss` — hero, plugin card, and callout styles.
- `_includes/` — `head_custom.html` (versioned favicon link, font, Mermaid label fixes), `title.html` (sidebar logo), `footer_custom.html` (license line).
- `assets/images/plugins/` — plugin icons, copied from each plugin's `.wordpress-org/icon-256x256` file.
- `favicon.ico` — the HyperTaxonomy tag icon; after replacing it, bump the `?v=` number in `_includes/head_custom.html` so browsers fetch the new one.
- `CNAME` — custom-domain marker (`hypertaxonomy.org`) used by GitHub Pages.

## How it's built

The site is a [Jekyll](https://jekyllrb.com/) site using the
[Just-the-Docs](https://just-the-docs.com/) theme (via `remote_theme`), built and
served automatically by **GitHub Pages**. Pushing to the default branch publishes
the site; there is no separate build step to run locally.

Each plugin's own documentation is a separate Just-the-Docs site published from
its own repository under a project path of this domain (for example,
`https://hypertaxonomy.org/hypertaxonomy/`).

## The plugins

| Plugin | Docs | Repository |
|--------|------|------------|
| HyperTaxonomy — core: groups, inclusions, synonyms, redirects, relevance search, enhanced archives | [Docs](https://hypertaxonomy.org/hypertaxonomy/) | [HyperTaxonomy/hypertaxonomy](https://github.com/HyperTaxonomy/hypertaxonomy) |
| TermConnect — link terms to knowledge bases & peer sites | [Docs](https://hypertaxonomy.org/termconnect/) | [HyperTaxonomy/termconnect](https://github.com/HyperTaxonomy/termconnect) |
| Social Hashtags & Mentions — inline #hashtags & @mentions as taxonomy terms | [Docs](https://hypertaxonomy.org/social-hashtags-mentions/) | [HyperTaxonomy/social-hashtags-mentions](https://github.com/HyperTaxonomy/social-hashtags-mentions) |
| As the Crow Flies — locations on terms, proximity filtering | [Docs](https://hypertaxonomy.org/as-the-crow-flies/) | [HyperTaxonomy/as-the-crow-flies](https://github.com/HyperTaxonomy/as-the-crow-flies) |
| WP-SKOS — taxonomies as SKOS linked data | [Docs](https://hypertaxonomy.org/wp-skos/) | [HyperTaxonomy/wp-skos](https://github.com/HyperTaxonomy/wp-skos) |

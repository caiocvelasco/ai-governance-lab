# AI Governance Lab

An independent, early-stage research initiative exploring how empirical evidence and quantitative methods can inform AI governance and societal impact.

The website is built with [Quarto](https://quarto.org/) and designed to remain small as research projects develop.

## Pages

- `index.qmd` — homepage, research directions, and featured project
- `research.qmd` — emerging research questions
- `projects.qmd` — research concepts and projects (currently one)
- `about.qmd` — researcher background and links

`_quarto.yml` controls the website and navigation; `styles.css` defines the visual design.

## Preview locally

Install [Quarto](https://quarto.org/docs/get-started/) and open a terminal in the repository folder:

```bash
quarto preview
```

To generate static files locally:

```bash
quarto render
```

## Publish to GitHub Pages

1. Create the public repository `ai-governance-lab` on GitHub.
2. Upload these eight source files to the repository root (include `.gitignore`).
3. On a computer with Quarto and Git installed, clone the repository and run `quarto publish gh-pages` from its root. Follow the prompts to publish the website to the `gh-pages` branch.
4. In GitHub **Settings → Pages**, set the source to **Deploy from a branch**, selecting `gh-pages` and `/ (root)` if Quarto did not set this automatically.
5. Check the temporary website URL: `https://caiocvelasco.github.io/ai-governance-lab/`.

The custom domain `aigovernancelab.org` is intentionally **not configured** here. Add the domain to GitHub Pages and update DNS separately after the temporary URL works.

## Research integrity

This is an independent initiative, not an established academic institution. Research directions are prospective, and the featured AI Governance Evidence Lab is a research concept—not a completed empirical study or validated tool. No institutional endorsement is implied.

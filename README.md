# AI Governance Lab

An independent, early-stage **research and technology initiative** at the intersection of artificial intelligence, human decision-making, governance, and public policy.

**Mission:** Advancing governance and public policy through the design, development, and rigorous evaluation of AI systems.

The Lab explores two complementary pillars: **Governance of AI** and **AI for Governance**. Its integrated approach is **Design → Develop → Evaluate**.

The website is built with [Quarto](https://quarto.org/), uses a small set of static pages, and deliberately distinguishes aspirations and research concepts from validated work or established services.

Projects are individual initiatives, classified by type (research or applied), relevant pillars, and stage (e.g., concept or working prototype). Research ideas are potential directions, not necessarily active projects.

## Pages

- `index.qmd` — mission, two pillars, lifecycle, and link to projects
- `research.qmd` — research questions and illustrative use cases
- `projects.qmd` — research and applied projects, their pillars, application areas, and development stages
- `about.qmd` — background, mission, and collaboration information
- `_quarto.yml` — navigation and website settings
- `styles.css` — visual styles
- `.gitignore` — generated/local files excluded from version control

## Portrait

`about.qmd` refers to `images/caio_ucla.JPG`. Copy the photograph into that location, preserving capitalization. The image is **not included** in this ZIP because it was not uploaded.

## Preview locally

Install [Quarto](https://quarto.org/docs/get-started/) and run from the repository root:

```bash
quarto preview
```

Build with:

```bash
quarto render
```

## Publish

If your existing GitHub Pages deployment is managed by Quarto, run `quarto publish gh-pages` from the repository root and follow its prompts. Keep your existing GitHub Pages custom-domain configuration for [aigovernancelab.org](https://aigovernancelab.org/); this package does not change DNS or hosting settings. Confirm the site configuration before publishing.

## Research integrity

This is an independent early-stage initiative. Current projects are at the concept stage, not deployed products, completed empirical studies, or validated assessment methods. No institutional affiliation, endorsement, or partnership is implied.

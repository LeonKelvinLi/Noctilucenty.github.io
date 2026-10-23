# Leon Kelvin Li — Lead Software Engineer & Product Builder

Personal portfolio at [noctilucenty.github.io](https://noctilucenty.github.io/), focused on substantial product, AI, research and client systems.

The default gallery features **LOQOL & Charlie AI, Curio, Scenara, ATLAS, Mingtu and ALLCPR Site Intelligence**. The All work filter adds BEASTY PAGES, Curio Automation, Continuity and the ONPECY AI Lab proposal. Smaller sites, sticker packs and earlier experiments are omitted.

Project scope is expandable, with clear boundaries for research, educational prototypes, archived simulations and development in progress. Experience is grouped by company, with LOQOL first: Software Engineer (Aug–Sep 2026), then Lead Software Engineer (Oct 2026–present). GOSVEA shows two entries: Software Engineer Intern (Jun 2026), then Product Engineer & Project Technical Lead — USJOPU (Jul 2026–present). The description specifies that project-level technical leadership for USJOPU began in October 2026. Each role includes relevant skills. The downloadable resume remains one page and uses the same role progression.

## Design and assets

The original animated portfolio UI is restored, including its typography, gradient accents, project-card layout, navigation, cursor and background effects. Updated career content, the curated projects, generated cover artwork and one-page resume are retained. It has no framework or runtime dependencies.

The ten project covers in `assets/projects/` were created with GPT image generation as **concept artwork**, not product screenshots. They are compressed WebP files with explicit dimensions and descriptive alternative text. The hero image loads first; gallery images load lazily.

## Local development

```sh
python3 -m http.server 5298
```

Open `http://127.0.0.1:5298/`. Run the repository checks with `npm test`.

GitHub Pages publishes from the repository's main branch, root directory.

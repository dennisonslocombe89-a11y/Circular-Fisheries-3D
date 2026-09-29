# Circular Fisheries 3D

Interactive evidence-led model for the Grenada Co-operative League Limited circular fisheries grant project.

## Current model

The single-file `index.html` application presents:

- four project-supported fisheries facilities;
- landing and catch handling;
- solar-supported cold-chain infrastructure;
- processing and value addition;
- circular use of suitable fisheries by-products;
- buyer and market linkages;
- training, mentoring and the Iceland study tour;
- cooperative governance, social protection, monitoring and knowledge sharing.

## Evidence boundary

Counts and activities are based primarily on:

- `ACTIVITIES PLAN 0008 Final Sept 15.docx`
- `Logical framework 0008 Revised Sept 15.docx`
- `2.1.6.-Budget-1_0008 Revised Sept 17.xlsx`

Other supplied reports, minutes, the transcript, action plan and GEF SGP proposal provide context. The future GEF SGP proposal is not treated as proof of delivery under the current EUCaN action.

Named facilities in the implementation plan are Petite Martinique, Carriacou, Carenage and Soubise. Building forms, dimensions, equipment placement and the exact package at each location are illustrative until the project completes the four site assessments and approves the site-specific infrastructure plans.

## Run

Open `index.html` through a static web server. The Three.js modules load from jsDelivr.

Example:

```bash
python -m http.server 8000
```

Then open `http://localhost:8000`.

## Deployment

This repository is ready for a static Cloudflare Pages deployment with no build command and `/` as the output directory.

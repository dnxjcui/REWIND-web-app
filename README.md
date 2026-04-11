# REWIND

**REWIND: An Immersive AR Surgical Training Tool** — Vanderbilt BME Senior Design project site (static HTML).

**Team:** Victor Dunagan, Nathan Hammond, Nick Cui, Audrey Hardtke, Aaron Falconer  
**Affiliations:** Department of Biomedical Engineering; Department of Electrical Engineering, Vanderbilt University, Nashville, TN  
**Mentors:** Professor Goldfarb, Professor Jie Ying Wu

Project materials in this repository:

- [`POSTER.pdf`](POSTER.pdf) — in-progress poster  
- [`Project Proposal.pdf`](Project%20Proposal.pdf) — senior design proposal  

## Deploying on Vercel

This site is **static** (no `package.json`, no build step). In the Vercel new-project flow:

1. **Framework Preset:** **Other** (or “No Framework” if that is what the UI shows).
2. **Root Directory:** repository root (where `index.html` lives).
3. **Build Command:** leave **empty**.
4. **Output Directory:** leave **empty** or default.
5. **Install Command:** leave **empty**.

Vercel will serve `index.html` at `/` and static assets under `/static/...`. No `vercel.json` is required unless you later add redirects, headers, or rewrites.

## Hero and carousel media

The teaser and carousel use [`static/images/rewind-poster.svg`](static/images/rewind-poster.svg) as a **placeholder**. For a sharper hero image, export a PNG from `POSTER.pdf` and replace or supplement that asset, then update the `src` attributes in `index.html` if the filename changes.

## Website license

Page structure derives from the [Nerfies project page](https://github.com/nerfies/nerfies.github.io) (CC BY-SA 4.0). REWIND-specific text and branding are the project team’s; retain appropriate attribution for the template as noted in the site footer.

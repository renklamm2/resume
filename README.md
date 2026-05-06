# Lauren M. Klamm &mdash; Paraprofessional Resume

Live, shareable HTML resume for **Lauren M. Klamm**, targeted to the Paraprofessional role with **Stafford County Public Schools**.

Authored by Lauren Klamm. Last updated **05/05/2026**.

## Pages

| File | Purpose |
| --- | --- |
| `index.html` | Main resume. Includes a **Print / Save as PDF** button. |
| `performance-data.html` | SOL &amp; intervention growth charts (Reading, Math, Engagement). |
| `student-impact.html` | Individual student impact profiles with per-student charts. |

All three pages are static HTML &mdash; open `index.html` directly in a browser, or host the folder on GitHub Pages and share the link.

## PDF download

The resume page (`index.html`) and both data pages include a **Print / Save as PDF** button that uses the browser&rsquo;s native print dialog. Choose &ldquo;Save as PDF&rdquo; as the destination.

Print styles are tuned for US Letter at 0.4&Prime; margins.

## Hosting on GitHub Pages

```bash
# from the repo root
git init
git add .
git commit -m "Lauren Klamm resume - 05/05/2026"
git branch -M main
git remote add origin https://github.com/renklamm2/resume.git
git push -u origin main
```

Then in the GitHub repo: **Settings &rarr; Pages &rarr; Source: `main` / root**. Public URL will be:

```
https://renklamm2.github.io/resume/
```

The chart pages will be linked from the resume header and footer and live at:

```
https://renklamm2.github.io/resume/performance-data.html
https://renklamm2.github.io/resume/student-impact.html
```

## A note on the data

All charts on `performance-data.html` and `student-impact.html` are **illustrative composites** built from the published assessment cadences for Amplify mCLASS, DIBELS 8, and VALLS. They communicate the *shape* of the intervention work &mdash; not records of individual students, whose data is protected under FERPA.

## Tech

- Pure HTML / CSS, no build step
- [Chart.js 4.4](https://www.chartjs.org/) via CDN for visualizations
- Inter font via Google Fonts
- Print stylesheet for clean PDF export

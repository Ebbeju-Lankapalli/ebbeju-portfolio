# Ebbeju Lankapalli — Portfolio Demo

## Run
Open `index.html` in Chrome, Safari, or Firefox. No npm installation required.

Optional local server (recommended):

```bash
cd ebbeju_portfolio_demo
python3 -m http.server 8000
```

Open http://localhost:8000 in your browser.

## Included
- Dark responsive landing page inspired by the reference screenshot
- Placeholder portrait (remote sample photo; replace with your own)
- Three featured project cards with animated **concept** previews, not fabricated demo videos
- Filterable ML / DL / GenAI / Agentic AI project grid, including subcategories
- Search, dynamic project details, verified-link GitHub buttons
- GitHub API load of public non-fork repositories (fallback to previously shared names if offline)
- All CSS and JS embedded in index.html

## Important limitations
- GitHub API may return a different count than the previously shared 38 (public, non-fork repos only).
- Project categories are derived from repository names; review classifications manually.
- Descriptions, problem statements, methodology and performance sections are demo scaffolding, not verified research results.
- No actual project demo videos were supplied. Replace concept previews with real recordings.
- Portrait is a stock placeholder; no real image of Ebbeju was provided.
- Resume, LinkedIn, email, and live app links are omitted until verified URLs are supplied.

## Edit
Edit the `known`, `special`, and `featuredNames` variables near the end of `index.html`.
The GitHub profile used is https://github.com/Ebbeju-Lankapalli.


## Personalized sections
This version includes Ebbeju's supplied portrait, About, Education, NxtWave learning, and Contact sections.
The skills/project descriptions in the original demo remain draft summaries; verify them against source repositories before publishing.
Run: `python3 -m http.server 8000` from this folder, then open http://localhost:8000.

Updated: Education (2023–2027, CGPA 8.2), resume-derived skills, View/Download Resume. The college icon is a placeholder, not an official logo.

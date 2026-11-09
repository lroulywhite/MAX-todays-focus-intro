# Today's Focus Interactive Walkthrough

An interactive, click-through walkthrough of the **Today's Focus** page in Momentus Enterprise. It guides users through each section of the page with a spotlight on the screenshot and a step-by-step side panel.

**Version:** v6 (blue highlight)

## What it covers

1. Your landing page (overview)
2. Decision Queue
3. My Tasks
4. New Opportunities
5. Performance
6. Upcoming Meetings
7. Calendar Preview
8. Sales Funnel
9. Putting it together (a simple daily check)

## Run it

It is a single self-contained HTML file (the screenshot is embedded), so there is no build step.

- **Locally:** open `index.html` in any modern browser.
- **GitHub Pages:** Settings → Pages → Deploy from a branch → `main` / root. The walkthrough will be served at `https://<org-or-user>.github.io/<repo-name>/`.

## Navigation

- **Next / Back** buttons, or click the step dots
- Click a highlighted area on the screenshot to jump to that section

## Notes

- Fonts load from Google Fonts (Plus Jakarta Sans) and fall back to system fonts offline.
- The embedded screenshot is Momentus product UI. Do not edit or recreate it; replace it only with an approved capture.
- To update step text, edit the `STEPS` array in `index.html`.

## Files

| File | Purpose |
| --- | --- |
| `index.html` | The walkthrough (HTML, CSS, JS, embedded screenshot) |
| `.nojekyll` | Tells GitHub Pages to serve the files as-is |
| `.gitignore` | Standard ignores |

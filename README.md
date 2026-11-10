# MBA Course Compass · Spring 2027

A responsive bilingual course planner with two clearly separated entries:

- **Bi-Weekly courses** — 12 home-cohort / global offerings.
- **Choose classes together** — 29 non-Bi-Weekly electives for cross-cohort planning.

Search and filter courses, save favourites, build a shortlist across catalogs, check timetable overlaps, browse a monthly calendar, copy a shared-plan link, and download CSV or ICS files. Preferences remain in the visitor's browser. Shared links contain selected course codes only.

## Data

Based on the two Spring 2027 tentative schedules dated **10 November 2026**. There are **41 offerings**, **268 teaching blocks**, and **43 overlapping course pairs**. Chinese titles are explanatory translations. Date ranges are expanded by the weekday specified in the source files.

This independent planner does not register courses. Exact Weekly / Full-Time home cohorts, shared quotas, prerequisites, hybrid attendance rules and credit limits require MBAO / SIS confirmation. Original inconsistent exam/add-drop years are flagged, not silently confirmed. Global programs with unknown sessions are excluded from overlap checks and calendar exports.

## Running

No build or external dependencies. Serve this directory over HTTP, for example:

```sh
python3 -m http.server 4173
```

Publish to GitHub Pages from `main` / root. The app includes a manifest and a small service worker for repeat offline visits. Update the service-worker cache version when shipping a new data release.

No school logo or official affiliation is claimed.

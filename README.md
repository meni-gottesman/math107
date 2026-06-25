# MATH 107 — Data, Functions & Graphs

An interactive, single-file study workspace for Occidental College **MATH 107
(Data, Functions & Graphs)**, a precalculus course.

**Live site:** https://meni-gottesman.github.io/math107

## What's inside
- **An Algebra Toolkit on-ramp + 7 units / 32 subtopics** — each with a lesson cheat-sheet, ranked videos, a
  full worksheet, and a worked answer key.
- **10 assessments** — a diagnostic, seven unit tests, a midterm (Units 1–4),
  and a cumulative final, each with a rubric and answer key.
- Progress ring, per-topic notes, topic search, and dark mode — all saved in the
  browser (`localStorage`), with an in-memory fallback so it also works inside
  sandboxed previews.

## How it works
Everything lives in `index.html` — no build step and nothing installed on the
page. KaTeX (math rendering) and Google Fonts load from CDNs at runtime. All
course content is one `COURSE` object near the bottom of the file; the nav,
search, and progress denominator all derive from it.

## Run locally
Open `index.html` directly in a browser, or serve the folder:

    python3 -m http.server 8000

then visit http://localhost:8000.

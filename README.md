# UCP Student Clubs Portal

A simple informational website for the University of Central Punjab (UCP) Student Clubs Portal, developed collaboratively using Git and GitHub as part of DevOps Assignment 01 — Spring 2026.

## Project Structure

```
student-portfolio/
├── .gitignore
├── README.md
├── src/
│   ├── index.html         # Home page (Abdul Mateen [Team Lead])
│   ├── clubs.html         # Club Categories (M. Asfand Yar)
│   ├── events.html        # Upcoming Events (M. Ahmad)
│   ├── join.html          # How to Join (Haroon Ashar)
│   └── highlights.html    # Club Highlights (M. Hashaam)
└── styles/
    └── style.css          # Shared stylesheet
```

## Pages

| Page | Description | Responsible |
|------|-------------|-------------|
| `index.html` | Landing page introducing the portal | Abdul Mateen (Team Lead) |
| `clubs.html` | Club categories with filter functionality | M. Asfand Yar |
| `events.html` | Upcoming events calendar | M. Ahmad |
| `join.html` | Step-by-step membership guide | Haroon Ashar |
| `highlights.html` | Achievements and member spotlights | M. Hashaam |

## Branching Strategy

- `main` / `production` — production-ready code only (3 approvals required)
- `develop` — active development integration branch (2 approvals required)
- `release/v1.0` — release candidate for QA testing
- `feature/<page-name>` — individual feature branches per team member

## How to Run

Open any `.html` file in the `src/` folder directly in a web browser. No build tools required.

## Team

See Table 1 in the submitted assignment document.

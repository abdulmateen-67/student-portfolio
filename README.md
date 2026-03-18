# UCP Student Clubs Portal

A simple informational website for the University of Central Punjab (UCP) Student Clubs Portal, developed collaboratively using Git and GitHub as part of DevOps Assignment 01 — Spring 2026.

## Project Structure

```
student-portfolio/
├── .gitignore
├── README.md
├── src/
│   ├── index.html         # Home page (Team Lead)
│   ├── clubs.html         # Club Categories (Member 1)
│   ├── events.html        # Upcoming Events (Member 2)
│   ├── join.html          # How to Join (Member 3)
│   └── highlights.html    # Club Highlights (Member 4)
└── styles/
    └── style.css          # Shared stylesheet
```

## Pages

| Page | Description | Responsible |
|------|-------------|-------------|
| `index.html` | Landing page introducing the portal | Team Lead |
| `clubs.html` | Club categories with filter functionality | Member 1 |
| `events.html` | Upcoming events calendar | Member 2 |
| `join.html` | Step-by-step membership guide | Member 3 |
| `highlights.html` | Achievements and member spotlights | Member 4 |

## Branching Strategy

- `main` / `production` — production-ready code only (3 approvals required)
- `develop` — active development integration branch (2 approvals required)
- `release/v1.0` — release candidate for QA testing
- `feature/<page-name>` — individual feature branches per team member

## How to Run

Open any `.html` file in the `src/` folder directly in a web browser. No build tools required.

## Team

See Table 1 in the submitted assignment document.

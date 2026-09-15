# Purl AI

An AI request harness that reduces the water and energy cost of AI usage through search-first caching, local prompt optimization, and complexity-based model routing.

## Project structure

```
purl-ai/
├── ai-core/        # AI harness: search layer, optimization layer, routing layer (Aafiya)
├── fullstack/       # Frontend + backend implementation (Maryam)
│   ├── frontend/
│   └── backend/
├── testing/         # Unit + integration tests (shared across the team)
├── security/         # Authentication, rate limiting, prompt injection protection (Shifa)
└── production/       # Deployment and production configs (Falak)
```

## Team ownership

| Folder | Owner | Scope |
|---|---|---|
| `ai-core/` | Aafiya | Search layer, optimization layer, model routing, end to end |
| `fullstack/` | Maryam | Frontend, backend, databases |
| `testing/` | Shared | Unit and integration tests for all layers |
| `security/` | Shifa | Auth, rate limiting, prompt injection protection |
| `production/` | Falak | Deployment, keeping frontend and backend live |

## Branch and merge authority

- `main` and `aafia_dev` are protected branches. No one pushes to them directly.
- Everyone branches off `aafia_dev`, opens a pull request, and waits for review.
- **Aafiya has final review and merge authority across the entire repository**, regardless of which folder a PR touches. See `.github/CODEOWNERS`.
- Teammates own their folder for day-to-day work, but nothing merges into `aafia_dev` or `main` without Aafiya's approval.

## Getting started

This is currently a blank template. Tech stack per folder is declared in each folder's own `README.md` and dependency file. Implementation is added stepwise, folder by folder.
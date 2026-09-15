# testing

Shared across the team. Every folder's logic gets its tests here, mirroring the source structure.

## Tech stack

- pytest (Python unit + integration tests)
- Locust (load testing, added closer to demo)

## Structure

```
testing/
├── unit/          # one test file per module, mirrors ai-core/ and fullstack/backend/
└── integration/   # full pipeline tests, hit the running API
```

Blank template. Tests are added alongside each implementation step.

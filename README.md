# Bob Onboarding Pipeline — landing page

Static landing page for the IBM Bob 2.0 Hackathon entry: one `/onboard` command in IBM Bob IDE that turns a real codebase into a personalised onboarding pack (PDF, narrated tour video, one file per issue, and a context folder for the newcomer's own Bob).

- Pipeline source: https://github.com/arisyasyahirah/NORTHWIND-LABS-bob2.0-hackathon-submission-
- Demo codebase: https://github.com/arisyasyahirah/NORTHWIND-LABS

## Contents

- `index.html` — the whole page (no build step, no JS)
- `assets/` — the real run's PDF, context zip, tour video, screen recordings (H.264, CRF 28), and screenshots
- `research/` — the research notes behind the problem statement and the time/cost estimate

## Run locally

```
python3 -m http.server 8000
```

Deployed on Vercel as a static site.

# app-review-triage website

The landing page for [app-review-triage](https://github.com/Ying8109/app-review-triage), a Claude Code
skill that turns app-store reviews into a ranked "what to fix first" report.

| Path | What it is |
|---|---|
| `index.html` | The landing page |
| `sample-report.html` | A sample report from a real run (Todoist on Google Play) |
| `assets/` | Intro video, its poster frame, and the report thumbnail |
| `netlify.toml` | Netlify settings: no build step, publish this folder |

Plain static HTML, no build. To preview locally:

```bash
python3 -m http.server 8000
```

The skill's code, tests, and docs live in the main repo.

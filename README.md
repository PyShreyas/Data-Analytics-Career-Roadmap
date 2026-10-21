# Analytics Navigator

A personal data analytics skills assessment and career-roadmap web app. It is a lightweight static site that can be hosted with GitHub Pages without a build step.

## Features

- 15-question diagnostic across SQL, Power BI/DAX, data modelling, Python, statistics, data engineering, cloud and portfolio fundamentals.
- Overall proficiency band, domain-level scores and answer explanations.
- Roadmap checklist with assessment-aware ordering.
- Built-in study mentor for Cloud/Data Architect, Data Scientist, and BI/Analytics Engineer paths.
- Local browser storage and JSON export/import.
- Responsive desktop and mobile layout.

## Deploy with GitHub Pages

1. Open Settings → Pages in this repository.
2. Choose GitHub Actions as the deployment source.
3. Ensure the default branch is main.
4. Push a commit to main or manually run the Deploy Analytics Navigator to GitHub Pages workflow under Actions.
5. When the workflow succeeds, open Settings → Pages for the published URL. It is expected to be https://pyshreyas.github.io/Data-Analytics-Career-Roadmap/ if the repository name and account remain unchanged.

## Local use

Open index.html in a modern browser. No package installation is required.

## Privacy and AI

Assessment answers and progress are stored in this browser's local storage and are not synced across devices. Use Settings & data to export or import a JSON backup.

The study mentor currently uses built-in rule-based recommendations; it does not call an external AI model. Do not put a private API key in a public repository or static site. For a production AI mentor, add a server-side API or serverless function, store secrets in deployment environment variables, and implement authentication, rate limits, input validation and privacy controls.

## Roadmap scope

This assessment is a short self-check, not a validated psychometric test or professional certification. Verify progress through real project outcomes and repeated assessments.

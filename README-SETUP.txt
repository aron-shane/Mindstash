Mindstash Daily Content Update (free setup)

Included:
- index.html: enhanced app wired to fetch daily.json without browser caching.
- daily-pool.json: 20 original bite-sized insights, rotating across topics.
- .github/workflows/daily-insight.yml: GitHub Actions scheduled workflow (daily at 00:07 UTC) that selects the day's bite and commits daily.json.
- daily.json: sample current daily feed.

Setup:
1. Replace the repository's index.html with this included index.html.
2. Upload daily-pool.json and daily.json to the repository root.
3. Upload daily-insight.yml into .github/workflows/ (create folders if needed).
4. In GitHub repository Settings > Actions > General, ensure workflows can read and write repository contents (Read and write permissions).
5. In Actions tab, run “Publish daily Mindstash insight” once via Run workflow to test.
6. GitHub Pages serves the updated static site. No paid API key or hosting subscription is required.

Important: this no-API version rotates through 20 authored lessons and will repeat after 20 days. It is free, but it does not invent endless fresh content. A fully novel AI-generated daily feed needs an external AI service; free tiers may have limits and are not guaranteed.

Mindstash — Free Daily Content + PWA Enhancement

Included files:
- index.html: Mindstash app with daily feed, saved/learned tracking, reflection, search, category filters, progress dashboard, and Random Insight control.
- daily-pool.json: original bite-sized insight pool used by the daily publishing workflow.
- daily.json: current daily insight feed.
- .github/workflows/daily-insight.yml: scheduled workflow that selects and publishes one insight daily.
- manifest.json and icons/icon.svg: installable Progressive Web App metadata and icon.
- sw.js: service worker for shell caching and offline fallback for the daily insight feed.

Deploy to GitHub Pages (free):
1. Upload/replace index.html in the repository root.
2. Upload daily-pool.json and daily.json to the repository root.
3. Upload manifest.json and sw.js to the repository root.
4. Upload icons/icon.svg, preserving the icons folder.
5. Upload .github/workflows/daily-insight.yml into that exact folder path.
6. Repository Settings > Actions > General: set workflow permissions to Read and write permissions, then Save.
7. In Actions, run “Publish daily Mindstash insight” once to test the workflow.
8. Wait for GitHub Pages to publish the update. Open the site over HTTPS.

PWA / offline:
- On supported browsers, Mindstash can be installed from the browser's install prompt/menu.
- The app shell and last cached daily feed are available offline after the site has been visited online once.
- Favorites, learned ideas, streak data, and reflections are stored locally in the browser on that device; they are not synced across devices.

Content limitation:
This free no-API configuration rotates through the authored insight pool and repeats after the pool is exhausted. It does not generate infinite novel AI content. No paid API or hosting is required.


MICROLEARNING UPGRADE
This update adds 20 original ideas (IDs 31-50), horizontal visual swipe cards, local preference-based topic ranking from saved/learned ideas, and a user-named collection action in the reader. Collections and personalization are stored locally in this browser. No paid API is used.

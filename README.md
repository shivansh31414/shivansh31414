# Dynamic GitHub Stats

![GitHub Readme Stats](https://github-readme-stats.vercel.app/api?username=shivansh31414&show_icons=true&hide_title=true&count_private=true&include_all_commits=true&cache_seconds=1800)
![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=shivansh31414&layout=compact&cache_seconds=1800)
![GitHub Commits](https://img.shields.io/github/commit-activity/y/shivansh31414/shivansh31414?style=flat-square)
![GitHub Activity Graph](https://github-readme-activity-graph.vercel.app/graph?username=shivansh31414&theme=react-dark&area=true&hide_border=true)

## What changed (and why)

### 1) Switched to fully dynamic stats cards
- **GitHub Readme Stats** now pulls your profile stats dynamically.
- Added:
  - `include_all_commits=true` to avoid undercounting due to default-branch-only behavior.
  - `count_private=true` so private contributions can be included (subject to what GitHub allows to be shown).

### 2) Languages card is dynamic
- **Top Langs** updates automatically as your public repos change.

### 3) Commit activity badge uses GitHub’s repo activity
- The commit badge is based on repo commit activity over the last year.
- This is *dynamic* and refreshes as commits land.

### 4) Replaced the activity graph endpoint
- The previous activity graph service often breaks or shows stale data.
- Updated to a maintained endpoint with explicit rendering options.

### 5) Controlled caching for freshness
- `cache_seconds=1800` (30 minutes) reduces staleness while keeping badge services responsive.

> Note on “total commits”: There is no perfect public badge that shows an always-accurate total commits across *all* repos (especially private). The cards above are the most reliable dynamic option within GitHub’s and badge providers’ constraints.
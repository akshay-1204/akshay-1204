# GitHub Profile Explorer

Search any GitHub username and see their profile, aggregated stats, language and star charts, a commit heatmap, a repo browser with README preview, and recent public activity.

Share a profile with a link such as `?user=torvalds`.

## Features
- Profile card: avatar, bio, company, location, blog, X/Twitter, followers, following, repos, join date
- Stats: total stars, forks, watchers, open issues, language donut, repos-by-stars chart
- Repo browser: search, sort (stars / updated / name), language filter, README drawer
- Activity feed and commit heatmap from public events (about 90 days)
- Quick-try profiles, recent searches, loading skeletons, not-found and rate-limit states
- Light/dark theme, keyboard friendly (press `/` to focus search)

## Run locally
Open `index.html` in a browser. No build step and no dependencies.

## Deploy on GitHub Pages
1. Push this repo to GitHub.
2. Go to **Settings → Pages** and set **Source** to **GitHub Actions**.
3. The included workflow publishes the site on every push to `main`.

Your site will be at `https://<your-username>.github.io/<repo-name>/`.

## Rate limit
Anonymous GitHub API access allows 60 requests per hour. Click **Token** in the header to add a personal access token (stored only in your browser) and raise it to 5,000 per hour. A token with no scopes is enough.

## License
MIT

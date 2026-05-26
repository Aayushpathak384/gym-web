# gym-web

Netlify deploy instructions

- Team: Aayush
- Account: Aayushpathak384
- Project name: gym-websitehi
- Branch to deploy: `main`
- Base directory: (leave empty)
- Build command: (none)
- Publish directory: `.`
- Functions directory: `netlify/functions` (optional)

Steps to deploy

1. Commit and push the repo to GitHub (or your Git provider):

```bash
git add netlify.toml README.md
git commit -m "Add Netlify config and deploy instructions"
git push origin main
```

2. In Netlify web UI: Create new site → Import from Git → choose your repo →
	Team: Aayush, Account: Aayushpathak384, Project name: `gym-websitehi`, Branch: `main`, Publish directory: `.`

Or use Netlify CLI to deploy directly from this folder:

```bash
npm install -g netlify-cli
netlify login
netlify deploy --prod --dir=.
```

No environment variables or build steps are required for this static site.


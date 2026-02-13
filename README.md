# Valentine Website (Jen ❤️)

This is a simple multi-page static site made for Valentine’s Day.

## Pages
- `index.html` — Happy Valentine’s Day + countdown to 12:00 AM (Singapore)
- `memories.html` — photo memories grid
- `note.html` — final note + play a song
- `bemyvalentine.html` — throwback “Will you be my valentine?” page

## Publish on GitHub Pages (fast)
1) Create a new GitHub repo (public) e.g. `valentine-jen`
2) Upload all files in this folder (or push with git)

### Option A — Upload ZIP
- GitHub → Add file → Upload files → drag everything inside this folder → Commit

### Option B — Git commands
```bash
git init
git add .
git commit -m "valentine site"
git branch -M main
git remote add origin https://github.com/<your-username>/<repo>.git
git push -u origin main
```

3) Enable Pages:
- Repo → **Settings** → **Pages**
- Source: **Deploy from a branch**
- Branch: **main** / **root**
- Save

Your site URL will be:
`https://<your-username>.github.io/<repo>/`

Tip: if you want it as `https://<your-username>.github.io/` then name the repo:
`<your-username>.github.io`

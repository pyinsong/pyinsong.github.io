# pyinsong.github.io

Personal portfolio site for Yinsong Zhu — Data Scientist in financial services / credit card industry.

**Live site:** https://pyinsong.github.io

## To deploy

```bash
# 1. Create a new GitHub repo named exactly: pyinsong.github.io
# 2. Push this folder to the main branch
git init
git add .
git commit -m "Initial portfolio site"
git remote add origin https://github.com/pyinsong/pyinsong.github.io.git
git push -u origin main
# GitHub Pages auto-deploys from main for user pages (username.github.io repos)
```

## What to customize

All placeholders are wrapped in `[brackets]` — search for `[` in `index.html` to find them all.

| Placeholder | What to fill in |
|---|---|
| `[Your Degree]` | e.g., M.S. Statistics |
| `[Your University]` | Cornell, etc. |
| `[Your Current Company]` | Your employer |
| `[Previous Company]` | Prior employer |
| `[your-linkedin]` | LinkedIn slug |
| Photo `👤` div | Replace with `<img src="photo.jpg">` |
| Resume link | Update `onclick` in nav to your PDF URL |
| Project bullets | Fill in real metrics |

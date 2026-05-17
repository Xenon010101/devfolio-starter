# Contributing to DevFolio Starter

Thank you for your interest in contributing! This project is part of **GSSoC 2026** and welcomes contributors of all experience levels.

---

## 🛠️ Local Setup

1. Fork this repository
2. Clone your fork: `git clone https://github.com/duduboiii123/devfolio-starter.git`
3. Open `index.html` in your browser or use VS Code's Live Server extension

No build tools, no npm install — it's pure HTML/CSS/JS. ✅

---

## 🔀 Git Workflow

```bash
# 1. Create a branch (use a descriptive name)
git checkout -b fix/issue-7-hamburger-toggle

# 2. Make your changes

# 3. Stage and commit
git add .
git commit -m "fix: hamburger menu toggle missing open class argument"

# 4. Push to your fork
git push origin fix/issue-7-hamburger-toggle

# 5. Open a Pull Request on GitHub
```

---

## ✅ PR Checklist

Before submitting, make sure:

- [ ] The bug/feature is clearly described in the PR body
- [ ] You've referenced the related issue number (`Fixes #7`)
- [ ] Your changes are tested in a browser
- [ ] You haven't introduced new bugs
- [ ] Code style is consistent with the existing codebase

---

## 📝 Commit Message Format

Use this format for your commits:

```
type: short description

Examples:
fix: viewport meta content attribute restored
feat: add dark/light mode toggle button
docs: update README with setup instructions
style: align skill bar widths to match design
```

---

## 🏷️ GSSoC 2026 — Labels & Points

Every merged PR earns points on the GSSoC leaderboard. Points are calculated from labels the Project Admin applies **after** merging. Here's how it works:

### Labels the Project Admin adds on merge

| Label | What it means |
|---|---|
| `gssoc:approved` | **Required on every merged PR** — gives 50 base points |
| `level:beginner` | Easy fix — +20 pts |
| `level:intermediate` | Medium complexity — +35 pts |
| `level:advanced` | Hard/architectural — +55 pts |
| `type:bug` | Bug fix — +10 pts |
| `type:feature` | New feature — +10 pts |
| `type:docs` | Documentation — +5 pts |
| `type:accessibility` | A11y improvement — +15 pts |
| `quality:clean` | Well-written, neat PR — ×1.2 multiplier |
| `quality:exceptional` | Outstanding contribution — ×1.5 multiplier |

### Example point calculation

A beginner bug fix with clean code:
```
(50 base + 20 difficulty + 10 type:bug) × 1.2 quality = 96 pts
```

### What this means for you as a contributor

- Fix bugs listed in the README issues table
- Write clean, well-explained PRs — quality labels are at the admin's discretion
- One issue per PR — don't bundle multiple fixes
- Always reference the issue: `Fixes #3`

---

## 🤝 Code of Conduct

- Be kind and constructive in reviews and comments
- Help beginners — everyone starts somewhere
- Avoid dismissive language

---

Happy hacking! 🚀

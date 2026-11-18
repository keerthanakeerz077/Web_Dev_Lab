# P3 — Feature-branch Git workflow

**Aim:** Work on a new branch instead of changing main directly.

```bash
git switch main
git pull
git switch -c feature/about-page
```

Make a small change to your portfolio, then:
```bash
git status
git add .
git commit -m "Add about page"
git push -u origin feature/about-page
```

On GitHub, create a pull request from `feature/about-page` to `main`. Check the changes and merge it.

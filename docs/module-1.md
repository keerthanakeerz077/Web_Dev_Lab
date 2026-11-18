# Module 1 — Terminal, Git & GitHub

## P1: Project folder and terminal navigation
Open Terminal and use:
```bash
pwd                 # show current folder
ls                  # list files
mkdir web-lab       # create a project folder
cd web-lab          # enter it
cd ..               # move one folder up
code .              # open current folder in VS Code (if installed)
```

## P2: Portfolio repository and an initial commit
From inside the project folder:
```bash
git init
git add .
git commit -m "Initial portfolio commit"
git branch -M main
git remote add origin https://github.com/keerthanakeerz077/Web_Dev_Lab.git
git push -u origin main
```
If the remote already exists, check it with `git remote -v` instead of adding it again.

## P3: Feature-branch Git workflow
```bash
git switch -c feature/my-update
# make and save a change
git status
git add .
git commit -m "Add portfolio update"
git push -u origin feature/my-update
```
Open a pull request on GitHub to review and merge the feature branch into main.

## P4: GitHub README and version tags
The root README links to every practical. Mark a completed milestone with:
```bash
git tag -a v1.0.0 -m "Web Development I practicals"
git push origin v1.0.0
git tag
```
A version tag identifies a particular commit.

# Push this project to GitHub

The intended destination is `https://github.com/Logonotobscurity/career-intelligence-os`.

## 1. Create the destination repository

Create an empty repository named `career-intelligence-os` under the `Logonotobscurity` GitHub account. Choose **private** or **public** according to your preference. Do not initialize it with a README, license, or `.gitignore`, because this source package already includes its own README and ignore rules.

## 2. Push from this directory

Open a terminal in the extracted `career-intelligence-os` directory and run:

```bash
git init
git branch -M main
git add .
git commit -m "Initial Career Intelligence OS implementation"
git remote add origin https://github.com/Logonotobscurity/career-intelligence-os.git
git push -u origin main
```

Authenticate with GitHub using your approved credential flow when Git requests authentication. Never paste a personal access token into source files, a chat, or a shell command saved in shell history.

If Git reports that a remote named `origin` already exists, inspect it with `git remote -v` before changing it. If the destination repository has an initial commit, review the histories before attempting to push; do not force-push over existing work.

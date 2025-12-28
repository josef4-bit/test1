# Belivar Studio — Portfolio

This repository contains a responsive single-page portfolio for Belivar Studio.

How to run locally

1. Open this folder in your code editor.
2. Open `index.html` in a browser (double-click or use Live Server).

How to publish to GitHub

Option A — create remote manually:

1. Create an empty repo on GitHub (no README).
2. In this folder run:

   git remote add origin https://github.com/<your-username>/<repo>.git
   git branch -M main
   git push -u origin main

Option B — using GitHub CLI (`gh`):

1. Install and authenticate `gh`.
2. Run:

   gh repo create <your-username>/<repo> --public --source=. --remote=origin --push

Replace `<your-username>` and `<repo>` with your GitHub username and desired repo name.

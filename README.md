![CI Status](https://github.com/jgescalante1-art/cloud-ci-cd-demo/actions/workflows/main.yml/badge.svg)


How it works

It works by using Github Actions

Workflow:

1. Checkout Code– Downloads the latest code from the repo
2. Setup Node.js – Installs Node.js version 24
3. Install Dependencies – Runs `npm install` to get packages
4. Run Tests – Runs `npm test` to check everything works
5. Use Secret – Safely accesses stored API keys
6. Deploy – Publishes the site to GitHub Pages automatically

----------------------------------------------
What triggers deplotment?

It is automatically triggered when a code is push into main branch. 
----------------------------------------------

Security Setup

Github Secrets - no hardcored keys

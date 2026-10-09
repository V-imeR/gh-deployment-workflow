# GitHub Pages Deployment

A simple GitHub Actions workflow that deploys a static website to GitHub Pages.
Every push to `main` that changes `index.html` triggers the workflow and
publishes the new version of the site.

Project URL: https://roadmap.sh/projects/github-actions-deployment-workflow

## Files

```text
.
├── .github/
│   └── workflows/
│       └── deploy.yml
├── index.html
└── README.md
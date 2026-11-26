# Temporary offline mode

The site is temporarily replaced by maintenance/index.html.

To restore the original site:
1. Copy archive/deploy.original.yml over .github/workflows/deploy.yml
2. Commit to main. The Deploy workflow runs and rebuilds the site from manifest.txt (unchanged).

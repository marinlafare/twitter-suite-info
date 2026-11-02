# X Manager — project information

Public description page for a personal X account-management application.

Website: https://marinlafare.github.io/twitter-suite-info/

The application displays mentions, supports text and image publishing and replies, and records publishing outcomes. Each account owner runs their own private instance and supplies their own API credentials. Keyword-triggered replies using a separate generation service are planned functionality.

This repository contains only the public information page. It contains no application backend, credentials, or account data.

## Hosting

GitHub Pages serves the static files from the root of `main`. `.nojekyll` disables Jekyll processing. There are no package dependencies, JavaScript, or background services to run. Hosting this page adds no CPU or RAM use to the account manager's Docker or Cloud Run instance.

## Editing

Edit `index.html` and `styles.css`, then push to `main`. GitHub Pages publishes the updated files. The links to the stylesheet and favicon are relative, so the site works under its repository URL.

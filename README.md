# Rohans Web — Personalized Welcome Page

This repository contains the `index.html` welcome page. It reads the `name` query parameter and displays a greeting such as **Hi Rohan**.

## Enable GitHub Pages

1. Open the repository Settings.
2. Select Pages.
3. Under Build and deployment, choose Deploy from a branch.
4. Choose the `main` branch and `/ (root)` folder, then Save.
5. After GitHub Pages publishes the site, the expected URL is:
   https://rohansweb-codexamples.github.io/ubiquitous-system/

The welcome page can then be opened with a name, for example:
https://rohansweb-codexamples.github.io/ubiquitous-system/?name=Rohan

The `name` parameter only personalizes the greeting. It is not an access-control mechanism. Verify access codes in Google Apps Script before redirecting here.

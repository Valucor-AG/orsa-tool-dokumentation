# ORSA-Tool Dokumentation

This repository contains the documentation for Valucor’s ORSA-Tool.
To work on the website, first clone the repository including the theme via
```
git clone --recurse-submodules ssh://github.com/Valucor-AG/orsa-tool-dokumentation
```
and then change into the directory.

To test the site locally, first install [hugo extended](https://gohugo.io/), eg, via `winget install Hugo.Hugo.Extended`, and then run `hugo server` from the root of the directory.

*Assuming GitHub pages has been set up for the repository* (check under Setting > Pages), to deploy, just push the `main` branch to GitHub; the `hugo.yaml` workflow does the rest.
# Boilerplate Technical Documentation
![Python](https://img.shields.io/badge/-Python-3776AB?style=flat-square&logo=python&logoColor=white)
![yaml](https://img.shields.io/badge/-YAML-black?style=flat-square&logo=yaml&logoColor=red)
![Markdown](https://img.shields.io/badge/-Markdown-000000?style=flat-square&logo=markdown&logoColor=white)

This repository contains the boilerplate technical documentation for your teams projects which are published and hosted using GitHub Pages.

## Getting Started

This repository uses `mkdocs` to generate a static website from GitHub flavored markdown. `mkdocs` can be installed by following the installation directions provided on the `mkdocs` website (https://www.mkdocs.org/user-guide/installation/).

In addition to `mkdocs`, the published static site uses a theme called [material](https://github.com/squidfunk/mkdocs-material). The theme can be installed using the following command:

```bash
poetry shell
poetry install
```

## Local Development

When creating or updating the content of the site, `mkdocs` can be used to serve the site locally. The command below will build and serve the site from a local directory.

```bash
mkdocs serve
```

`mkdocs` will automatically rebuild the site as changes are made.

## Deploying Updates

After your pull request has been merged to the main branch, travis will automatically generate the site and push the results to the github.ibm.com `gh-pages` branch for hosting.

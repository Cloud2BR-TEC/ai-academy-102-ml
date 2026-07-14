# Machine Learning 102

[![GitHub](https://img.shields.io/badge/--181717?logo=github&logoColor=ffffff)](https://github.com/)
[Cloud2BR TEC](https://github.com/Cloud2BR-TEC)

Last updated: 2026-07-13

----------

Machine Learning 102 is an intermediate learning path focused on Azure ML workflows beyond the basics.

This repository follows the same GitHub Pages structure and styling used in Machine Learning 101, with a bilingual layout (English and Spanish).

## Scope

This repository publishes Machine Learning 102 content:

- Intermediate ML math and model selection depth.
- End-to-end workflow design and optimization.
- Training, explainability, deployment, and debugging at production level.
- Integration patterns across Azure ML and Fabric.

## Local Preview

`ash
pip install mkdocs mkdocs-material pymdown-extensions mkdocs-static-i18n
mkdocs serve
`

## Build for GitHub Pages

`ash
mkdocs build --strict
`

GitHub Pages deployment is configured in [.github/workflows/deploy-github-pages.yml](.github/workflows/deploy-github-pages.yml).

In GitHub repository settings, set:

- Settings -> Pages -> Source = GitHub Actions

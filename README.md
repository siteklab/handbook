# Speech and Hearing Pathways Lab Handbook

The lab handbook for the Speech and Hearing Pathways Lab (Kevin R. Sitek, UT Dallas): how we work together, and what everyone, PI included, can expect from everyone else.

**Read it at https://siteklab.github.io/handbook/**

It's a [Quarto](https://quarto.org) book. `index.qmd` is the welcome page, and each other chapter is a file in `chapters/`. The chapter order is set in `_quarto.yml`.

## Preview locally

```bash
quarto preview
```

## Propose a change

Open a pull request against `main`, or use the "Edit this page" link on any chapter. You can also raise it at lab meeting. Every push to `main` rebuilds and publishes the site through GitHub Actions (`.github/workflows/publish.yml`). In the repo settings, Pages → Source should be set to **GitHub Actions**.

## Public vs. private

This repo and the site are public. Don't add passwords, private scheduling links, personal contact information, or participant details. Those belong in the private lab wiki, and the handbook links to it.

# CLAUDE.md — Saobraćaj `public_documents`

Guidance for Claude Code / autopilot agents working in this repository.

## ⚠️ This repository is PUBLIC — public documents ONLY

`Saobracaj/public_documents` is a **public** repository. It is published through
GitHub Pages at <https://docs.saobracaj.gleb.at> and is visible to anyone on the
internet — including every branch and the full git history, not just `main`.

**Only public-facing content may live here**, for example:

- Privacy policy (`privacy_policy*.md`)
- Terms of use / subscription terms (`terms_of_use*.md`)
- Account deletion instructions (`delete_account.md`)
- Public landing assets (`favicon.png`, `readme.md` → `index.html`)

### Never commit internal documents or reports here

Do **not** commit — on any branch, including feature branches — any internal
material: implementation/migration plans, audit or legal-review reports, cost or
billing analyses, infrastructure notes, anything containing secrets, credentials,
internal URLs, personal data of users, or unpublished decisions.

Pushing such a file to **any** branch publishes it. A public repo also exposes
its **entire history**, so an internal file is not "safe" just because a later
commit deletes it — removing it requires history rewriting.

Internal documents belong in the private `private_documents/` folder of the
workspace (not a public repo), or in the private repositories of the project.

## How the site is built

`.github/workflows/static.yml` converts every `*.md` in the repository root to
`<name>.html` (`readme.md` → `index.html`) with `markdown-to-html-cli` and deploys
the result to GitHub Pages. Nothing else is needed: add a markdown file, push to
`main`, and it appears at `https://docs.saobracaj.gleb.at/<name>.html`.

Conventions:

- The first line of every document is a level-1 heading (`# …`) — it becomes the
  HTML `<title>`.
- Serbian is the primary (legally binding) version and has no suffix
  (`privacy_policy.md`); translations use `_ru` / `_en` suffixes.
- Every document ends with the «last updated» date. Change history is the git
  history of the file — link to it instead of keeping a changelog inside the
  document.
- The Flutter app links to these documents from «About» — renaming a file
  breaks the links in released app builds. Add, don't rename.

## Delivery

Work on a feature branch and open a Pull Request into `main` (this repo has no
`develop`). Never push directly to `main`.

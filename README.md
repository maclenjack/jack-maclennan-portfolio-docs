# jack-maclennan-portfolio-docs

This repository contains the generated TypeDoc documentation for the `jack-maclennan-portfolio` project.

## What is included

- Static documentation output in `docs/`
- Generated API reference for the main portfolio codebase
- Site assets and HTML files for local preview or deployment

## How to use

### Clone with submodules

```powershell
git clone --recurse-submodules https://github.com/maclenjack/jack-maclennan-portfolio
```

If the submodule is already present, initialize and update it with:

```powershell
git submodule update --init --recursive
```

### Preview locally

Open `docs/index.html` in your browser to view the generated documentation.

## Regenerate documentation

Documentation is generated from the root repository.
From the main project root, run:

```powershell
pnpm document
```

Then commit any changes to the submodule output if the generated docs are updated.

## Notes

- This folder is intended as a documentation site for the portfolio source project, not as the main application source.
- Keep the documentation folder in sync with the root project by re-running `pnpm document` after code changes. Alternately use `pnpm document:watch` to update when files change automatically.

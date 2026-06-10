# CLAUDE.md

This repo is a personal playground for learning CadQuery. Joe is new to CadQuery and using this repo to experiment with parametric CAD models.

## Git workflow

- After committing, push to `origin` immediately (repo is on GitHub, used as a sync point)

## Viewing models in VS Code

- Use the OCP CAD Viewer extension with the `# %%` cell pattern (Jupyter-style)
- Scripts should `from ocp_vscode import show` and call `show(result)` to render
- Run cells with Shift+Enter; interpreter should be set to `./venv/bin/python`

## Working style

- Keep projects small and self-contained, one subdirectory per project/experiment
- Favor parametric scripts (variables for dimensions) over hardcoded one-offs
- When generating models, prefer exporting to STEP and/or STL for viewing
- Explain CadQuery concepts/API as they come up since Joe is learning

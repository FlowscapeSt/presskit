# Contributing

Thanks for contributing to the Flowscape Press Kit!

## Adding assets to an existing project

1. Locate the project folder under `projects/<project-name>/`.
2. Place files in the correct sub-folder:
   - `covers/` — Notion cover images (1500 × 600 px recommended, PNG/JPG)
   - `thumbnails/` — YouTube thumbnails, social banners (1280 × 720 px recommended)
   - `logos/` — Logos in SVG + PNG (transparent background)
   - `press-kit/` — Fact sheets, screenshots, press releases (PDF, PNG, MD)
3. Delete the `.gitkeep` file from a sub-folder once real files are added.
4. Commit and open a PR.

## Creating a new project

```bash
# 1. Copy the template
cp -r projects/_template projects/<your-project-slug>

# 2. Edit the README inside the new folder
#    Replace placeholder text with real project info

# 3. Add your assets to the relevant sub-folders
#    Remove the .gitkeep files from folders that now have real content

# 4. Commit and open a pull request
```

Folder names should use **lowercase kebab-case** (e.g. `my-cool-series`).

## File naming conventions

- Use lowercase and hyphens: `flowscape-logo-dark.svg`
- Include variant hints: `-dark`, `-light`, `-white`, `-square`
- Avoid spaces and special characters

## License reminder

By submitting assets you confirm that:
- You own the rights to the material, **or**
- The material is already licensed compatibly with CC BY 4.0

All assets in this repository are published under
[Creative Commons Attribution 4.0 International (CC BY 4.0)](LICENSE).

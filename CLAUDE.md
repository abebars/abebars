# CLAUDE.md

Guidance for Claude Code in this repository.

## Repository purpose

`abebars/abebars` is Ahmed Bebars's GitHub profile repository. The root `README.md` renders on the public profile. Static Markdown and images only, no build.

## Key files

- `README.md`: the profile page. Branded banner (dark/light via `<picture>`), credential line, work, talks, newsletter/podcast, consulting, certifications.
- `talks/README.md`: full history of talks, workshops and organizing. Keep each table newest first; move "Up Next" rows to "Past Talks" once the date passes.
- `assets/brand/`: banner PNGs (2560x800, 2x). Generated from Ahmed's design system (`brand/design-system/github/` in the project: `gen.py` + `render.js`). Never hand-edit or redraw them; regenerate there and copy in.
- `assets/images/`: older AWS badge images.

## Brand rules

- Name is always "Bebars". No job title or employer in profile copy. Credential line: "AWS Container Hero · CNCF Ambassador".
- Colors: Electric Blue #004FFE, black, gray #E6E7E8; teal/mustard accents, coral minimal. Tagline "BUILT. NOT THEORIZED", hashtag #LevelUpWithAhmed.
- Links: ahmedbebars.io, ab.ventures, linkedin.com/in/ahmedbebars, contact hello@ahmedbebars.io.
- Official talk titles stay as published; no NYT branding or visuals.

## Workflow

Changes go through a pull request; merging to `main` updates the profile.

# Contributing to the Q2 Wiki

This wiki documents fixes, mods, upgrades, and configuration for the Qidi Q2, and is community-maintained. Contributions keep it accurate and current.

## Before You Start

- Search the existing docs and open issues/PRs first to avoid duplicating work.
- Confirm which category your contribution belongs in (see taxonomy below).

## Category Taxonomy

- **[`fixes/`](../fixes)** — known error messages, bugs, and defects in stock behavior, and how to resolve them.
- **[`mods_and_upgrades/`](../mods_and_upgrades)** — optional hardware/software changes.
- **[`configurations/`](../configurations)** — printer.cfg / Klipper config snippets. *(Planned category, not yet populated.)*
- **[`hardware/`](../hardware)** — physical component reference. *(Planned category, not yet populated.)*
- **[`docs/`](../docs)** — general reference material (SSH access, power usage, update process, etc.).

## File Naming Convention

Use `snake_case.md` with a verb-led, descriptive name, matching existing files like `fixing_kiauh.md` and `bed_tramming.md`.

## How to Submit

### Pull Request (preferred)

1. Fork the repository and create a branch.
2. Add your file to the correct category folder.
3. Add a link to it from the root [`README.md`](../README.md) index.
4. Open a PR.

### Issue (alternative)

If you can't write the doc yourself, open an issue describing the fix or mod, and a maintainer will write it up.

## Writing the Doc

Start from [`TEMPLATE.md`](./TEMPLATE.md) — it also includes an alternate structure for catalog/list-style docs (e.g. a list of upgrade options) that don't fit the single fix/mod flow. Style rules pulled from existing docs:

- H1 = title, H2 = major sections, H3 = sub-steps.
- Use GitHub admonitions for callouts, not bold text: `> [!NOTE]`, `> [!IMPORTANT]`, `> [!WARNING]`, `> [!TIP]`.
- Put code/config in fenced blocks with a language hint (e.g. ` ```ini `, ` ```gcode `).
- Put images in an `images/` subfolder next to the doc if needed; link to videos rather than embedding them.
- If adapting someone else's fix, credit and link the original source (matches the existing pattern of citing outside sources like YouTube/Odysee links).

## Review Checklist

Before requesting review, confirm you have:

- Tested the fix/mod personally on a Q2.
- Checked that all links resolve.
- Stated any firmware/hardware-version assumptions the doc relies on.
- Added the doc to the relevant category index/root README.

## License

Contributions are MIT-licensed under this repository's existing [`LICENSE`](../LICENSE).

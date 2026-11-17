# Changelog

## v0.9.17

- Added the same thin neutral outline to standalone **[card]** blocks in Rich/Advanced templates that Rich H2 section containers already use, making card containment visually consistent.

# Changelog

## v0.9.16

- Moved preview editing behind **Advanced** and renamed the action to **Import Preview Edits**.
- Added clearer warnings that preview import is approximate and replaces the current Course Studio markup.
- Added optional page-specific contributor details with **Contributed by** and **Last updated** fields.
- Kept contributor metadata separate from the right-aligned **Back to Modules** navigation.
- Added a light footer divider for Canvas Native and retained the heavier divider for themed presets.
- Made launch behavior predictable: **Light — Teal** starts selected, Advanced starts off, and contributor details start off and blank.
- Updated About, How to Use, and FAQ guidance for Canvas Native, Advanced preview editing, heading hierarchy, and contributor details.
- Removed the bottom **Copy Canvas Title** button to keep output controls focused on generated Canvas HTML.

## v0.9.10

- Added **Canvas Native**, a built-in structural mode that uses Canvas's default heading, paragraph, list, divider, and navigation appearance.
- Canvas Native preserves Course Studio's markup, live preview, snippets, import, and HTML-generation workflow without applying a separate visual theme.
- Simplified the Templates interface in Canvas Native mode by hiding visual-template controls that do not apply.
- Kept library-level actions such as importing templates and adding optional DVC Green presets available in Native mode.
- Right-aligned the default **Back to Modules** footer in Canvas Native to match the other built-in presets.
- Clarified that Canvas supplies the page H1 and body heading structure should begin with H2.

## v0.9.8

Initial public release.

- Light and Structured built-in presets
- optional Advanced features
- custom template creation, import, export, and removal
- optional DVC Green presets
- reusable top-of-page reminders and bottom-of-page notes
- Canvas HTML import
- full backup and restore

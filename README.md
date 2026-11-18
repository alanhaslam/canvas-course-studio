# Canvas Course Studio

**Canvas Course Studio** is a free, offline tool for creating consistent, accessible, and visually organized Canvas pages without requiring users to write HTML from scratch.

It uses simple markup and a live preview to generate Canvas-ready HTML. Users can start with Canvas-native structure, restrained built-in presets, create or import custom templates, save reusable reminders and notes, and enable more advanced layouts when needed.

## Current version

**v0.9.18**

The current source is available in this repository as [`canvas_course_studio.html`](canvas_course_studio.html).

For the easiest download, use the repository's **Releases** section and download the versioned HTML release asset. Save the HTML file to your computer and open it in a modern web browser. No installation is required.

## Preset levels

Course Studio supports four levels of visual complexity:

- **Canvas Native** — semantic structure with Canvas's default appearance
- **Light** — restrained visual styling
- **Structured** — stronger visual separation between sections
- **Advanced** — richer layouts and more layered HTML

Canvas Native is intended for instructors who want help with page structure, markup, preview, snippets, and HTML generation without adding a separate visual theme.

## What it does

Canvas Course Studio can:

- generate Canvas-ready HTML from simple markup
- preview pages while you work
- support semantic H2, H3, and H4 heading structure
- add callouts, lists, reminders, notes, contributor details, and navigation
- use Canvas Native, Light, and Structured presets
- expose richer layouts and preview editing through optional Advanced features
- create, import, export, and remove custom templates
- add optional DVC Green presets
- save reusable top-of-page reminders and bottom-of-page notes
- import existing Canvas HTML for editing
- export and restore backups of custom templates, snippets, and preferences

## Privacy and offline use

Canvas Course Studio runs locally in your browser.

It does **not** connect to Canvas, ChatGPT, OpenAI, or another online service. Content stays on the user's computer unless the user independently chooses to copy, upload, or share it elsewhere.

## Basic workflow

1. Download the HTML file and open it in a browser.
2. Choose a visual preset.
3. Write or paste content into the Course Studio Body.
4. Use the toolbar or simple markup to structure the page.
5. Review the live preview.
6. Copy the generated HTML.
7. Paste it into the HTML editor in Canvas.
8. Preview the page in Canvas before publishing.

Course Studio also includes a **Load Sample Page** option for users who want to explore the markup and page components before creating their own page.

## Advanced preview editing

Advanced mode allows small text edits directly in the preview. **Import Preview Edits** translates those changes back into Course Studio markup.

Preview import is approximate. Complex formatting or structural changes may be simplified, and importing replaces the current Course Studio markup with the translated preview. Review the Course Studio Body after importing and avoid making competing changes in both places before an import.

## Backups

Course Studio stores custom templates, snippets, and preferences locally in the browser. They do not automatically follow users to another browser or computer.

Use **Backup → Export Full Backup** to create a dated JSON backup file. Store that file somewhere already protected by a normal backup or cloud-storage workflow, then use **Restore Full Backup** when needed.

## Canvas notes

- Canvas supplies the page H1; Course Studio body content begins with H2.
- Course Studio does not publish directly to Canvas.
- Internal Canvas links should be added or checked in Canvas after pasting the generated HTML.
- The example **Back to Modules** link must be replaced with the appropriate link for the user's own Canvas course.
- Contributor name and update date are page-specific and intentionally start blank on each launch.
- Preview generated pages in Canvas before publishing because Canvas may handle some HTML or spacing differently from the local preview.
- Keep headings semantic and sequential: H2 → H3 → H4.

## About

Canvas Course Studio was developed using ChatGPT as an independent faculty tool for building Canvas course materials while preserving instructor control over page design and HTML.

© 2026 Alan Haslam

## License

The software is licensed under the [MIT License](LICENSE).

Documentation and sample content are licensed under **Creative Commons Attribution 4.0 International (CC BY 4.0)**.

See [CHANGELOG.md](CHANGELOG.md) for release history.

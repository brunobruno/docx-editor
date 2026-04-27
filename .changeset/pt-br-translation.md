---
"docx-editor": patch
---

Add Brazilian Portuguese (pt-BR) locale support with 41% translation coverage.

This PR introduces:
- New `packages/react/i18n/pt-BR.json` file
- 251 translated UI strings (41% coverage)
- Proper locale structure following existing patterns
- All keys in sync with en.json source

The translation covers core UI elements including:
- Common actions (cancel, save, edit, etc.)
- Toolbar and formatting controls
- Color picker and dialog interfaces
- Table operations and context menus
- Error messages and status indicators

Remaining untranslated keys will fall back to English gracefully, allowing for incremental completion of the translation.

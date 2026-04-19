# Axiom Desk

Axiom Desk is a single-file, offline productivity cockpit for Windows built entirely with Python's standard library. It stores tasks, notes, focus sessions, favorites, templates, and activity history in a local SQLite database.

## Current Version

**v1.6**

## License

Released under the [MIT License](LICENSE).

## Highlights

- Task manager with filters, due dates, priorities, recurrence, duplicate, and postpone actions
- Dashboard with overdue, due-soon, and 7-day agenda visibility
- Notes editor with tags, clipboard helpers, and quick search
- Focus timer with session logging
- File hash calculator and text statistics tools
- Global search and command palette for fast keyboard-driven navigation
- Favorite files and folders for quick access
- Persistent activity trail stored locally
- Light/dark theme toggle
- Backup, export, and import tools

## Requirements

- Windows
- Python 3.x with `tkinter` enabled
- No third-party dependencies

## Quick Start

1. Clone or download this repository.
2. Make sure Python is installed.
3. Run:

```bash
python axiom_desk.py
```

On Windows, you can also double-click:

```bash
run_axiom_desk.bat
```

## Data Storage

Axiom Desk stores all data locally in your user profile:

- **Windows:** `%APPDATA%\AxiomDesk`
- **SQLite database:** `axiom_desk.sqlite3`
- **Backups:** `backups/`

## Keyboard Shortcuts

- **Ctrl+K** — Global search
- **Ctrl+P** — Command palette
- **Ctrl+N** — Quick task
- **Ctrl+Shift+N** — Quick note
- **Ctrl+S** — Save the active editor
- **F5** — Refresh all
- **F6** — Toggle light/dark theme

## Usage Notes

- Use the top search bar for quick searching across tasks, notes, favorites, and templates.
- Save a task as a template from the Task tab, then create new tasks from that template later.
- Mark recurring tasks as complete to automatically generate the next instance.
- Use the Command Palette for fast navigation and common actions.
- Create a backup before large imports or major data changes.
- Export and import are JSON-based for simple portability.

## Version History

- **v1.6** — command palette improvements, persistent activity trail, and template-aware navigation
- **v1.5** — command palette, persistent activity history, activity dashboard counter
- **v1.4** — 7-day agenda, task templates, duplicate/postpone tools, broader search coverage
- **v1.3** — recurring tasks, repeat-aware task editor, recurrence counters
- **v1.2** — due-soon forecasting, duplicate/postpone task actions, folder favorites, richer search previews
- **v1.1** — due watch dashboard, improved quick-note flow, favorite search jumps
- **v1.0** — initial release

## Contributing

Issues and pull requests are welcome. Please keep changes aligned with the project goals: offline-first, Windows-friendly behavior, and no third-party dependencies.

## Repository Notes

The repository should include the main app script, the Windows launcher batch file, and the latest patch notes for the current release.

This project and README is entirely generated and maintained by OpenAI's GPT-5.4-Thinking-Mini.


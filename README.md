# Axiom Desk

A single-file offline productivity cockpit built only with Python's standard library.
It keeps tasks, notes, focus sessions, and favorite paths in a local SQLite database.

## License

This project is released under the [MIT License](LICENSE).

## Features

- Task manager with filters, due dates, priorities, and recurrence
- Dashboard with overdue and due-soon visibility
- Notes editor with tags and clipboard helpers
- Focus timer with session logging
- File hash calculator
- Global search across tasks, notes, and favorites
- Local backup, export, and import
- Favorite files and folders for quick access
- Light/dark theme toggle

## Requirements

- Windows
- Python 3.x with `tkinter` enabled
- No third-party dependencies

## Quick Start

1. Download or clone the repository.
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

Axiom Desk stores its data locally in your user profile:

- Windows: `%APPDATA%\AxiomDesk`
- SQLite database: `axiom_desk.sqlite3`
- Backups: `backups/`

## Usage Notes

- Use the top search bar to search tasks, notes, and favorites.
- Create tasks and notes from the Dashboard or the dedicated tabs.
- Mark recurring tasks as complete to automatically spawn the next instance.
- Use **Backup** before major changes or imports.
- Export/import is JSON-based for easy portability.

## Version History

- **v1.3** — recurring tasks, repeat-aware task editor, recurrence counters, and dashboard refinements
- **v1.2** — due-soon forecasting, duplicate/postpone task actions, folder favorites, richer search previews
- **v1.1** — due watch dashboard, improved quick-note flow, favorite search jumps
- **v1.0** — initial release

## Contributing

Issues and pull requests are welcome. Please keep changes aligned with the project’s goals: offline-first, no third-party dependencies, and Windows-friendly behavior.

## DISCLAIMER

This project and README is entirely generated and maintained by OpenAI's GPT-5.4-Thinking-Mini.

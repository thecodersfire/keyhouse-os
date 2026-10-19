# Built-in features for keyhouse-os

Purpose: real estate work

1. **organize project files** — run keyhouse-os-workspace. It creates ~/Documents/keyhouse-os-workspace/ with Inbox, Projects, Archive folders.
2. **draft a session plan** — run keyhouse-os-plan to open a purpose-specific Markdown plan, saved under ~/Documents/keyhouse-os-session-plans/.
3. **check task readiness** — run keyhouse-os-check for an interactive checklist. Answers are not saved or transmitted.

These local tools create folders, open a local note, or display prompts. They do not install packages, change system settings, or send data.

Install them from this repository:

    mkdir -p "$HOME/.local/bin"
    install -m 0755 features/keyhouse-os-workspace features/keyhouse-os-plan features/keyhouse-os-check "$HOME/.local/bin/"

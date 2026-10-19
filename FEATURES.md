# Built-in features for solo-desk-os

Purpose: freelance work

1. **organize work and records** — run solo-desk-os-workspace. It creates ~/Documents/solo-desk-os-workspace/ with Tasks, Records, Reference folders.
2. **plan a focused work session** — run solo-desk-os-plan to open a purpose-specific Markdown plan, saved under ~/Documents/solo-desk-os-session-plans/.
3. **check records and task readiness** — run solo-desk-os-check for an interactive checklist. Answers are not saved or transmitted.

These local tools create folders, open a local note, or display prompts. They do not install packages, change system settings, or send data.

Install them from this repository:

    mkdir -p "$HOME/.local/bin"
    install -m 0755 features/solo-desk-os-workspace features/solo-desk-os-plan features/solo-desk-os-check "$HOME/.local/bin/"

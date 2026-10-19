# Built-in features for solo-desk-os

Purpose: freelance work

1. **organize work and records** — run solo-desk-os-workspace. It creates ~/Documents/solo-desk-os-workspace/ with Tasks, Records, Reference folders.
2. **plan a focused work session** — run solo-desk-os-plan to open a purpose-specific Markdown plan, saved under ~/Documents/solo-desk-os-session-plans/.
3. **check records and task readiness** — run solo-desk-os-check for an interactive checklist. Answers are not saved or transmitted.

These local tools create folders, open a local note, or display prompts. They do not install packages, change system settings, or send data.

Install them from this repository:

    mkdir -p "$HOME/.local/bin"
    install -m 0755 features/solo-desk-os-workspace features/solo-desk-os-plan features/solo-desk-os-check "$HOME/.local/bin/"

## Preinstalled purpose software

The installer adds these three Flathub applications for freelance work:

1. **GNOME Calendar** — org.gnome.Calendar
2. **KeePassXC** — org.keepassxc.KeePassXC
3. **VSCodium** — com.vscodium.codium

They are installed from Flathub during setup. The repository contains application IDs and documentation, not third-party binaries; each publisher’s terms and licenses apply.

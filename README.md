# MAXEY MOD1K — Starter UI Prototype

This repository starter contains a standalone browser-based interface concept for the MAXEY MOD1K project.

## Included
- Black and electric-blue styling
- Collapsible menu controlled by a floating button
- FOV circle preview with on/off toggle and adjustable size
- Clearly labeled demo diagnostics
- Item-catalog placeholder

## Important limitations
This is a standalone HTML prototype. It is **not** an iOS dylib, does not modify Oxide, does not read game memory, does not aim at players, and does not spawn items or send server commands.

Actual game integration requires a legitimate development build and authorization for any server-side testing features. ESign signs compatible app packages; it does not compile native libraries or decrypt App Store executables.

## Preview on iPhone
1. Open `index.html` from the Files app or a suitable static hosting preview.
2. Use the floating `M` button to collapse or reopen the menu.
3. Toggle the FOV circle and adjust its size.

## Suggested next steps
- Commit this starter to the private `MAXEY-MOD1K` GitHub repository.
- Keep Apple signing certificates, provisioning profiles, passwords, and private game files out of the repository.
- Determine the game's engine and obtain an authorized development/test build before considering native integration.
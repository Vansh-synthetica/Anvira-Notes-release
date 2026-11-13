# Anvira Notes 1.2.32

A safer, sturdier app, with a command palette and the fixes and features from this week's testing.

## Command palette
- Press Ctrl+P anywhere (or Ctrl+K when you are not typing in a text box) to jump to any page, or to run a command: go to Notes, Study, Messages or Settings, switch a theme, open AI & models, see the shortcuts, check for updates, report a problem.
- Type `>` to see commands only.

## Safer
- The app now runs only its own code: a script hidden in a shared notebook, an imported document or a chat message is refused outright.
- Exporting a page to PDF prints the page and never runs anything inside it.
- A page with a missing or malformed id, or a damaged study-progress record, is refused with a clear message instead of being written into your notebook.

## Sturdier
- If the window ever stops or freezes, the app now says so and offers Reload, instead of leaving a blank window. Your notes are saved as you type.
- A background error no longer puts up a technical error box; it is written to a log beside the app's data.
- The "Something went wrong" screen has the right words for this app, a Try again button, and Copy details.

## Fixes
- Links in a note open only on Ctrl+click again (a second copy of the link feature could open them on a plain click).
- The "Ready for AI: high-end PC" card was drawn in warning red; it is green, like the other "ready" cards.
- The account menu stays attached to the side rail, and Escape closes it.
- "Moved to Trash · Undo" and other messages stay while the pointer is on them, and a repeated message no longer stacks.
- Notebook names are trimmed and kept to a sensible length.
- Checkboxes and radio buttons in dialogs match the dark and light themes.
- Messages (Ctrl 3) is listed in the keyboard shortcuts.

## From this week's testing
- Choose your school level (junior high, senior high, college): Pochi explains at that level, and Research Studio follows your school's format.
- Research Studio: three methodologies and 23 research designs, with a question guide to help you choose.
- Report a problem, from the account menu or Settings › About, with an optional screenshot. It is kept and sent later if you are offline.
- Cheat sheets no longer repeat themselves, and formulas in chat are drawn properly instead of showing raw LaTeX.

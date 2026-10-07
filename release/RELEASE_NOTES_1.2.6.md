### New
- **Deleted notebooks can be brought back.** Deleting a notebook used to remove it for good. It now shows **Undo** right away, and stays in **Settings → Data → Deleted notebooks** for 30 days, with its pages, files, history and exams.
- **Undo for Ask AI page edits.** A change Ask AI makes to a page is now one step, with **Undo this change** right under the answer.

### Faster
- **Mock exams are made much faster.** The AI stops writing as soon as the exam has enough questions, never runs on past a sensible length, and checks its answers without re-reading the same notes for every question. In our test (a Quick exam from biology notes, Qwen2.5 3B on a laptop processor) an exam took 4 min 23 s instead of 6 min, with 16 AI calls instead of 27, and came out complete (10 of 10 questions instead of 9).
- **No more freezes with big notebooks.** Preparing a long PDF or textbook for an exam, a lesson or exam results took up to 10 seconds with the window frozen, several times per exam. It now takes a fraction of a second, done once.
- **Explanations of your mistakes appear as they are written**, instead of after the whole answer.
- **Typing stays smooth in big notebooks.** Saving a large notebook used to freeze the app (and your keyboard) for up to 3 seconds at a time. Saves now happen in the background, and the app is busy for only about a tenth of a second.
- **Search and Ctrl+P** no longer load every notebook in full to look through page titles.
- Pages linked to Google Docs or Notion no longer rewrite the whole notebook every few seconds while nothing changes.

### Better
- **Ask AI with 3B models:** answers written as "[1] (paragraph) …" instead of the expected format are now understood and applied (before, nothing changed); a heading repeated at the top of a rewrite is taken out.
- **Ask AI with very small models (about 0.5B):** an edit that would overwrite other parts of the page is refused, and you are told to select the passage and use Improve writing instead. In our tests Qwen2.5 0.5B damaged other blocks in 6 of 72 edits before, none now.
- **Flashcard and daily sessions you leave early still count.** Before, closing a session before the last card threw away every review in it: the cards stayed due as if never studied. Reviews are now saved as you go, and earn XP and streak.
- **Closing the window waits for unsaved typing** (a second or so) instead of risking the last words.
- **Damaged files repair themselves.** A damaged notebook list is rebuilt from the notebooks, and a damaged notebook opens from a backup made each session (you are told when that happens).

### Fixed
- Characters typed while a save finished could disappear, and the loss was saved.
- With no AI engine installed, the "Anvira Runtime is needed" window popped up every time you paused typing, even after **Not now**.
- Restoring a page version now always shows the restored text, and keeps what you had just typed in the history.
- Moving a page to another notebook can no longer lose it if saving fails half way.
- Security: web research can no longer be redirected to your own PC or local network; spreadsheets exported as CSV can no longer contain cells that run as formulas in Excel; chart values are escaped in exported pages.

### Update
If you have an earlier Anvira Notes, it offers this update by itself: click **Update available** at the top right, then **Restart to update**. Or download Anvira-Notes-Setup-1.2.6.exe below. Your notes, lessons and settings are kept.

### Checksum
SHA-256: `96922e4dd687068059a8f2561e47a6e57cb92a4bfb9ce55c0ffa2b86fe565585`

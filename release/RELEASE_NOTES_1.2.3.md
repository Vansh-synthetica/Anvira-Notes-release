### New
- **Tiny AI models (about 0.5B) now work properly.** Qwen2.5 0.5B, Qwen3 0.6B and other models under 1.5B get their own way of being asked: the task and your text are clearly separated, a worked example shows what a good answer looks like, edits are written as checked JSON, and every answer is checked before it touches your note. In our tests across every Notes AI feature, Qwen2.5 0.5B went from 33 to 62 of 63 checks and Qwen3 0.6B from 42 to 63 of 63 (and 29→55 and 41→54 of 57 on a second set of new texts).
- **Thinking switched off for tiny Qwen3 models.** Qwen3 0.6B spent about three quarters of every answer thinking privately; it now answers directly (about 0.7 s instead of 3 s), and only thinks for questions that need it, like "which month cost the most?".

### Better
- **Writing tools with small models.** Improve writing no longer answers a selected question instead of rewriting it. Shorten actually shortens. Continue writing no longer repeats your paragraph before continuing. If a small model still gets it wrong, your text is left exactly as it was and you are told.
- **Ask AI with small models.** Answers come from your notes and sources; when they don't cover a question it says "Your notes don't cover this." instead of guessing. Lines that match your question are pointed out to the model, so facts tucked inside a source are found.
- **Editing pages and sheets with small models.** Sheet edits use cell names (B4) and work out the right row and column; a new row always goes below the last one, never over it. Page edits never delete a block you didn't ask to remove, renamed headings stay headings, and "add a paragraph" writes a real paragraph. Questions about the page or sheet are answered instead of turned into edits, with totals, highest and lowest worked out exactly.
- **No more runaway answers.** Small models can no longer loop on one line until the answer fills the page: answers have a sensible length and repeated lines are removed.
- **Ghost text arrives faster** on Qwen3 models (it no longer waits for a thinking phase).
- **Lecture notes and meeting notes with small models.** Lectures are read in shorter parts and answered as checked JSON, so the notes always come out.
- Models of 1.7B and up (Qwen3 1.7B/4B, Llama 3.2 3B, Qwen2.5 7B…) are asked exactly as before.

### Fixed
- **Summarize page, web research and meeting notes on PCs without an NVIDIA GPU.** Anvira Runtime gives those models a 4,096-token memory; a long page (up to 18,000 characters) or web research with your notebook (up to ~25,000) did not fit, and the request failed or was cut off. Everything sent to the model is now sized to the model's real context.
- **Summarize page** tells you when something goes wrong instead of silently stopping.

### Anvira Runtime 1.0.1
Get the most out of this update with **Anvira Runtime 1.0.1** (click **Runtime update** at the top right): it passes the anti-repetition and thinking settings through to the model. Anvira Notes 1.2.3 also works with Runtime 1.0.0.

### Update
If you have an earlier Anvira Notes, it offers this update by itself: click **Update available** at the top right, then **Restart to update**. Or download Anvira-Notes-Setup-1.2.3.exe below. Your notes, lessons and settings are kept.

### Checksum
SHA-256: `4d1ab99e8a640d6ef9438a47c0e3077a800d0a22c1a750f9d151601bc5698f1a`

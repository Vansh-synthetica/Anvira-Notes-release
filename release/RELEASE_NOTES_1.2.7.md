### New
- **Turn on GPU acceleration from Settings.** If your PC has an NVIDIA graphics card but Anvira Runtime was installed without its GPU pack, **Settings → AI & Models** now says so and offers **Turn on GPU** (a one-time download of about 650 MB; your models and settings are kept). Before, the GPU pack could only be chosen when the runtime was first installed, so many PCs ran every AI feature on the processor without knowing. On our test laptop (RTX 3050, Qwen2.5 3B) a Quick mock exam from six research papers took about 30 seconds.

### Better
- **Every new mock exam really asks new questions.** A later exam used to tell the AI which questions had been asked before and ask for "other points". In our tests a 3B model often copied that list instead of writing new questions, and the copies were thrown away: time lost, and sometimes a shorter exam. Now the AI reads only the parts of your notes no earlier question covered, so it cannot repeat them, and it has less to read. In our test, two Quick exams in a row from the same papers both came out complete (10 of 10), each in one pass.
- **Fairer multiple-choice questions.** A wrong option that is really another true fact from your notes (for example "detoxifies drugs" and "makes lipids" both offered for the smooth ER), or the right answer said another way, is taken out, leaving a clean question with one right answer. Questions that talk about "the passage", give the answer away by making it the one long detailed option, just repeat the question as the answer, or whose explanation points at a different option than the one marked, are left out. Quizzes in lessons get the same checks.
- **Cleaner reading of PDFs.** Citation markers (like 【8†L25-L33】 or [12]) and web addresses are removed before the AI reads your material: less to read, and they no longer end up inside questions.
- **Study guide, cheat sheet and grade extraction start sooner** when you use more than one of them on the same notebook: the notebook now goes to the model first, so it reuses what it has already read instead of reading it all again.

### Anvira Runtime 1.0.2
Get the most out of this update with Anvira Runtime 1.0.2 (click **Runtime update** at the top right): the AI can now work on more than one request at a time, so chat, Ask AI and ghost text no longer wait behind an exam or lesson being written. Anvira Notes 1.2.7 also works with Runtime 1.0.1.

### Update
If you have an earlier Anvira Notes, it offers this update by itself: click **Update available** at the top right, then **Restart to update**. Or download Anvira-Notes-Setup-1.2.7.exe below. Your notes, lessons and settings are kept.

### Checksum
SHA-256: `00bb77c97b06297afb6f11fea29d4d79eecdd097d6e001003b8086979f4ed229`

### Every question checked against your notes
Quizzes, flashcards and mock exams no longer show a question your notes do not back. Before anything reaches you, Anvira finds the sentence in your notes that states its answer, checks that the sentence is about what the question asks, that the numbers agree, and that no other option is also right. Then the AI answers the question again without seeing the answer key; if it disagrees, the question is left out. "Which is NOT…" questions, options that contain the answer, and names or terms your notes never use are left out too.

Tested on 58 questions and cards written by the Qwen2.5-Coder 3B model and checked by hand: all 17 wrong or unfair ones were caught, and all 41 good ones were kept. Before this update, about a quarter of a mock exam's questions could be wrong.

- **You get the number of questions you asked for.** A quiz of 25 sometimes came out with 5. Anvira now reads all of your material and, when the checks leave out questions, writes more from parts not asked about yet. If your notes really cannot support that many, it says so instead.
- **The answer comes from your notes.** After each quiz answer and on the mock exam results you see "From your notes", with the sentence that proves it.

### Mock exams
- **Choose the question types:** Mixed (multiple choice, identification and written, in sections like a real exam), Multiple choice, Identification or Written.
- **Identification questions** are new: write the term, name or number. Small spelling slips are accepted, and you can change a mark you disagree with.
- **Faster to make:** each part of your notes is read once for all question types, and no more extra rounds to chase the last question or two.

### Cheat sheet and study guide cover every source
Both used to read only the part of the notebook that best matched one search, so with 6 lessons they often covered only 2. Now every source is read and gets its own section, and lines your notes do not back are left out.

### Ask Pochi with many sources
Notebook chat now handles 6 to 10 sources, even with small models. Pochi always knows which sources the notebook has and what each covers. A question about everything ("summarize all the lessons", "compare lesson 3 and 4") gets every lesson, and the passages it reads are cut down to the sentences that matter, so more fits in the same space. Tested on a 10-source notebook: the passage with the answer was included for 19 of 20 questions at a small model's budget (it was 10 of 20), and every lesson was visible on overview questions (it was 2 to 7 of 10).

### Tagalog lessons
Questions are written and checked in the language of your notes, then translated. A translation is only kept if every term and number survives and it means the same when translated back. Models that cannot write reliable Tagalog (such as Qwen2.5-Coder 3B) keep the lesson in your notes' language and tell you so; choose Gemma 3 4B in Settings → AI & Models for Tagalog lessons.

### New: Math Lab
Next to the Chemistry and Physics Labs on the Study page.
- **Solve:** type an equation, a system, "factor …", "derivative of …", "integrate …", two points or a word problem, and see every step worked out and graphed. The math engine computes every answer exactly; the AI only reads word problems and explains on request.
- **Coordinate plane:** plot and drag points, see their quadrant, distance, midpoint, slope and the line through them; practice plotting and reading points; connect-the-dots pictures; translations, reflections, rotations and dilations.
- **Functions and graphs:** a graphing calculator with sliders and key points (roots, turning points, intersections), lines, parabolas and the unit circle.
- **Algebra, Geometry, Calculus:** equations and systems step by step, factor and expand, triangles and circles, derivatives with tangent lines, and area under a curve.

### Fixes
- "Practise mock exam" is now spelled "Practice mock exam".

### Update
If you have an earlier Anvira Notes, it offers this update by itself: click **Update available** at the top right, then **Restart to update**. Or download Anvira-Notes-Setup-1.2.20.exe below. Your notes, lessons and settings are kept. Anvira Runtime does not need an update.

### Checksum
SHA-256: `a3c8c27fec0d1aa8b333f047a805307353cb34a181c1c0bd626d457d26427508`

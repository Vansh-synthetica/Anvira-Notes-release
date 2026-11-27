# Anvira Notes 1.2.43

A small fix to Research Studio's examples.

## Fixed
- **Anonymous school examples:** the example titles, the sample project and the AI's worked examples in Research Studio no longer name real schools. They now say things like "a public high school" or "a private senior high school", so a generated title or paper won't pick up a real school's name by accident.
- The school box now suggests keeping it anonymous. You can still type your own school's name if you want it in your paper.

## Also out today: Anvira Runtime 1.0.4
Loading an AI model can no longer freeze the PC. The Runtime now sizes the model to the memory that is actually free, leaves processor cores for Windows, runs at low priority and stops retrying a model that won't fit. If there isn't enough room, it tells you so instead of loading. Anvira will offer the Runtime update on its own.

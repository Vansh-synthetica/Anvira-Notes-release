# Anvira Notes 1.2.36

Recording lectures works with antivirus programs.

## Record a lecture
- The speech engine now comes with the app, so recording no longer has to download a program the first time. Some antivirus programs (Avast, AVG) flagged that downloaded engine by mistake as a threat. The first setup now only downloads the speech model.
- If an antivirus still stops the engine, Anvira says so plainly: it's a false alarm, and you can allow the engine's folder in your antivirus. An **Open the engine folder** button takes you straight there.
- If capturing the PC audio fails, the message now says what Windows reported, and suggests the microphone instead.

The speech engine is whisper.cpp's official, unchanged open-source build. The app checks it against a pinned checksum, and everything is still transcribed on your PC.

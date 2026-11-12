# Anvira Notes 1.2.29

## Lecture recording on the NVIDIA graphics card (new)
- On PCs with an NVIDIA graphics card, speech to text can now run on the card: several times faster than the processor, so even the Most accurate speech model keeps up with live speech.
- Turn it on in Record lecture → Speech model → "Use the NVIDIA graphics card". It is a one-time download of about 260 MB, checked against the official whisper.cpp release before it is used.
- If the card does not work on a PC (an old driver, too little graphics memory), the processor takes over by itself and the app says why. Recording never stops because of it.

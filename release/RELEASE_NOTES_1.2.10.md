### Fixed
- **Remember me works.** Anvira Notes asked you to sign in every time it started, even with **Remember me** ticked: your sign-in was saved, but read back too early at startup, before Windows' secure storage was ready, so it looked like there was none. It is now read once that storage is ready, and the app waits for it before deciding whether to ask you to sign in. Sign in once with Remember me and the app opens straight to your notes from then on, offline too. If you signed in on 1.2.9 with Remember me, you will most likely be signed in already after this update.

### Update
If you have an earlier Anvira Notes, it offers this update by itself: click **Update available** at the top right, then **Restart to update**. Or download Anvira-Notes-Setup-1.2.10.exe below. Your notes, lessons and settings are kept.

### Checksum
SHA-256: `154e6fd72dee808457bb718f9f8217edb4006e58ae3822c867aa85561b501861`

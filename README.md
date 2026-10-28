# Lift for Android — releases

Signed APKs and the update file for the personal Lift app. **No source code, no data** — only what a phone needs to install and update the app.

- Download page: https://vaydnn.github.io/Lift-APK/
- `latest.json` — what the app's "check for updates" reads (`version`, `url`, `notes`).
- `lift-X.Y.Z.apk` — the newest five releases, signed with the same key (so each installs over the last and keeps your data).

**Installing:** back up in the old app (💾 Backup) → open the download page on the phone → download the APK → allow "install unknown apps" for that
browser once → Play Protect may say "unrecognized app": choose *Install anyway* → open Lift → *↺ Restore* the backup.

Built and published by the project's release script (`npm run apk:release` in the Lift working copy); see `CHANGELOG.md` there.

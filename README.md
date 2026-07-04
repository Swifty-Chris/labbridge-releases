# labbridge-releases

Öffentliche Release-Artefakte für LabBridge (https://labbridge-web.vercel.app). Der Quellcode liegt im privaten Repo `labbridge-app`; dieses Repo enthält ausschließlich signierte Build-Artefakte und wird automatisch vom CI-Workflow `release-android.yml` gepflegt. Bitte keine manuellen Commits.

## Android (Sideload-Beta)

- `android/labbridge-android-beta.apk` — jeweils neueste signierte Beta-APK (Android 11+)
- `android/android-latest.json` — Versions-Manifest (version_code, version_name, apk_url, apk_sha256); Grundlage für den In-App-Updater und die Download-Seite

Download für Testnutzer: https://labbridge-web.vercel.app/android

Ältere Versionen sind über die Git-History dieses Repos erreichbar. Die iOS-App erscheint im App Store und braucht dieses Repo nicht.
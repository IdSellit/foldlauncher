# Apple Duo

Apple-inspired foldable launcher for Android (target device: Galaxy Z Fold 8).
Status: **Phase 2 - foundation.** Not yet compiled by the author; the first CI run is the first real build.

## Build with GitHub Actions
1. Create a GitHub repo and push this folder to `main`.
2. Open the **Actions** tab -> "Build debug APK". Send/fix any compile errors it reports.
3. When green, download the `apple-duo-debug-apk` artifact, unzip, and install `app-debug.apk`
   (allow "install unknown apps" for your browser/file manager).

## Set as default launcher
Settings -> Apps -> Choose default apps -> Home app -> **Apple Duo**.

## Works now (intended)
HOME registration, installed-app discovery via LauncherApps (all profiles), live refresh on
install/remove/update, launching, light/dark design tokens, transparent window over the system wallpaper.

## Not yet built
Pages, dock, folders, persistence, search, widgets, fold-aware layouts, app pairs, quick panel (Phases 3-7).

## Notes
Versions (AGP 8.7.3, Kotlin 2.0.21, Compose BOM 2024.12.01, compile/targetSdk 35) were chosen for
known compatibility, not verified as latest. Bump to newer APIs once the baseline builds.

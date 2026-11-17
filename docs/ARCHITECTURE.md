# MODUX — Android Architecture

## Stack
- Kotlin
- Jetpack Compose + Material 3
- MVVM / unidirectional state flow
- Coroutines and StateFlow
- Room for structured theme metadata
- DataStore for preferences
- Android WallpaperManager, WallpaperService, AppWidgetProvider and InputMethodService where appropriate
- GPU rendering with Android Canvas / OpenGL ES as features require

## Proposed modules
```text
app/
core/designsystem/
core/model/
core/data/
feature/dashboard/
feature/themes/
feature/creator/
feature/wallpaper/
feature/icons/
feature/launcher/
feature/keyboard/
feature/lighting/
feature/widgets/
feature/effects/
```

## Theme manifest
Each theme should include a stable ID, schema version, title, creator, palette tokens, references to locally validated assets and optional component capabilities.

## Platform boundaries
Android does not grant third-party apps universal control of system fonts, lock screens, status bars or other apps. Home screen layouts require an opt-in launcher. Keyboards require user-enabled IME selection. Lighting effects are primarily simulated on-screen. Live wallpapers are user-selected services and cannot silently replace arbitrary device surfaces.

## Build policy
Use Gradle wrapper, version catalog, pinned compatible Android Gradle Plugin and JDK 17 or later as required by selected tooling. CI must run unit tests and assemble a debug APK before publishing artifacts.

# MODUX — Product Requirements

## Vision
MODUX lets Android users personalize supported device surfaces from one cohesive, premium creative studio.

## Target users
Android enthusiasts, creators, theme designers and users who want coordinated device aesthetics.

## Modules
- **Theme Engine:** theme manifests, palettes, presets, import/export, preview and apply supported components
- **Wallpaper Studio:** static wallpaper selection and Android wallpaper application; live wallpaper engine in later phases
- **Icon Studio:** icon packs and launcher-managed icons; shortcuts where supported
- **Home Screen Studio:** optional MODUX launcher, app grid, dock, folders and widget placement
- **Keyboard Studio:** opt-in custom IME with themes and accessibility-conscious controls
- **Lighting Studio:** screen edge effects and notification-inspired animations, subject to platform permissions
- **Typography Studio:** text effects inside MODUX-controlled surfaces
- **Widget Studio:** configurable Android App Widgets
- **Effects Lab:** shader effects, particles, transitions and motion presets
- **AI Theme Creator:** optional AI-generated coordinated visual assets
- **Marketplace:** eventual creator publishing, moderation and paid theme packs

## Alpha v0.1 acceptance criteria
1. App launches without network connection.
2. Navigation opens real screens for Dashboard, Themes, Create, Explore and Profile.
3. Theme selection and palette changes persist after restart.
4. Theme creator previews changes without modifying device settings.
5. Wallpaper picker handles supported local image formats and system permission flows.
6. Applying a theme explicitly reports which components were applied, skipped or unsupported.
7. Automated Android debug build and basic tests run in GitHub Actions.

## Security and privacy
- Avoid unnecessary permissions.
- Keyboard input must never be logged or transmitted; design explicit privacy disclosures.
- Avoid accessibility-service workarounds for unauthorized system UI modification.
- Keep personal assets on-device unless users explicitly choose cloud synchronization.
- Validate imported theme manifests and assets before use.

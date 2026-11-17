# MODUX

**Modify Your Universe.**

MODUX is a premium Android customization studio by **CodePhrex**. The project aims to bring wallpapers, icons, themes, typography, keyboard styling, lighting effects, widgets and launcher customization into a cohesive Android experience.

> **Status:** Design approved · Documentation foundation · Android application not yet implemented.

## Official design direction
- **Logo:** Gradient hexagonal M
- **Colors:** Midnight `#0B1021`, Cyan `#45E5F9`, Ultraviolet `#985AFF`, Pink `#FF4CA8`, White `#F5F6FC`
- **Fonts:** Orbitron (brand) and Inter (interface)
- **UI:** Dark sci-fi surfaces, luminous gradients, premium modular tiles
- **Approved mockups:** Splash, dashboard, theme browser, theme creator and app icon

## Planned features
| Area | Capabilities |
|---|---|
| Themes | Coordinated palettes, previews and saved presets |
| Wallpapers | Static, live, parallax and interactive backgrounds |
| Icons | Icon packs and launcher-managed styles |
| Home screens | Optional launcher, grids, docks and widgets |
| Keyboards | Opt-in themed Android keyboard |
| Lighting | Screen-edge animations and notification-inspired effects |
| Typography | Fonts and text effects on supported MODUX surfaces |
| Effects | Particles, shaders, transitions and animated themes |
| Marketplace | Future creator uploads and premium theme packs |

## Development
**Target stack:** Kotlin, Jetpack Compose, Material 3, Room, DataStore and Android platform APIs.

**Alpha v0.1 scope:** Dashboard, navigation, theme browser, theme creator, local storage, wallpaper picker and preview.

This repository currently contains the initial documentation. It does **not** yet contain a functional Android application or verified APK.

## Documentation
- [Brand guidelines](docs/BRAND_GUIDELINES.md)
- [Product requirements](docs/PRODUCT_REQUIREMENTS.md)
- [Architecture](docs/ARCHITECTURE.md)
- [Roadmap](docs/ROADMAP.md)
- [Visual asset inventory](assets/README.md)

## Android limitations
Third-party Android apps cannot universally change system fonts, lock screens, status bars or other apps. MODUX will use supported APIs and clearly communicate when an effect requires an opt-in launcher, keyboard, wallpaper service or permission.

## License
All rights reserved by the project owner unless a license is explicitly added. Third-party assets require appropriate rights.

---
**MODUX · Modify Your Universe.**

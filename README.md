# Map Maker — 3D World Studio

Map Maker is an early browser-based 3D world editor prototype. It is intended to grow into a creator-first platform for building, saving and sharing virtual worlds.

## Try the editor

- Live project: https://iammdtanvirrahman.github.io/map-maker/
- Source: https://github.com/iammdtanvirrahman/map-maker

The app is a static site using Three.js from jsDelivr. Open it in a modern browser with an internet connection.

## Current prototype features

- 3D terrain viewport with orbit and zoom controls
- Terrain sculpting: raise, lower, flatten and paint
- Grass, sand, rock and snow material colors
- Place trees, rocks, houses, towers, water ponds and path markers
- Select and drag objects across the terrain
- Object inspector for naming, position, scale and rotation
- Duplicate and delete objects
- Preset terrain: floating island, green valley, desert plateau and snowy mountains
- Reproducible terrain seeds
- Local text-based world recipes that choose terrain and scatter props using simple keyword rules
- Brush preview, configurable brush size and strength
- Scatter tree placement
- Daylight, sunset and blue-hour lighting
- Ground-grid toggle
- Viewport screenshot export
- Scene hierarchy, undo/redo, local browser save and restore
- World JSON export/import with basic input validation
- Mobile-responsive tool and inspector panels
- GitHub Pages deployment workflow

## Important prototype limitations

This is not yet a production-ready editor or full game engine. Projects are saved in the current browser or exported as JSON; there is no cloud account system, synced storage, public read-only world page, real-time collaboration, multiplayer, custom scripting runtime, asset marketplace or AI model integration. “World by description” currently uses local keyword rules and is **not generative AI**.

Imported projects should still be treated as untrusted data. Back up valuable projects before importing or changing terrain detail.

## Technology

- HTML/CSS and JavaScript ES modules
- Three.js and OrbitControls
- Import maps for browser module resolution
- JSON project serialization and localStorage persistence
- GitHub Pages deployment using GitHub Actions

## Product roadmap

1. Stabilize sculpting, drag placement, project save/restore, and undo/redo.
2. Test the editor with independent creators; fix usability and performance problems.
3. Add improved terrain materials, brushes, roads/rivers, and asset organization.
4. Add backend accounts, cloud projects and publishable read-only world links.
5. Explore true AI-assisted world generation only after the core editor is validated.

## Investor readiness checklist

- Record a real product demo from the deployed site.
- Interview target creators and document their feedback.
- Measure first-world completion and repeat usage, not just sign-ups.
- Compare the workflow with existing world editors and prove a specific differentiation.
- Build a milestone-based budget before requesting investment.

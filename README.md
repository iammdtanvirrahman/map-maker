# Map Maker — 3D World Studio

A browser-based 3D world editor prototype. Create a small world, sculpt terrain, place objects, tweak selected objects, and save/export the scene.

## Try it

Open `index.html` in a modern browser, or enable GitHub Pages for the repository:
**Settings → Pages → Deploy from a branch → main / root**.

The editor uses Three.js from jsDelivr, so an internet connection is required. No build step is required for the current prototype.

## Current MVP features

- Interactive 3D terrain viewport with orbit/zoom controls
- Terrain sculpting: raise, lower, flatten and paint
- Grass, sand, rock and snow surface colors
- Place trees, rocks, houses, towers, water ponds and path markers
- Scene hierarchy and object inspector
- Move, scale, rotate, duplicate and delete placed objects
- Preset terrain generation: island, valley, desert and snowy mountains
- Daylight, sunset and blue-hour lighting presets
- Undo/redo for scene changes
- Local browser save/restore
- Export and import world data as JSON
- Responsive layout with mobile tool panels

## Current limitations

This is an early prototype, not a production-ready game engine. It currently has no account system, cloud persistence, public publishing backend, multiplayer, AI world generation, advanced terrain texture splatting, collision/physics simulation, or asset marketplace. Local saves stay in the current browser/device. Treat imported world files as untrusted input.

## Product direction

1. Make terrain editing and asset placement reliable.
2. Add robust world serialization, local project management and autosave.
3. Run creator tests and collect usage/retention data.
4. Add cloud accounts and publishable read-only world URLs.
5. Consider AI-assisted world generation and shared collaboration after core usage is validated.

## Technical choices

- HTML/CSS/JavaScript ES modules
- Three.js for 3D rendering and OrbitControls
- JSON-based world project export/import
- localStorage for early prototype persistence

## Funding readiness

Before fundraising, prepare a short demo, user feedback from target creators, a comparison with alternatives, an MVP milestone budget, and a clear explanation of how this product differs from existing world editors.

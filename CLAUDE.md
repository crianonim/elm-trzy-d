# elm-trzy-d

**Purpose:** Minimal WebGL 3D rendering experiment — renders a single blue quad viewed by a perspective camera using ianmackenzie's Scene3d library.

## Stack
- Elm 0.19.1
- `ianmackenzie/elm-3d-scene`, `elm-3d-camera`, `elm-geometry`, `elm-units`
- `elm-explorations/webgl` (transitive), `avh4/elm-color`
- `elm/browser`, `elm/html`

## Build/Run
No npm/package.json — plain Elm. The repo ships a pre-built `index.html` (open it directly). To rebuild from source:
```
elm make src/Main.elm --output index.html
```

## Structure
- `src/Main.elm` (~40 lines) — sets up a `Scene3d.unlit` scene with a quad entity and a perspective camera at (5, 2, 3) looking at the origin, rendered at 800x600.
- `index.html` — pre-compiled output.

## Status/Notes
Learning/experiment project (single "Initial commit"). It is the most basic possible Scene3d demo; the README is effectively empty.

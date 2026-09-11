# RollOut — design working files

Off-machine backup of the RollOut app's design working material. These are **not**
app assets — the renders the app actually ships live in the app repo under
`assets/`. This folder is `designs/` in the app repo, where it is gitignored (it is
working material, not code), so this repo is its only backup off the build machine.

## Contents
- `*.jpg` — reference photos (tow trucks) used to art-direct the tow-type illustrations.
- `flatbed-type/`, `heavy-haul-type/`, `wheel-lift-type/`, `other-type/` — the raw
  `.obj` / `.mtl` / `.glb` 3D models the tow-type tile renders were built from.
- `tow-tiles/` — the rendered tile screenshots.
- `commission-tow-type-illustrations.md` — the illustration commission brief.

## Keep in sync
When the design files change on the build machine, commit and push here so the
backup stays current. `src/config/towTypes.ts` in the app repo points at this
material for provenance.

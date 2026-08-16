# Preview renders

Deterministic previews for the Axiom Relay batches, so a reviewer can see every
model without checking out a branch and running the renderer.

Produced with `bun run vibe:model preview` on each model's `createPreview`
export, then composed with `scripts/contact-sheet.mjs`. Same rig for every
model in a wave — that is the point of a contact sheet, since the defect that
matters at pack scale is whether the props look like one catalogue.

- `sheets/` — one contact sheet per batch
- `models/` — the individual 1024x1024 previews

This branch carries images only. It is never merged.

# Rere Character & Production Reference Assets

Place approved/canonical visual reference assets here, or document the intended canonical asset path before the binary is committed.

## Character References

- `rere-character-sheet-canonical.png`
- `rere-character-sheet-v02.png`
- `rere-expression-sheet-canonical.png`
- `rere-turnaround-sheet-canonical.png`
- `rere-outfit-sheet-canonical.png`
- `rere-gesture-pose-sheet-canonical.png`

## World / Environment Reference

The environment reference is maintained as a separate production asset family:

- `assets/environment/rere-world-environment-sheet-canonical.png`

The master specification is:

- `docs/WORLD-ENVIRONMENT-BIBLE-RERE.md`

The environment master sheet should visually represent the established Rere universe, including the primary playroom/world anchor and supporting locations.

## Canonical Naming Rules

The word `canonical` means the asset is approved as a visual source of truth. Draft generations should use a draft suffix/version and should not silently replace canonical assets.

Examples:

- `rere-world-environment-sheet-draft-v01.png`
- `rere-world-playroom-draft-v01.png`
- `rere-world-playroom-canonical.png` only after explicit approval

## Character Lock

Key locked identifiers are documented in:

- `docs/CHARACTER-BIBLE-RERE.md`
- `docs/OUTFIT-BIBLE-RERE.md`
- `docs/GESTURE-BIBLE-RERE.md`
- `docs/WORLD-ENVIRONMENT-BIBLE-RERE.md`

## Reference Hierarchy

When multiple references are provided to an AI production tool, use this conceptual priority:

**Identity → Face → Anatomy → Outfit → Gesture → World → Scene**

A scene-specific generation must not silently override higher-priority references.

## World Reference Hierarchy

For a recurring location:

**World Bible → Canonical Environment Sheet → Location Anchor → Story Props → Scene Decoration**

A scene may add story-specific objects, but must not silently redesign the canonical environment.

## Canonical Asset Families

### Identity

- Character canonical sheet
- Character detail/version sheet
- Expression sheet
- Turnaround sheet

### Production Acting

- Outfit sheet
- Gesture & pose sheet

### World

- World/environment master sheet
- Location-specific master sheets
- Future prop sheets

## Binary Asset Note

Documentation may define the intended canonical filename before the binary image is committed. A file is considered **repository-hosted canonical** only after the actual binary asset exists at the documented path.

# Rere Character Reference Assets

Place approved/canonical character images here.

Recommended naming:

- `rere-character-sheet-canonical.png`
- `rere-character-sheet-v02.png`
- `rere-expression-sheet-canonical.png`
- `rere-turnaround-sheet-canonical.png`
- `rere-outfit-sheet-canonical.png`
- `rere-gesture-pose-sheet-canonical.png`

The word `canonical` means the asset is approved as a visual source of truth. Draft generations should use a draft suffix/version and should not silently replace canonical assets.

## Character Lock

Key locked identifiers are documented in:

- `docs/CHARACTER-BIBLE-RERE.md`
- `docs/OUTFIT-BIBLE-RERE.md`
- `docs/GESTURE-BIBLE-RERE.md`

## Reference Hierarchy

When multiple references are provided to an AI production tool, use this conceptual priority:

**Identity → Face → Anatomy → Outfit → Gesture → World → Scene**

A scene-specific generation must not silently override higher-priority references.

## Canonical Asset Set

### Identity

- Character canonical sheet
- Character detail/version sheet
- Expression sheet
- Turnaround sheet

### Production Acting

- Outfit sheet
- Gesture & pose sheet

### Future

The folder will be expanded with approved references for:

- environments
- props
- camera/framing
- other recurring supporting characters

## Binary Asset Note

Documentation may define the intended canonical filename before the binary image is committed. A file is considered **repository-hosted canonical** only after the actual binary asset exists at the documented path.

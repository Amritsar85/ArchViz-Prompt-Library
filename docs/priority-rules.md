# Module priority and conflict resolution

1. **Geometry and composition locks** take precedence for architecture and camera.
2. **Explicit editing requests** permit the named object or region to change, but not other content.
3. **Ambience modules** override the default instruction to preserve time of day, weather and lighting atmosphere. A `LOCK_LIGHTING` module conflicts with a day-to-night conversion: omit it.
4. **Scene-specific modules** refine existing subjects; do not create irrelevant content.
5. **Sharpening modules** control finish and should not override physical realism.

## Assembly order
Master → subject modules → one time-of-day ambience → optional weather/season/mood → compatible locks → local edit instructions.

Avoid using multiple contradictory time-of-day presets together. Avoid `LOCK_OBJECTS` when the task is to replace those exact objects, unless you clearly make an exception.

**Technical limit:** Text is not a geometry constraint solver. A masked composite with original pixels remains the reliable way to keep untouched areas identical.

# Modes and Prompt Compatibility

## Two distinct goals
- **Photorealistic refinement:** use `masters/` + `modules/` + `locks/`; default is *do not redesign*.
- **Concept exploration:** use `concept-design/masters/` + a concept category + a `design-freedom/` setting; explicit architectural modification is allowed.
- **Insertion:** use `insertion/` + position/depth or proxy information and an applicable preservation lock.

Never stack contradictory instructions such as `do not change any geometry` and `reimagine massing` without explicitly identifying which geometry is fixed and which is free.

## Recommended priority
1. Explicit user/client requirements and rights to use material.
2. Fixed project or site constraints and requested edit boundaries.
3. Selected mode (refinement / ideation / insertion).
4. Category prompts and environment/ambience.
5. Quality and sharpness finishing instructions.

## Evaluation
Check camera, footprint, openings, scale references, materials, use, and shadows against source. A good-looking image is not necessarily an accurate proposal. Prompts alone cannot lock pixels or guarantee code compliance.

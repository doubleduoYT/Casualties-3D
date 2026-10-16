# Casualties: Unknown 3D — tentative roadmap

This is a **proposal** for discussion, not a promise of features or release date.

## Milestone 0 — Team foundations
- [x] GitHub repository and README
- [x] Contribution rules, templates, Unity ignore / LFS config
- [x] Agree on Unity 6.3 as the engine version
- [ ] Agree on exact Unity 6.3 patch/build, pipeline, and primary platforms
- [ ] Confirm art/code ownership and original-game IP permissions
- [x] Record the master document's development roles
- [ ] Assign and confirm individual GitHub tasks

## Milestone 1 — 3D prototype
- [ ] Add a working Unity project and a simple test scene
- [ ] Basic player movement, camera, collision, and controls
- [ ] One small environment made of PS1-style low-poly placeholders, legible pixel textures, and atmospheric lighting
- [ ] Placeholder Experiment character and simple animation
- [ ] First runnable development build and reproducible build instructions

## Milestone 2 — Core loop prototype
- [ ] Define a short, realistic gameplay loop (exploration, objectives, and survival)
- [ ] Interactive objects and basic inventory / item handling as needed
- [ ] Character feedback, dynamic sound layering and audio effects, and a basic UI
- [ ] Save/load decision and quality-of-life controls

## Milestone 3 — Vertical slice
- [ ] One polished short playable section
- [ ] Authorized or original character/level art, animation, and sound
- [ ] Performance baseline, bug testing, and controller/key rebinding where feasible
- [ ] Team review of rights, credits, AI disclosures, and distribution eligibility

## Design references

- [Master document notes](MASTER_DOC_NOTES.md)
- [Art direction](ART_DIRECTION.md)
- [Sound design](SOUND_DESIGN.md)
- [AI contributions](AI_CONTRIBUTIONS.md)

## Out of scope until decided
- Full recreation of all content from the original game
- Networked multiplayer
- Mobile builds
- Automatic reuse/extraction of original-game assets or code

## Definition of done
A task is complete when the change is reviewed, compiles in the pinned Unity version, runs as described, does not add unauthorized content, and documents any remaining limitations.

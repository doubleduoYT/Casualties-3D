# Music and sound direction

**Basis:** Casualties Unknown Fan Project Master Doc (shared excerpt). Listed soundtrack names are *stylistic references*, not files authorized for redistribution.

## Music

- Draw inspiration from **lo-fi**, **synthwave-esque** moods and retro digital textures.
- Consider bitcrushing, static/noise, synth layers, and processing when they convey tension or place.
- Music can change, overlap, crossfade, or be replaced depending on area, injury, and gameplay context.
- Keep music variations deliberately consistent with the game's overall atmosphere.

**Original-game tracks named in the master document as references:**
*Disturbing Discovery*; *Radiation pulse*; *Gaze Into the Pit*; *Dying ..! Death*.

Do **not** upload or reuse the recordings without permission that covers use and distribution.

## Sound effects / ambience

Pursue a believable environment. Suggested audible layers from the master document include:

- Creature movement and nearby activity.
- Flowing water and environmental noise.
- Character heartbeat / panic.
- Cargo pod mechanisms and mechanical movement.
- Dynamic changes to hearing based on injury or effects.

Multiple subtle sounds should coexist naturally; key effects can become prominent during stressful moments.

## Dynamic mixing guidelines

- Separate buses or mixer groups for music, ambience, creature audio, interface, and player state.
- Create gradual filters/attenuation for hearing impairment or other status effects rather than relying only on sudden hard mutes.
- Avoid uncontrolled large volume jumps; preserve the ability to understand gameplay cues.
- Provide basic volume controls and consider a reduced-intensity option for intentionally disorienting effects.
- If VR support is ever pursued, prioritize user comfort and feedback from testers around loudness and disorientation.

## Prototype audio tasks

1. Create **original or properly licensed** placeholder ambience loops.
2. Implement a short music crossfade between two states.
3. Add a subtle environmental emitter and a basic heartbeat layer.
4. Prototype one situational mixer effect (e.g., temporary muffling).
5. Test legibility, sound balance, and performance.

Actual implementation and middleware/audio framework are not yet decided; Unity 6.3 includes built-in audio tools but technical choices belong to the developers.

## Rights and credits

Composer/artist **Smithinghouse** is listed as a project developer in the master document. This does not transfer ownership or grant unconditional redistribution rights. Keep each contributor's explicit permission and credit requirements with audio contributions.

See [ASSET_POLICY.md](ASSET_POLICY.md).

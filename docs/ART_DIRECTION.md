# Art direction — PS1-era low-poly atmosphere

**Basis:** Casualties Unknown Fan Project Master Doc (shared excerpt). This is an art brief, not a mandate to copy original-game assets.

## Look and feel

- **3D retro / PS1-era:** low-poly geometry, deliberately defined sharp edges, simplified forms.
- **Pixel-art influence:** use pixel textures when they strengthen the art direction; UV mapping may be used where appropriate, but is not required for every placeholder.
- **Resolution:** aim for an intentionally low-detail/low-resolution presentation where readable; choose final rendering/scaling techniques during the Unity prototype.
- **Materials:** keep materials relatively simple and avoid relying on high-resolution texture detail.
- **Color:** artists can choose palettes consistent with the scene, anticipating strong lighting effects; balance gritty darkness with selected vibrant accents.
- **Mood:** an isolating, grimdark atmosphere supported by lighting, fog, contrast, and carefully controlled shaders.
- **Legibility:** interactions and dangers should be visually distinguishable. Consider clear silhouettes or tasteful outlines; do not sacrifice readability to darkness.

## Guidance for the first prototype

1. Block out one small environment with original primitive meshes.
2. Experiment with one low-poly placeholder Experiment character.
3. Try pixelated texture sampling and deliberately limited palette.
4. Validate light/shadow readability at a proposed low render resolution.
5. Record screenshots at gameplay scale and ask other artists for feedback.

## Technical decisions not yet finalized

- Built-in/URP/HDRP renderer
- Native vs upscaled internal resolution, and whether pixelation is postprocessed
- Pixel density/texel density and import filtering per texture type
- Outline solution (geometry, shader, post-effect, or no outline)
- Target polygon budgets, lighting modes, and performance floor

These choices should be established collaboratively and tested in Unity 6.3 before being made hard requirements.

## References and permissions

The original master document mentions Terraria at night as a **mood comparison**; that is not a source of licensed content. The shared text did not include its embedded reference images. Do not add extracted original-game files or image assets from references without distribution rights. Each submitted asset needs creator, licensing/permission, and attribution details.

See [ASSET_POLICY.md](ASSET_POLICY.md) and [MASTER_DOC_NOTES.md](MASTER_DOC_NOTES.md).

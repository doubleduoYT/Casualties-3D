# Unity project setup (team checklist)

**Status:** Unity chosen; exact editor version and render pipeline not chosen. The current repository contains collaboration scaffolding, **not yet a runnable Unity game**.

## Decisions needed before creating the project

- [ ] Agree on an exact Unity LTS editor version and record it in \`ProjectSettings/ProjectVersion.txt\`.
- [ ] Choose 3D Built-in, URP, or HDRP. For broad PC support, consider URP, but decide together.
- [ ] Choose target platforms and input approach (e.g. Unity Input System).
- [ ] Confirm base scene and folder naming standards.
- [ ] Agree whether the first milestone uses placeholder art only.

## Creating the initial Unity project

1. Install the chosen editor in **Unity Hub**.
2. Clone this repository with Git and install Git LFS, then run \`git lfs install\`.
3. Create a Unity project with the selected template, using the **repository root** as the Unity project folder. Do not leave the project inside a second nested Unity project directory.
4. In **Edit > Project Settings > Editor**, set:
   - **Version Control / Mode:** Visible Meta Files (where offered)
   - **Asset Serialization / Mode:** Force Text
5. Save project changes. Make sure \`Assets/\`, \`Packages/\` and \`ProjectSettings/\` are included. Ensure the correct \`ProjectVersion.txt\` and \`Packages/manifest.json\` are committed.
6. Make a small sample scene or placeholder scene, verify it opens without errors, and open a PR with your editor version and run instructions.

**Do not manually fabricate Unity scene, prefab, package, or .meta YAML files** as substitutes for Unity-generated files.

## Git / LFS

- Keep all \`.meta\` files, even for moved or renamed assets. Prefer renaming assets inside Unity.
- Git ignore rules exclude engine caches and IDE outputs.
- This repository tracks \`.blend\`, \`.fbx\`, \`.psd\`, \`.tga\`, \`.exr\`, \`.wav\`, \`.flac\`, and \`.mp4\` via Git LFS. Install LFS **before** committing such files; verify the project is within storage quotas.
- On every machine: \`git lfs install\`, then \`git lfs pull\` after cloning when applicable.

## Merge conflicts

Unity \`.unity\`, \`.prefab\`, and \`.meta\` files can be difficult to merge. Coordinate scene ownership and avoid simultaneous editing of the same scene. \`.gitattributes\` names \`unityyamlmerge\`, but it does **not** install/configure UnityYAMLMerge automatically: developers must configure that merge driver locally if they want to use it.

## Optional future automation

Once the exact editor version, build targets, and licenses/secrets are known, consider Unity test/build GitHub Actions. CI is intentionally **not enabled** yet to avoid broken or misleading checks.

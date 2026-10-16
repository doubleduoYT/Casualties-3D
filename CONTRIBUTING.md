# Contributing to Casualties: Unknown 3D

Thank you for helping with this unofficial fan project! Please coordinate before starting major work.

## Before contributing

1. Read the [Unity setup](docs/UNITY_SETUP.md), [team workflow](docs/TEAM_WORKFLOW.md), and [asset policy](docs/ASSET_POLICY.md).
2. Check or open a GitHub Issue describing your planned change.
3. Agree with the team on the Unity editor version, render pipeline, and scope before generating the Unity project or adding packages.
4. Keep original-game files, leaked data, paid assets without redistributable permission, and secrets out of the repository.

## Branches and pull requests

- Branch from updated \`main\` using \`feature/<topic>\`, \`fix/<topic>\`, \`art/<topic>\`, or \`docs/<topic>\`.
- Keep changes focused and reference the Issue when possible.
- Commit Unity \`.meta\` files alongside the assets they refer to.
- Do not commit \`Library/\`, \`Temp/\`, build outputs, local settings, or generated IDE files.
- Open a pull request explaining the change, how it was tested, screenshots/video if relevant, and asset permissions.
- Request review; avoid merging your own large changes without another team member checking them.

## C# conventions (initial proposal)

- Use four spaces, \`PascalCase\` for types/methods/properties, \`camelCase\` for locals and parameters.
- Prefer small, understandable MonoBehaviour scripts with clearly named public or serialized fields.
- Prefer \`[SerializeField] private\` over exposing mutable fields publicly.
- Explain changes that affect performance, persistence, scene structure, or public APIs.

These conventions may change after the team agrees on a technical design.

## Testing

For Unity changes, please note the exact Unity version and platform used. Before requesting merge:

- Confirm there are no new compile errors.
- Test affected gameplay in Play Mode.
- Check scene/prefab references for missing scripts and broken GUIDs.
- Verify the diff does not contain unnecessary generated files.

## Rights and licensing

By submitting material you must have the rights needed to submit it for review and agreed project use. **The repository currently has no open-source license.** Do not assume a contributor's work can be redistributed or relicensed without appropriate permission.

For questions about assets, permissions, and attribution, see [ASSET_POLICY.md](docs/ASSET_POLICY.md).

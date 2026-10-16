# Team workflow

## Coordinating work

- **DoubDu:** project coordination and final scope/integration decisions.
- Other contributors: roles and permissions will be confirmed individually; being in a chat does not automatically grant write/admin access.
- Discuss work in the project's chat, but make important decisions visible in Issues or PRs so later contributors can catch up.

## Board columns (suggested)

`Backlog` → `Ready` → `In Progress` → `Review` → `Done`

## Branch names

- `feature/<short-name>` — new gameplay or tools
- `fix/<short-name>` — bug fixes
- `art/<short-name>` — 3D models, animation, materials, textures
- `docs/<short-name>` — documentation

Avoid pushing unfinished changes straight to `main`. Prefer pull requests and at least one reviewer before merging.

## Communication / reviews

1. Make or select an Issue.
2. Agree on scope and mark who is working on it (avoid two people unknowingly changing the same scene).
3. Make a focused branch and commits.
4. Create a PR using the template, including screenshots/video for visual changes.
5. Review for compile errors, missing assets, permissions, performance, and scope.
6. Merge to `main`; close the linked Issue.

## Version compatibility

The initial Unity project PR must pin the exact editor version. Never upgrade the Unity editor or switch render pipelines in an unrelated feature PR. Discuss version changes first.

## Access

Use the minimum permissions needed: keep administration limited to trusted maintainers. Do not post tokens, secrets, or raw game extraction files in GitHub discussions.

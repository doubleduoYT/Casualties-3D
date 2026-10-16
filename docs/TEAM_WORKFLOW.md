# Team workflow

## Coordinating work

- **DoubDo:** Lead Developer, Programmer (GitHub owner: @doubleduoYT).
- **Smithinghouse:** Composer, Artist.
- **LongMiddle:** Artist.
- **Thundoxa:** Artist.
- **argenalmaz00:** Programmer.
- **Mega Muncher:** Programmer, Artist.
- These are the roles stated in the shared project master document, not confirmed GitHub usernames or repository invitations. GitHub access and ongoing participation must be verified individually.
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
5. Review for compile errors, missing assets, permissions, performance, **AI-use disclosures**, and scope.
6. Merge to `main`; close the linked Issue.

## AI-assisted work

The team permits AI tools, but the master document requires contributors to note any AI-generated or AI-modified work. See [AI contributions policy](AI_CONTRIBUTIONS.md) and use the PR template's disclosure field. Human review and testing remain mandatory.

## Version compatibility

The initial Unity project PR must pin the exact editor version. Never upgrade the Unity editor or switch render pipelines in an unrelated feature PR. Discuss version changes first.

## Access

Use the minimum permissions needed: keep administration limited to trusted maintainers. Do not post tokens, secrets, or raw game extraction files in GitHub discussions.

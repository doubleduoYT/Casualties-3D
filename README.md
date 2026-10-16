# Casualties: Unknown — 3D Fan Remake

> An unofficial, non-commercial fan project inspired by **Casualties: Unknown** by **Orsoniks**.

## Status

**Pre-production / project setup.** This repository is being prepared for team collaboration. **There is no playable Unity build here yet.**

- **Engine:** Unity (the exact editor version and render pipeline are still to be decided by the team).
- **Goal:** Explore a fan-made 3D interpretation of the game's atmosphere, characters, and survival experience.
- **Project coordination:** DoubDu.
- **Contributors:** Welcome after agreeing on project scope and asset ownership.

## Getting started

1. Read [CONTRIBUTING.md](CONTRIBUTING.md) and [the Unity setup guide](docs/UNITY_SETUP.md).
2. Check the [roadmap](docs/ROADMAP.md) and open [Issues](../../issues).
3. Coordinate an assigned task before implementing a major feature.
4. Work on a separate branch and submit a pull request.
5. Once the actual Unity project is committed, clone this repository and open its root folder in **Unity Hub** using the recorded editor version.

> Do **not** create competing Unity projects in this repository before the team settles on a Unity editor version, template, and render pipeline.

## Planned repository structure

When the first Unity project is added, its root should be the repository root:

```text
Assets/              Unity scenes, scripts, art, audio, prefabs (+ .meta files)
Packages/            Unity package manifest and lockfile
ProjectSettings/     Version-controlled Unity project settings
docs/                Design, planning, and onboarding documentation
.github/             Issue and pull request templates
```

Commit `Assets/`, `Packages/`, `ProjectSettings/`, and their required `.meta` files. **Do not commit** generated folders such as `Library/`, `Temp/`, or `UserSettings/`.

## Collaboration

- Use GitHub Issues for tasks and bugs; link pull requests to relevant issues.
- Prefer branches such as `feature/player-controller`, `art/experiment-model`, or `fix/input`.
- Keep `main` as the integration branch. Ask for review before merging changes.
- See [team workflow](docs/TEAM_WORKFLOW.md), [contribution guidelines](CONTRIBUTING.md), and [asset policy](docs/ASSET_POLICY.md).

## Intellectual property and licensing

This is **not** an official Casualties: Unknown project and is not affiliated with or endorsed by Orsoniks. The original game's names, characters, artwork, code, audio, and other protected material belong to their respective rights holders.

**Do not commit extracted original-game assets, proprietary code, or other third-party work without permission covering this use and public distribution.** Keep a record of the source and permission for every imported asset.

**No open-source license has been selected yet.** Public visibility does not grant permission to reuse code or assets. Contributors retain their applicable rights until permissions and licensing are explicitly agreed. See [asset policy](docs/ASSET_POLICY.md).

## Links

- [Roadmap](docs/ROADMAP.md)
- [Unity setup](docs/UNITY_SETUP.md)
- [Team workflow](docs/TEAM_WORKFLOW.md)
- [Report a bug or suggest a feature](../../issues/new/choose)

---
*Fan project; not for sale.*

# AI-generated and AI-modified contributions

The project's master document allows *vibe coding* (AI tools writing or modifying code) but warns that complex generated code can contain errors. **Any AI tool use, for any reason, must be noted**, so contributions remain reviewable and maintainable.

## Required disclosure

When using AI to create, edit, translate, refactor, analyze, or help design project material:

1. Clearly label the relevant Pull Request or Issue with **AI assistance: yes**.
2. State the **tool**, the **files or areas affected**, and **what the tool did** (generation, edit, advice, translation, etc.).
3. Explain **what a human verified or tested**, and what remains unverified.
4. For AI-generated or AI-modified **source code**, add a brief, non-disruptive file/header or nearby comment when practical, pointing to the PR or indicating AI assistance. Avoid inserting comments into Unity serialized YAML or binary assets; document those in the PR and provenance notes instead.
5. Do not upload personal information, private credentials, confidential source code, or unlicensed third-party assets to AI tools.

### Example C# note

```csharp
// AI-assisted: initial movement logic generated with an AI tool.
// Reviewed and tested by <contributor> in Unity 6.3.
// Context: PR #<number>; check movement and collision edge cases.
```

This is an illustrative comment, **not code from the game**. Replace placeholders with real review and test information. Do not claim a test was performed unless it was.

### PR disclosure example

```text
AI assistance: Yes
Tool: ChatGPT
Scope: Suggested audio mixer architecture and revised docs/SOUND_DESIGN.md
Human verification: Team reviewed the audio plan; no Unity runtime test yet
```

## Quality and accountability

AI disclosure does not exempt a contribution from normal code review, licensing, security review, or testing. Contributors remain responsible for what they submit.

## Initial repository documentation disclosure

**2026-10-17:** The initial GitHub repository scaffolding (README, contribution guidelines, Unity setup, workflow, issue/PR templates, and supporting policies) and this master-document adaptation were prepared with **ChatGPT AI assistance** at the project coordinator's request. These are **documentation and Git configuration changes only**. No executable Unity project or gameplay implementation has been created or tested as part of these documentation updates.

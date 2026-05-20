# Unity Showcase project - Tutoring

A small Unity tutoring project built with primitives only. The scene introduces a controllable sphere player, a ground plane, obstacles, barriers, a jump ramp, lighting, and a camera.

## Project Details

- Unity version: `6000.3.9f1`
- Main scene: `Assets/Scenes/PrimitiveShowcase.unity`
- Player script: `Assets/Scripts/PlayerController.cs`
- Controls: `WASD` or arrow keys to move, `Space` to jump

## Quick Start

1. Install Unity Hub.
2. Install or locate Unity Editor `6000.3.9f1`.
3. In Unity Hub, choose `Add` or `Open`.
4. Select this repository folder.
5. Open `Assets/Scenes/PrimitiveShowcase.unity`.
6. Press Play in the Unity Editor.

For the full setup guide, see [docs/setup-and-run.md](docs/setup-and-run.md).

The PowerPoint walkthrough is included at [docs/presentations/unity-showcase-tutoring-guide.pptx](docs/presentations/unity-showcase-tutoring-guide.pptx).

## Repository Notes

This repository intentionally commits only source project files:

- `Assets/`
- `Packages/`
- `ProjectSettings/`
- documentation files

Unity-generated folders such as `Library/`, `Temp/`, `Logs/`, `UserSettings/`, and `outputs/` are ignored because Unity can rebuild them locally.

## Scene Summary

The showcase scene contains:

- Blue sphere player with a Rigidbody and `PlayerController`
- Green cube floor
- Red cube obstacles and side barriers
- Yellow cube ramp for jump testing
- Main camera and directional light

## GitHub Publishing

Recommended public repository name:

```text
Unity-Showcase-project-Tutoring
```

GitHub-safe names normally avoid spaces, so this keeps the requested title while using a URL-friendly repository slug.

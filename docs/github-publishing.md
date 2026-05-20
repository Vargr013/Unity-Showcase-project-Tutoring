# GitHub Publishing Notes

The intended public repository is:

```text
Unity-Showcase-project-Tutoring
```

This name is GitHub-safe while preserving the requested project title: `Unity Showcase project - Tutoring`.

## Files to Commit

Commit these folders and files:

- `Assets/`
- `Packages/`
- `ProjectSettings/`
- `.gitignore`
- `README.md`
- `docs/`

Do not commit Unity-generated local cache folders:

- `Library/`
- `Temp/`
- `Logs/`
- `UserSettings/`
- `outputs/`

## Suggested Publish Commands

After installing and authenticating the GitHub CLI, run:

```powershell
gh auth login
gh repo create Unity-Showcase-project-Tutoring --public --source . --remote origin --push --description "Unity Showcase project - Tutoring"
```

If the repository already exists, add it as the remote and push:

```powershell
git remote add origin https://github.com/Vargr013/Unity-Showcase-project-Tutoring.git
git push -u origin main
```

## Suggested Repository Description

```text
Basic Unity 6 primitive showcase project for tutoring: sphere movement, jumping, obstacles, and setup documentation.
```

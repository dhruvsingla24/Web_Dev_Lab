# P4: GitHub README and Version Tags

## Objective
To understand how to create project documentation using README.md, manage changes using Git, create annotated version tags, and publish releases to GitHub.

## Tools Used
- Git
- GitHub
- Visual Studio Code
- macOS Terminal

## Commands Used

| Command | Purpose |
|---|---|
| `touch README.md` | Creates a README file |
| `code README.md` | Opens README in VS Code |
| `git status` | Checks repository status |
| `git add` | Stages changes |
| `git commit` | Saves changes |
| `git push` | Uploads commits to GitHub |
| `git tag -a` | Creates an annotated version tag |
| `git push origin v1.0.0` | Publishes the version tag |
| `git tag` | Lists available tags |
| `git log --oneline` | Displays commit history |

## Procedure
1. Created `README.md` inside `04-P4-GitHub-README-and-Version-Tags/` using `touch README.md` and opened it with `code README.md`.
2. Documented the objective, tools, Git commands, and step-by-step workflow.
3. Staged, committed, and pushed `README.md` to the `main` branch on GitHub.
4. Created an annotated version tag `v1.0.0` using `git tag -a v1.0.0 -m "First stable release"` and published it with `git push origin v1.0.0`.
5. Verified the tag locally using `git tag` and `git log --oneline`, as well as in the GitHub Tags view.

## Expected Output
```text
v1.0.0
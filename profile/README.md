# AthletesLab

AthletesLab is a nutrition product designed to help people make better everyday food decisions.

## AthletesLab project map

```text
AthletesLab on GitHub
+-- AthletesLab.App          GitHub: AthletesLab/AthletesLab.App
+-- AthletesLab.WebPage      GitHub: AthletesLab/AthletesLab.WebPage
+-- Business                 Local project; no GitHub repository connected
+-- Analytics                Local project; no GitHub repository connected
+-- off-import-worker        GitHub: mariotoorrees/off-import-worker
+-- Marketing-Mario          Local folder: Marketing (name exception)
```

The project names above match the local project folder names, except for Marketing, which appears here as `Marketing-Mario`. The webpage's additional local folders are worktrees of the same repository, not separate projects. `Business` and `Analytics` are currently local-only; `off-import-worker` is in Mario's personal GitHub account rather than the AthletesLab organization. Repository access depends on privacy and GitHub permissions.

## How work moves between people

```text
Mario's computer                         Alex's computer
Local copy of a project                  Local copy of the same project
        |                                          |
        +---------------- GitHub ------------------+
                 Shared online copy and history
```

Mario and Alex each work on a local copy. Changes do not appear on the other person's computer automatically.

1. Make and save changes in your local project folder.
2. Commit the changes to record them in that project's history.
3. Push the commits to GitHub.
4. The other person pulls from GitHub to get those changes.

If both people edit the same part before syncing, Git may ask them to resolve the overlap. Separate branches can help when working on larger changes.

## What GitHub does

GitHub stores the project's code and change history and helps people share updates. It is not where customers use the mobile app or website; those run as separate services.

## Words you may see

- **Repository:** one project's folder and its change history.
- **Local copy:** the project files on someone's computer.
- **Commit:** a saved record of a set of project changes.
- **Push:** send committed changes from a computer to GitHub.
- **Pull:** bring changes from GitHub onto a computer.
- **Branch:** a separate line of work within a project.

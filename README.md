# A02 - Git/GitHub/VS Code Guide

0) Install Applications

* Git: [https://git-scm.com/downloads](https://git-scm.com/downloads)
* VS Code: [https://code.visualstudio.com/](https://code.visualstudio.com/)

1) Make your GitHub account & repo

1. Sign in at [https://github.com](https://github.com)
2. Create New repository named "A02" including README.md

2) Set Github Account Locally

```bash
git config --global user.name "Your Name"
git config --global user.email "you@example.com"
```

3) Git in VS Code

1. Copy your repo URL.
2. Open VS Code -> Source Control view -> Clone Repository.
3. Paste URL -> choose a folder -> Open when prompted.

4) Edit & Save

Open README.md, replace with this guide (or your own), then save.

5) Commit & Push

* Source Control view -> type a message like Task: Create Repository -> Commit -> Sync/Push when prompted.

6) Syncing Repository

* Pull: `Ctrl/Cmd+Shift+P` → “Git: Pull”.
* Fetch: `Ctrl/Cmd+Shift+P` → “Git: Fetch”.


Part 2 - Glossary

* **Branch** = A separate line of development in a repository.
* **Clone** = Make a local copy of a remote repository.
* **Commit** = Saves a snapshot of the project files in the local computer with a description.
* **Fetch** = Bring in remote changes but don't merge them in.
* **GIT** = Version control system.
* **Github** = Collab/hosting site for Git repos.
* **Merge** = Combines changes from one branch into another.
* **Merge Conflict** = Git needs help resolving between two conflicting changes.
* **Push** = Pushes local commits to the remote repository.
* **Pull** = Fetch + merge from remote into your branch.
* **Remote** = Reference to a hosted repository by name.
* **Repository** = Project along with its project full history.


References

* [https://docs.github.com](https://docs.github.com)
* [https://code.visualstudio.com/docs/sourcecontrol/overview](https://code.visualstudio.com/docs/sourcecontrol/overview)

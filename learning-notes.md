# Git concepts

## Working directory, staging area, and repository

1. Edit files in the working directory.
2. Select changes with `git add` to place them in the staging area.
3. Save the staged snapshot with `git commit`.
4. Upload local commits to GitHub with `git push`.

A commit records a snapshot. Five files added in a single commit still create
only one commit. A useful commit groups one related change with a clear message.

## Git and GitHub

Git records version history locally. GitHub hosts a remote repository that can
receive the local history and make it available to others.

## Ignored files

`.gitignore` defines patterns for intentionally untracked files, such as Python
cache files and local environment files. It does not remove files or secrets
that were already committed. Check staged changes before committing.

## Public repository checklist

- Include README.md and .gitignore among at least five tracked files.
- Keep at least five commits in the history uploaded to GitHub.
- Use the exact repository name git-practice and Public visibility.
- Exclude passwords, access tokens, student IDs, and private documents.
- Submit the full repository URL as the Cybercampus post title.

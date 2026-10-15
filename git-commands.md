# Git command reference

## Start and inspect

- `git init -b main`: initialize a repository with a main branch.
- `git status`: inspect tracked and untracked changes.
- `git diff`: inspect unstaged changes.

## Record changes

- `git add <file>`: stage a specific file.
- `git commit -m "Describe the change"`: save staged changes as a commit.
- `git log --oneline`: inspect the commit history.

## Work with files

- `git mv old.txt new.txt`: rename a tracked file.
- `git rm file.txt`: remove a file from the working directory and stage removal.
- `git rm --cached file.txt`: stop tracking a file while keeping the local copy.
- `git restore --staged file.txt`: unstage a file after the first commit.
- `git restore file.txt`: discard unstaged changes to a tracked file.
  This discards local edits, so inspect changes before using it.

## Share on GitHub

- `git remote add origin https://github.com/osm2345679/git-practice.git`
- `git push -u origin main`: upload main and set its upstream branch.
- `git remote -v`: inspect remote addresses.

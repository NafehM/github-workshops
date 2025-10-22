# Git & GitHub — Demo Repository

This repository is a demo for practising Git and GitHub workflows.

## Purpose
- Practice core Git commands, branching, commits, pushes, and pull requests.
- Try common collaboration tasks (review, merge, revert).

## Quick start
1. Clone the repo:
    ```
    git clone <repo-url>
    cd <repo-name>
    ```
2. Create a branch for an exercise:
    ```
    git checkout -b exercise-1
    ```
3. Make changes, stage and commit:
    ```
    git add .
    git commit -m "Describe your change"
    ```
4. Push and open a pull request:
    ```
    git push -u origin exercise-1
    ```

## Suggested exercises
- Exercise 1: Simulate a merge conflict, resolve it, and complete the PR.
- Exercise 2: Use `git rebase` to clean up commits before merging.

## Cheat sheet
- Status: `git status`
- Diff: `git diff`
- Commit: `git commit -m "msg"`
- Branch list: `git branch` / `git branch -r`
- Switch branch: `git checkout <name>` or `git switch <name>`
- Merge: `git merge <branch>`
- Rebase: `git rebase <branch>`
- Pull: `git pull`
- Push: `git push`

## Notes
- Use descriptive commit messages.
- Create small, focused branches for each task.
- Review PRs before merging.

## License
Open for workshop use.

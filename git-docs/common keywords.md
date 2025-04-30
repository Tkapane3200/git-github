🔹 Common Git Keywords & Their Meaning

    init (Initialize)

    Used in git init It creates a new Git repository in the current directory.

    Example: git init initializes an empty Git repository.

    clone (Copy a Repository)

    Used in git clone <repo_url> It downloads an existing repository from a remote source (e.g., GitHub) to your local machine.

    Example: git clone https://github.com/user/repo.git

    status (Show Current State)

    Used in git status It shows the status of files (modified, staged, committed, etc.).

    Example: git status tells you which files are changed but not committed.

    add (Stage Changes)

    Used in git add <file> or git add . It adds files to the staging area, preparing them for commit.

    Example: git add file1.txt → Adds only file1.txt git add . → Adds all modified files

    commit (Save Changes)

    Used in git commit -m "message" It saves changes in Git history with a commit message.

    Example: git commit -m "Added new feature"

    log (View History)

    Used in git log It shows a history of commits in the repository.

    Example: git log → Shows detailed commit history git log --oneline → Shows a shorter version

    branch (Work on Different Versions)

    Used in git branch <branch_name> It creates or lists branches in the project.

    Example: git branch → Shows all branches git branch feature-1 → Creates a new branch named feature-1

    checkout (Switch Branches or Restore Files)

    Used in git checkout <branch_name> It switches between different branches.

    Example: git checkout main → Switches to the main branch. It can also be used to restore files: git checkout -- file1.txt → Discards changes in file1.txt

    merge (Combine Branches)

    Used in git merge <branch_name> It combines changes from another branch into the current branch.

    Example: git merge feature-1 → Merges feature-1 into the current branch.

    push (Upload to Remote Repository)

    Used in git push origin <branch_name> It uploads commits from your local repository to the remote (GitHub, GitLab, etc.).

    Example: git push origin main → Uploads the main branch to remote.

    pull (Download & Merge Changes)

    Used in git pull origin <branch_name> It fetches the latest changes from the remote repo and merges them into your local branch.

    Example: git pull origin main

    fetch (Download Changes Without Merging)

    Used in git fetch It downloads changes from the remote repository but doesn’t merge them. Example: git fetch origin

    reset (Undo Changes)

    Used in git reset It removes commits or unstages files.

    Examples: git reset HEAD1 → Removes the last commit but keeps the changes git reset --hard HEAD1 → Completely removes the last commit and changes

    revert (Undo a Commit with a New Commit)

    Used in git revert <commit_hash> It undoes a specific commit by creating a new commit that cancels out the previous one.

    Example: git revert abc123 → Reverts the commit with ID abc123

    stash (Save Work Temporarily)

    Used in git stash It saves your uncommitted changes temporarily and restores a clean working directory.

    Example: git stash → Stashes current changes git stash pop → Applies the last stashed changes

    cherry-pick (Copy a Specific Commit to Another Branch)

    Used in git cherry-pick <commit_hash> It applies a specific commit from another branch without merging the whole branch.

    Example: git cherry-pick abc123 → Applies commit abc123

    rebase (Rewrite Commit History)

    Used in git rebase <branch_name> It moves commits from one branch onto another, cleaning up history.

    Example: git rebase main

    tag (Label a Version)

    Used in git tag <tag_name> It marks a specific commit as a release version.

    Example: git tag v1.0

    clean (Remove Untracked Files)

    Used in git clean -f It removes untracked files from the working directory.

    Example: git clean -n (preview) → git clean -f (force delete)

    remote (Manage Remote Repositories)

    Used in git remote It manages connections to remote repositories like GitHub.

    Example: git remote -v → Lists remote repositories git remote add origin → Adds a remote repository

🔹 Summary Table

init: Initialize a repository

clone: Copy a repository from remote

status: Show current file status

add: Stage files for commit

commit: Save changes to the repository

log: View commit history

branch: Create or list branches

checkout: Switch branches or restore files

merge: Combine branches

push: Upload changes to remote repo

pull: Download and merge remote changes

fetch: Download changes without merging

reset: Undo changes

revert: Undo a commit with a new commit

stash: Save changes temporarily

cherry-pick: Apply a specific commit

rebase: Rewrite commit history

tag: Mark a version

clean: Remove untracked files

remote: Manage remote repositories

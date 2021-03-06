# Farzaneh.Git-101
| Command | Definition |
| --- | --- |
| branch | A branch is essentially is a unique set of code changes with a unique name. Each repository can have one or more branches. The main branch — the one where all changes eventually get merged back into, and is called master |
| check out | Checkout is the command used to switch between the different branches of a GitHub repository. When a branch is checked out, all files in the working directory are updated to match the versions stored in that branch |
| commit | git commit creates a commit, which is like a snapshot of your repository. These commits are snapshots of your entire repository at specific times. You should make new commits often, based around logical units of change|
| fast-forward | Fast forward merge can be performed when there is a direct linear path from the source branch to the target branch. In fast-forward merge, git simply moves the source branch pointer to the target branch pointer without creating an extra merge commit |
| fetch | The git fetch command downloads commits, files, and refs from a remote repository into your local repo. Fetching is what you do when you want to see what everybody else has been working on |
| head | This is like the pointer to the current branch reference, which is in turn a pointer to the last commit you made or the last commit that was checked out into your working directory. That also means it will be the parent of the next commit you do |
| merge | Merging is Git's way of putting a forked history back together again. The git merge command lets you take the independent lines of development created by git branch and integrate them into a single branch |
| remote | This is like a common repository that all team members use to exchange their changes. In most cases, such a remote repository is stored on a code hosting service like GitHub or on an internal server. In contrast to a local repository, a remote typically does not provide a file tree of the project's current state |
| origin/up-stream/down-stream | upstream is where you cloned from (the origin). Downstream is any project that integrates your work with other works. The terms are not restricted to Git repositories |
| pull | This command let you tell others about changes you've pushed to a branch in a repository on GitHub. Once a pull request is opened, you can discuss and review the potential changes with collaborators and add follow-up commits before your changes are merged into the base branch |
| push | This command used to upload local repository content to a remote repository. Pushing is how you transfer commits from your local repository to a remote repo. It's the counterpart to git fetch , but whereas fetching imports commits to local branches, pushing exports commits to remote branches |
| repository | A repository contains all of your project's files and each file's revision history. You can discuss and manage your project's work within the repository.You can own repositories individually, or you can share ownership of repositories with other people in an organization.You can restrict who has access to a repository by choosing the repository's visibility. |
| stash | The git stash command takes your uncommitted changes (both staged and unstaged), saves them away for later use, and then reverts them from your working copy |



| Word      | Definition |
| ----------- | ----------- |
| clone | Clone command is used to create a copy of a remote repository. |
| Rebase | Rebase is to aused to apply a sequence of commits from distinct branches into a final commit. |
| Cherrypick | Cherrypick allows you to integrate selected, individual commits from any branch into your current branch. |

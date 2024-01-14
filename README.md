Explain version control:
Version control is a system that helps track changes in files and code over time. 
It is commonly used in software development but can also be applied to any project where multiple people collaborate on documents or files. 
The primary purpose of version control is to manage different versions of files, 
allowing contributors to work on their own copies independently and merge their changes seamlessly.


Diffrence between Git and GitHub:
Git is a version control system that allows developers to track changes in their code. 
GitHub is a web-based hosting service for git repositories.

Other 3 GitHub alternatives are:
1, SourceForge
2, GitBucket
3, LaunchPad

Diffrence between Git fetch and Git pull:
Git pull:
* git pull copies changes from a remote repository directly into your working directory.
* it automatically merges the changes into your current branch and updates your working directory.

Git fetch: 
* The git fetch command only copies changes into your local Git repo.
* Does not automatically merge or update your working directory with the changes. It only brings the changes to your local repository, allowing you to decide when and how to integrate them.

Explain Git Rebase:
 Git Rebase allows you to easily change a series of commits, modifying the history of your repository.

 Command for Git Rebase: git rebase feature-branch

 Explain Git Cherry pick:
 git cherry-pick is a Git command that allows you to take a specific commit from one branch and apply it onto another branch.

 Command for Git Cherry pick: git cherry-pick <commit-hash>

Replace <commit-hash> with the actual hash of the commit you want to cherry-pick. This command will take the changes introduced by that commit and apply them to your current branch.

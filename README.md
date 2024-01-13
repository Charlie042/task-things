# task-things

## Explain Version control
Version control or Source control is the practise of tracking and managing changes to files.

### Explain the difference between git and git hub
 Git is a version control system that you use locally on your system, which allows developers to track changes in their code.
 Github is a hosting platform for git repositories providing a centralized location for collaboration,code review and project management.

 ### List 3 other github alternatives
 * Gitlab
 * Bitbucket
 * OneDev

 ### Explain the difference between git fetch and git pull
* Git fetch is used to download new branches and objects from the remote repository but does not automatically update the working directory or merge any changes. It only updates the remote-tracking branches in your local repository. 

* Git pull on the other hand is used to download new branches and objects from the remote respository and automatically updates the working directory or merge changes.

### Explain in simple terms git rebase and the command for it
* Git rebase is a Git command that helps you incorporate changes from one branch into another by moving or combining the commits in a more linear and neat way.

* Command for it is as follows
git rebase [-i | --interactive] [ options ] [--exec cmd] [--onto newbase | --keep-base] [upstream [branch]]

### Explain in simple terms git cherry-pick and the command for it 
Git cherry-pick is a Git command that allows you to pick or copy a specific commit from one branch and apply it onto another branch.

* command for it is as follows: git cherry-pick<commit-hash>

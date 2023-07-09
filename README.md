# Intro_github3.2
## _My Basic Github Project 2_

Welcome to my page

## What is GitHub Authentication and how what methods available to be implemented?

There are several methods available to implement GitHub Authentication:

- Username and Password: This is the most basic authentication method where users provide their GitHub username and password to authenticate. However, this method is considered less secure and is not recommended for automated systems or third-party applications.

- Personal Access Tokens: Personal Access Tokens (PATs) are an alternative to using passwords for authentication. Users can generate a PAT from their GitHub account settings, and it can be used as a password replacement to authenticate API requests or access repositories.

- OAuth Apps: OAuth (Open Authorization) is a widely used protocol that allows third-party applications to access resources on behalf of users without directly obtaining their credentials. GitHub provides OAuth Apps as a way for developers to integrate their applications with GitHub. Users can authorize an OAuth App to access their GitHub account, and the app receives an access token that can be used for authentication.

- GitHub Apps: GitHub Apps are another way for developers to integrate their applications with GitHub. Unlike OAuth Apps, GitHub Apps can have more granular access permissions and can interact with repositories and other GitHub resources. GitHub Apps use a private-public key pair for authentication.

- Web Application Flow: This method involves implementing a web application that acts as an intermediary for authentication. Users are redirected to the GitHub login page, where they enter their credentials. After successful authentication, GitHub redirects the user back to the application with an authorization code. The application can then exchange this code for an access token, allowing it to make API requests on behalf of the user.

- Device Flow: The Device Flow is an authentication method suitable for devices with limited input capabilities, such as smart TVs or game consoles. It involves displaying a verification code on the device and instructing the user to visit a specific URL on their computer or mobile device to authenticate using their GitHub account.

These methods provide various levels of security and flexibility depending on the requirements of your application. The choice of method depends on factors such as the type of application, user experience, and the level of access required. GitHub provides detailed documentation and libraries for various programming languages to help developers implement these authentication methods effectively.

## List out 15 github commands & usage

|no. | Command |Desciption   | Usage  |
|----| ------- | ----------- |--------|
|1. | `git clone` | Clones a remote repository to your local machine.|git clone <repository URL>|
|2. | `git init` | Initializes a new Git repository in the current directory. |git init|
|3. | `git add` |Adds changes or new files to the staging area. | git add <file>|
|4. | `git commit`| Commits the staged changes to the repository. | git commit -m "Commit message"|
|5. | `git push` | Uploads local commits to a remote repository. | git push <remote> <branch> |
|6. | `git pull` | Fetches and merges changes from a remote repository to your local repository. | git pull <remote> <branch>|
|7. | `git branch`| Lists, creates, or deletes branches. |  List branches: git branch; Create branch: git branch <branch-name>; Delete branch: git branch -d <branch-name>|
|8. | `git checkout`| Switches between branches or restores files from a commit. | Switch branch: git checkout <branch-name>; Restore files: git checkout <commit> <file> |
|9. | `git merge` | Combines changes from one branch into another branch. | git merge <branch-name> |
|10.| `git status` | Shows the status of the working directory and staged files. | git status |
|11.| `git log` | Displays the commit history. | git log |
|12.| `git remote` | Manages remote repositories. | - List remotes: git remote -v  - Add remote: git remote add <name> <repository URL> - Remove remote: git remote remove <name> |
|13.| `git fetch` | Retrieves changes from a remote repository without merging. | git fetch <remote>|
|14.| `git revert` | Creates a new commit that undoes the changes of a previous commit. | git revert <commit> |
|15.| `git stash` | Temporarily saves changes that are not ready to be committed. | - Save changes: git stash, - Apply changes: git stash apply, - Discard changes: git stash drop |

## The 4 Github commands that I think I will use the most in the real project and why?
Answer:  In a real project, there are several GitHub commands that are frequently used. Here are four commands that are commonly used and why they are essential:

- git clone: This command is used to clone a remote repository to your local machine. It is often the first command you use when starting a new project or when collaborating with others. Cloning a repository allows you to have a local copy of the codebase and enables you to make changes, track version history, and contribute to the project.

- git pull: The git pull command is used to fetch and merge changes from a remote repository to your local repository. It is commonly used to update your local repository with the latest changes made by others. By pulling the changes, you can ensure that you have the most up-to-date version of the codebase and avoid conflicts when working in a team.

- git add: The git add command is used to stage changes or new files for commit. It allows you to selectively choose which changes you want to include in the next commit. By adding files to the staging area, you can carefully control what changes are committed and keep your commits organized and meaningful.

- git push: The git push command is used to upload local commits to a remote repository. It is used to share your changes with others and make them available to the rest of the team. Pushing your commits allows for collaboration and ensures that your work is integrated into the shared codebase.

These four commands (clone, pull, add, and push) are fundamental for working with Git and GitHub in real projects. They enable collaboration, version control, and the seamless sharing of code changes with others. By mastering these commands, you can effectively contribute to projects, stay updated with the latest changes, and maintain a well-organized version history.

### Resource
- Dillinger
- https://www.freecodecamp.org/news/10-important-git-commands-that-every-developer-should-know/
- https://training.github.com/
- https://dzone.com/articles/top-20-git-commands-with-examples
- Work based on -6m-cloud-3.2-introduction-to-git-ii/edit/main/assignment.md

```markdown
# Git Assignment - shwetasharma14
```

## a. What is an _issue_?
An issue can be created in a git repo to track and plan a piece of work.
    
## b. What is a _pull request_?
A pull request is a proposal to merge a set of changes from one branch into another. In a pull request, collaborators can review and discuss the proposed set of changes before they integrate the changes into the main codebase.

## c. Describe the steps to open a _pull request_?
1. Create a feature branch from the main branch.
2. Commit the code to the feature branch.
3. Got to Github and click on New Pull Request button.
4. Verify the branch which the code will be merged to correct and is the intended branch to merge into like main.
5. Verify the files and see if the correct code is being committed.
6. Click on Create Pull Request button.

## d. Describe the steps to add a collaborator to a repository (share write permissions)
1. Go to Your Repository: Navigate to the repository on GitHub where you want to add a collaborator.
2. Settings: Click on the "Settings" tab, which is usually located at the top of the repository page.
3. Manage Access: In the left sidebar, click on "Manage access."
4. Invite a Collaborator: Click on the "Collaborators" link in the side navigation. Click on Add People button.
5. Enter Username: Type the GitHub username or email address of the person you want to add as a collaborator.
6. Send Invitation: Click "Add [username] to this repository" to send an invitation. The user will receive an email with a link to accept the invitation.
7. Acceptance: Once the user accepts the invitation, they will have access to the repository based on the permissions you set.

## e. What is the difference between `git` and `GitHub`?
### Git 
Git is a version control system which manages and tracks changes to source code during software development. It allows multiple developers to work on the same project without overwriting each other's changes. Git is installed locally on your computer. It uses commands like git commit, git push, git pull, etc.

### GitHub 
Github is a web-based platform. It hosts Git repositories online, providing a collaborative environment. It facilitates code sharing, collaboration, and version control through a web interface. Github offers additional tools like issue tracking, project management, and continuous integration. It is accessible via a web browser and integrates with Git.

## f. What does `git diff` do?
### Unstaged Changes: 
git diff shows changes between your working directory and the staging area.

### Staged Changes: 
git diff --staged or git diff --cached shows changes between the staging area and the last commit.

### Between Commits: 
git diff commit1 commit2 shows changes between two commits.

### Specific Files: 
git diff [file] shows changes in a specific file.

## g. What is the `main` branch?
    This is the default branch created for each git repo. This branch is used to create all feature branches. The feature branches are merged back into the main branch through the pull requests. The main branch is used to send code to the environments.

## h. Besides our initial commit if it is a new repository, should we directly push our changes directly into the `main` branch?
    No we should not push changes directly to the main branch. Feature branches should be created to commit code into. The feature branches should then be merged to the main branch through pull requests. This allows reviewers to review the code and provide feedback which can be corrected before committing the code to the main branch.
# Static CV Website – DS1
A collaborative static website created using HTML & CSS by a team of 4 as part of our DS1 DevOps project.

## Files:
- accueil.html
- information.html
- parcours.html
- experience.html
- contact.html
- couleur.css

## Git Workflow:
- Branch per feature
- Pull requests for merges
- Team reviews for every PR

## Git Commands Used
# 1. Initialize a Repository
`git init`

Creates a new Git repository locally. This is the first step to set up version control.

# 2. Add Files to Staging
`git add <file-name>
git add .`

Moves files to the staging area, preparing them for a commit. Use git add . to add all files.

# 3. Commit Changes
`git commit -m "Your message here"
`
Saves changes to the repository with a descriptive message explaining the updates.

# 4. Push Changes to Remote Repository
`git push origin <branch-name>
`
Uploads local changes to the remote repository. Ensure the branch name corresponds to your current branch.

# 5. Create and Switch Branches
`git branch <branch-name>
git checkout <branch-name>
git checkout -b <branch-name>
`
git branch creates a new branch. git checkout switches branches, while git checkout -b creates and switches simultaneously.

# 6. Pull Changes from Remote Repository
`git pull origin <branch-name>
`
Fetches changes from the remote repository and integrates them into your current branch.

# 7. Merge Branches
`git merge <branch-name>
`
Combines the specified branch into your current branch.

# 8. Resolve Merge Conflicts
Manually resolve conflicts in files after Git highlights differences. Use commands like:
`git add <file-name>
git commit -m "Resolved merge conflict"
`
# 9. View Repository Status
`git status
`
Displays the current state of your repository, including staged, unstaged, and untracked files.

# 10. Set Remote Repository
`git remote add origin <repository-url>
`
Links your local repository to a remote repository hosted on GitHub.

# 11. Clone a Repository
`git clone <repository-url>
`
Copies a remote repository to your local machine.

# 12. List All Branches
`git branch -a
`
Displays all branches, both local and remote.

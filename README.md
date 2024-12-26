# Learn Git and GitHub

## Recent Updates: 
- I have changed the default branch to dev
- all the changes will be updated in to dev branch
- most git repos uses dev (development branch), where all on going changes are updated in dev branch
- so that main branch will be stable and isolated from the constantly updating dev branch
- main branch is used for production ready environment


## TASK-3 Collaborate on the dev Branch and Merge to main
This task is designed to strengthen collaboration while ensuring the repository maintains a clean structure. Everyone will contribute to the dev branch, and once finalized, changes will be merged into main.

### Steps to Follow

### 1. Pull the Latest Changes from dev
- Make sure your local repository is up-to-date with the latest work on the dev branch
```bash
git checkout dev
git pull origin dev
```
- This ensures you don’t overwrite any updates from other teammates.

### 2. Make Changes in Teammates Folders
- Navigate to the folder of a teammate in the repository:
```bash
cd <teammate-folder-name>
```
- Add a notes.txt file or update an existing file (like README.md) with feedback, suggestions, or additional learning resources. Example:
```bash
echo "This folder looks great! Adding a suggestion for improvement." >> notes.txt
```
### 3. Commit Your Changes
- After making changes, stage and commit them:
```bash
git add .
git commit -m "Added notes.txt with feedback to <teammate-folder-name>"
```
- Keep your commit messages clear and concise.

### 4. Push Changes to the dev Branch
- Push your changes back to the dev branch:
```bash
git push origin dev
```
### 5. Create a Pull Request to Merge dev into main
- Go to your GitHub repository: Learning-Root.
- Click on the "Pull Requests" tab and select "New Pull Request".
- Choose dev as the source branch and main as the target branch.
- Provide a meaningful title and description for your PR. For example:

> Title: "Merged updates and feedback from the dev branch into main"

> Description: This PR includes feedback, additional notes, and minor improvements to the folders in the repository. All changes were reviewed collaboratively on the dev branch.

### 6.  Review and Merge the Pull Request
- Discuss any suggestions or conflicts directly on GitHub.
- Once approved, merge the PR into the main branch.



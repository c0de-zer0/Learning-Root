# Learn Git and GitHub

## Introduction to Git and GitHub

**Git** is a distributed version control system that allows developers to track changes in source code during software development. It helps in managing and coordinating multiple developers working on the same project without conflicts.

**GitHub** is a cloud-based platform that hosts Git repositories and enables collaboration among developers. It provides version control and allows developers to share code, contribute, and manage their projects.

Other platforms like **GitLab** and **Bitbucket** offer similar functionalities to GitHub, with some added features and differences. GitLab is often used for CI/CD pipelines, and Bitbucket is integrated with Atlassian tools like Jira.

### Key Concepts

- **Repository (Repo):** A repository is where your project files, along with their revision history, are stored. You can create a repository to start tracking your project's changes with Git.
  
- **Branch:** A branch is a parallel version of the repository that allows you to work on different features or fixes without affecting the main codebase (often called `main` or `master`).
  
- **Commit:** A commit is a snapshot of your changes in the repository, representing a point in history that you can refer back to.

- **Pull Request (PR):** A pull request is a request to merge changes from one branch into another (usually from a feature branch into the main branch) on GitHub. It allows others to review your code before merging it.

### GitLab and Bitbucket

- **GitLab** is similar to GitHub but offers built-in CI/CD, better integration for DevOps pipelines, and private repositories.
- **Bitbucket** is another Git repository management platform that integrates well with Jira and Confluence, focusing more on private repositories.

---

## Resources to Learn Git and GitHub

### Books
1. [Pro Git](https://git-scm.com/book/en/v2)

### YouTube Tutorials

1. [Git and GitHub for Beginners - freeCodeCamp](https://youtu.be/RGOj5yH7evk?si=QVI_63lAWpdt8Kt1)
2. [Git for Dummies](https://youtu.be/mJ-qvsxPHpY?si=b7lc_Gm7x3bA4UUc)
3. [Git and GitHub Crash Course](https://www.youtube.com/watch?v=SWYqp7iY_Tc)

### Blogs

1. [Intro to Git and GitHub](https://product.hubspot.com/blog/git-and-github-tutorial-for-beginners)
2. [Tutorial of Git and GitHub for Basic to Advanced](https://medium.com/@sachinsoni600517/complete-tutorial-of-git-and-github-for-basic-to-advanced-1dd34d12b90b)
3. [freeCodeCamp](https://www.freecodecamp.org/news/the-beginners-guide-to-git-github/)

---

## Practice Tasks to Learn Git and GitHub

### Task 1: Basic Workflow

1. **Clone the Repository:**
   - Clone the repository to your local machine using the following command:
     ```bash
     git clone https://github.com/c0de-zer0/Learning-Root.git
     ```
   - Navigate into the cloned repository:
     ```bash
     cd Learning-Root
     ```

2. **Create a New Branch:**
   - Create and switch to a new branch with the format `name_favnumber`, where `name` is your name and `favnumber` is your favorite number (e.g., `john_7`):
     ```bash
     git checkout -b [name_favnumber]
     ```

3. **Create a Folder and Add a File:**
   - Create a folder named after your name:
     ```bash
     mkdir [name]
     ```
   - Navigate into the folder and create a text file:
     ```bash
     cd [name]
     ```
   - Create a file `task1.txt`:
     ```bash
     touch task1.txt
     ```
   - Add content to `task1.txt`, indicating the task is complete (e.g., `Task 1 is done`).

4. **Stage, Commit, and Push Changes:**
   - Stage the new file:
     ```bash
     git add task1.txt
     ```
   - Commit the changes:
     ```bash
     git commit -m "Task 1: Created task1.txt"
     ```
   - Push the changes to the remote repository:
     ```bash
     git push origin [name_favnumber]
     ```

5. **Create a Pull Request:**
   - Go to the repository's GitHub page: [Learning-Root Repository](https://github.com/c0de-zer0/Learning-Root)
   - Click on "Compare & pull request."
   - Add a title and description for your pull request.
   - Click "Create pull request."

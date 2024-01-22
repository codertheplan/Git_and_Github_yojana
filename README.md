# Welcome to the Git and Github Workshop Repository

This repository is dedicated to helping you learn about version control using Git and Github. Follow the steps below to make your first pull request and contribute to this project.

## How to Contribute

### Step 1: Fork the Repository

Click the "Fork" button on the upper right corner of the GitHub repository page.

### Step 2: Clone the Repository to Your Local Machine

Open your terminal and use the following command to clone the repository to your local machine:

```bash
git clone https://github.com/your-username/repository.git
```

## Create a New Branch:

1. Change into the repository's directory:
    ```bash
    cd repository
    ```
2. Create a new branch for your changes:
    ```bash
    git checkout -b new-branch-name
    ```

## Make Changes and Commit:

- Make the necessary changes to the code or add new files.
- Stage your changes:
    ```bash
    git add .
    ```
- Commit the changes:
    ```bash
    git commit -m "Descriptive message about the changes"
    ```

## Push Changes to Your Forked Repository:

- Push your changes to the new branch on your forked repository:
    ```bash
    git push origin new-branch-name
    ```

## Create a Pull Request:

1. Go to your forked repository on GitHub.
2. Switch to the newly created branch.
3. Click on the "New Pull Request" button.
4. Provide a descriptive title and comment about your changes.
5. Click "Create Pull Request."

## Await Review and Merge:

- Wait for the repository owner to review your pull request.
- If changes are requested, make them on your local branch and push the changes.
- Once approved, your changes will be merged into the main repository.

## Sync Fork (Optional):

- To keep your fork up-to-date with the original repository, add the original repository as a remote:
    ```bash
    git remote add upstream https://github.com/original-username/repository.git
    ```
- Fetch the changes:
    ```bash
    git fetch upstream
    ```
- Merge the changes into your local main branch:
    ```bash
    git merge upstream/main
    ```
- Push the updated changes to your fork:
    ```bash
    git push origin main
    ```

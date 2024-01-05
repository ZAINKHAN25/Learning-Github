# Learning-GitHub

Hello everyone! If you're new to GitHub and want to learn how to push your code for the first time, you're in the **right** readme file. In this guide, you will learn the basics of pushing your code to GitHub. I've included images for each step to make it easier for you. (Thanks!)

## Getting Started

These instructions will guide you through the process of pushing your code to GitHub for the first time.

### Prerequisites

Make sure you have the following installed:

- Git: [Download Git](https://git-scm.com/downloads)

### Steps

1. **Create a GitHub Account:**
   If you don't have a GitHub account, you can create one [here](https://github.com/).

2. **Create a New Repository:**
   - Click on the "+" sign in the top right corner.
   - Select "New Repository."
   - Fill in the repository name and description.
   - Click on "Create repository."

3. **Initialize a Git Repository:**
   - Open your terminal.
   - Navigate to your project folder:
     ```bash
     cd /path/to/your/project
     ```
   - Run the following commands:
     ```bash
     git init
     git status
     git add .
     ```

4. **Create a New Branch:**
   - Create a new branch for your changes:
     ```bash
     git branch feature-branch
     git checkout feature-branch
     ```

5. **Commit Changes:**
   - Add the files to the staging area:
     ```bash
     git add .
     ```
   - Commit the changes:
     ```bash
     git commit -m "Initial commit"
     ```

6. **Configure Git Credentials (Windows Only):**
   - If you encounter credential issues on Windows, configure your Git credentials using:
     ```bash
     git config --global credential.helper manager
     ```

7. **Push to GitHub:**
   - Push your code to GitHub:
     ```bash
     git push origin feature-branch
     ```

8. **Remove Git Credentials (Windows Only):**
   - If you need to update or remove credentials on Windows, you can do so in the Credential Manager.

That's it! Your code is now on GitHub.

## Support

If you encounter any issues or have questions, feel free to reach out via [email](mailto:your.email@example.com).

## Acknowledgments

Thank you for using this guide. Happy coding!

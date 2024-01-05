# Learning-GitHub-For-Beginner's

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
     ```

     This command initializes a hidden file in your project, responsible for Git-related operations.

     ```bash
     git status
     ```

     If the result is shown in red, use `git add .` to stage the changes. If it's green, proceed to the next step. If the result is "nothing to commit, working tree clean," your code is up to date, and you don't need to push.

     ```bash
     git add .
     ```

     Now, commit your changes:

     ```bash
     git commit -m "Your commit name"
     ```

     Select a branch:

     ```bash
     git branch -M main
     ```

     Add the remote origin to your project:

     ```bash
     git remote add origin https://github.com/YourAccountName/YourRepositoryName.git
     ```

     Finally, push your code:

     ```bash
     git push -u origin main
     ```

4. **Push Changes to GitHub:**
   - After making changes to your code:
     ```bash
     git status
     ```
     If the result shows modified files in red, proceed to the next steps.

     ```bash
     git add .
     ```

     Commit the changes:

     ```bash
     git commit -m "Description of your changes"
     ```

     Replace "Description of your changes" with a brief and meaningful message describing the changes you made.

     Push the changes to GitHub:

     ```bash
     git push
     ```

     If you are on the `main` branch, you can use `git push origin main`. If you are on a different branch, replace `main` with the name of your branch.

That's it! Your code is now on GitHub.

## Support

If you encounter any issues or have questions, feel free to reach out via [email](mailto:your.email@example.com).

## Acknowledgments

Thank you for using this guide. Happy coding!

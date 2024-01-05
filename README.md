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

3. **Clone the Repository:**
   - Click on the "Code" button in your new repository.
   - Copy the repository URL.
   - Open your terminal and run:
     ```bash
     git clone <repository-url>
     ```

4. **Add your Code:**
   - Move your project files into the cloned repository folder.

5. **Commit Changes:**
   - In your terminal, navigate to the repository:
     ```bash
     cd <repository-folder>
     ```
   - Add the files to the staging area:
     ```bash
     git add .
     ```
   - Commit the changes:
     ```bash
     git commit -m "Initial commit"
     ```

6. **Push to GitHub:**
   - Push your code to GitHub:
     ```bash
     git push origin main
     ```

That's it! Your code is now on GitHub.

## Support

If you encounter any issues or have questions, feel free to reach out via [email](mailto:your.email@example.com).

## Acknowledgments

Thank you for using this guide. Happy coding!

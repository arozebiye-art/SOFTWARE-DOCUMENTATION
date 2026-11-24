# SOFTWARE-DOCUMENTATION
A) User Manual Procedure: Creating a GitHub Repository and Making the First Commit
1. Purpose
This procedure explains how a first-semester computing student can create a GitHub repository, connect it to a local project folder, and make the first commit. GitHub is an online platform used to store, manage, and share code.
2. Prerequisites
Before starting, the reader needs:
- A computer with internet access.
- A GitHub account.
- Git installed on the computer.
- A text editor such as Visual Studio Code.
- Basic knowledge of using the command line (Terminal or Command Prompt).
3. Step-by-Step Procedure
Step 1: Open the GitHub website.
- Action: Open a web browser and visit https://github.com.
- Expected result: The GitHub homepage appears.
Step 2: Sign in to GitHub.
- Action: Enter your GitHub username and password and click Sign in.
- Expected result: Your GitHub dashboard opens.
Step 3: Create a new repository.
- Action: Click the New button or the plus (+) icon and select New repository.
- Expected result: The repository creation page appears.
Step 4: Enter a repository name.
- Action: Type a name for your project, for example, my-first-project.
- Expected result: The repository name appears in the name field.
Step 5: Choose repository visibility.
- Action: Select Public as the repository visibility.
- Expected result: The repository is configured to be publicly accessible.
Step 6: Create the repository.
- Action: Click Create repository.
- Expected result: GitHub creates the repository and displays its setup instructions.
Step 7: Open the project folder on your computer.
- Action: Open Terminal or Command Prompt and navigate to your project folder.
- Expected result: The command line is positioned inside your project folder.
Step 8: Initialize Git.
- Action: Run the command git init.
- Expected result: Git initializes a new repository in the project folder.
Step 9: Add project files to Git.
- Action: Run the command git add ..
- Expected result: All eligible project files are staged for committing.
Step 10: Make the first commit.
- Action: Run the command git commit -m "Initial commit".
- Expected result: Git creates the first commit and records the staged changes.
Step 11: Connect the local repository to GitHub.

- Action: Run the following command, replacing the URL with your own repository URL:
git remote add origin https://github.com/YOUR-USERNAME/my-first-project.git


- Expected result: Your local Git repository is connected to the GitHub repository.

Step 12: Set the main branch name.
- Action: Run git branch -M main.
- Expected result: The current branch is named main.
Step 13: Upload the commit to GitHub.
- Action: Run git push -u origin main.
- Expected result: Your committed project files appear in your GitHub repository.
4. Screenshot Description
The screenshot should show the GitHub repository page after successfully uploading the project.

It should include:
- The repository name (my-first-project).
- The list of uploaded project files.
- The main branch.
- The latest commit message, Initial commit.
This screenshot provides evidence that the repository was successfully created and the first commit was uploaded.
5. Troubleshooting
Common problem: Authentication failed when pushing to GitHub.

This happens when GitHub cannot verify your identity.

Solution:
1. Check that the repository URL is correct.
2. Sign in to GitHub in your browser.
3. If using HTTPS with Git credentials, authenticate using GitHub's supported sign-in method or a Personal Access Token instead of your account password.
4. Try running git push -u origin main again.
6. Conclusion
Following these steps allows a beginner to create a GitHub repository, initialize Git locally, save project files in a commit, and upload them to GitHub. GitHub helps students track changes, back up their work, and collaborate with others.

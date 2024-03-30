# TASK-6-WORKING-WITH-GITHUB
Working with GitHub involves several key steps, including creating a repository, committing changes, creating branches, merging branches, collaborating with others, and managing issues. Here's an overview of these steps:

# Creating a Repository:

Go to GitHub and sign in to your account.
Click on the "New" button to create a new repository.
Give your repository a name, choose whether it's public or private, add a description if needed, and select options like initializing with a README file or adding a license.
Click on the "Create repository" button to create your repository.
Cloning a Repository:

To work with an existing repository on your local machine, you'll need to clone it. Go to the repository on GitHub.
Click on the "Code" button and copy the repository URL.
Open your terminal or command prompt, navigate to the directory where you want to clone the repository, and use the git clone command followed by the repository URL.
Adding and Committing Changes:

Make changes to your files in the cloned repository on your local machine.
Use the git status command to see which files have been modified.
Stage the changes using git add <file> for individual files or git add . to add all changed files.
Commit the changes using git commit -m "Commit message".
Creating Branches:

Use branches to work on new features or fixes without affecting the main codebase.
Create a new branch using git checkout -b <branch-name>.
Merging Branches:

After making changes and committing them on a branch, you can merge that branch into the main branch or another target branch.
Switch to the target branch using git checkout <target-branch>.
Merge the changes from your branch using git merge <branch-to-merge>.
Collaborating and Pushing Changes:

To collaborate with others, you can push your changes to the remote repository.
Use git push origin <branch-name> to push your changes to a specific branch on GitHub.
Managing Issues:

GitHub provides a way to track and manage issues related to your repository.
You can create issues, assign them to collaborators, add labels, and track their progress.
These are the basic steps involved in working with GitHub. As you gain more experience, you may also explore advanced topics such as pull requests, code reviews, continuous integration, and more.

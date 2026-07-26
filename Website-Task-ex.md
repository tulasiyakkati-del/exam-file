# Creating a Website Using a Markdown Project in VS Code

You can build a simple website by writing your content in Markdown, managing it with Git inside VS Code, and publishing it live using GitHub Pages. This method keeps your content lightweight, version-controlled, and easy to update without needing separate hosting software.

## Prerequisites

- VS Code is installed on your system.
- Git is installed and configured.
- You have an active GitHub account.

## To create your website

1. Open VS Code.
2. Create a new project folder for your website.
3. Open the terminal, and run the following command to initialize Git: git init
4. Create a new file named index.md in your project folder.
5. Add your website content to index.md using Markdown syntax, for example: # Welcome to My Website
6. (Optional) Press Ctrl+Shift+V to preview your formatted content.
7. Connect your project to GitHub by running: git remote add origin https://github.com/username/repo.git
8. Stage, commit, and push your files using git add, git commit, and git push.
9. On GitHub, go to your repository, and select Settings > Pages.
10. Under Source, select the main branch, then select Save.

Your website is now published and available at your GitHub Pages link.
# Creating a Website Using a Markdown Project

You can build a simple website by writing your content in a Markdown file and publishing it using GitHub Pages. This is useful when you want a lightweight, version-controlled way to publish content without setting up separate hosting.

## Prerequisites

- Visual Studio Code is installed on your computer.
- Git is installed and configured.
- You have an active GitHub account.

## To create a website using a Markdown project

1. Open Visual Studio Code.
2. Select **File > Open Folder**, and create or select a folder for your project.
3. In the Explorer panel, create a new file named `index.md`.
4. Open `index.md`, and add your website content using Markdown syntax. For example, type `# Welcome to My Website`. For the full list of Markdown syntax, see the Quick Start Guide.
5. Save the file.
6. Open the terminal, and run the following command to initialize Git:

git init


7. Run the following command to stage your file:

git add .


8. Run the following command to commit your file:

git commit -m "Initial website content"


9. Create a new, empty repository on GitHub:

   a. Go to github.com, and sign in.  
   b. Select the **+** icon in the top-right corner, and select **New repository**.  
   c. Enter a repository name.  
   d. Leave all other options at their default settings.  
   e. Select **Create repository**.  

10. On the repository page, copy the URL shown under **Quick setup**.
11. In the terminal, run the following command to connect your project to the repository, replacing the URL with the one you copied:

 
 git remote add origin https://github.com/username/repo.git
 

12. Run the following command to push your file to GitHub:

 
 git push -u origin main
 

13. On GitHub, go to your repository, and select *Settings > Pages*.
14. Under *Source, select the main branch, and select **Save*.

Your website is now published and available at the GitHub Pages link shown on the Settings page.
# Create a Website Using a Markdown Project

This topic describes how to create a website by using a Markdown project and publish it through GitHub Pages. After completing this task, you can access your website through the GitHub Pages URL.

## Prerequisites

Before you begin, ensure that:

- Visual Studio Code is installed on your computer.
- Git is installed and configured.
- You have an active GitHub account.
- Your computer is connected to the internet.

## To create a website using a Markdown project

1. Open **Visual Studio Code**.

2. Select **File** > **Open Folder**.

3. Create a new folder or open an existing project folder.

4. In the **Explorer** pane, create a new file named `index.md`.

5. Open the `index.md` file.

6. Add the required website content by using Markdown syntax.

   Example:

   ```markdown
   # Welcome to My Website

   This is my first website created with Markdown.
   ```

7. Save the file.

8. Select **Terminal** > **New Terminal** to open the integrated terminal.

9. Run the following command to initialize the Git repository.

   ```bash
   git init
   ```

10. Run the following command stage the project files.

    ```bash
    git add .
    ```

11. Run the following command commit the project.

    ```bash
    git commit -m "Initial website content"
    ```

12. Sign in to **GitHub**.

13. Select **+** > **New repository**.

14. Enter a repository name.

15. Leave the default settings unchanged.

16. Select **Create repository**.

17. Under **Quick setup**, copy the **HTTPS** repository URL.

18. Return to **Visual Studio Code**.

19. Connect the local project to the GitHub repository.

    ```bash
    git remote add origin https://github.com/username/repository.git
    ```

    Replace `username` with your GitHub username and `repository` with your repository name.

20. Push the project to GitHub.

    ```bash
    git push -u origin main
    ```

21. Open the GitHub repository and verify that the `index.md` file is available.

22. Select **Settings**.

23. Select **Pages**.

24. Under **Build and deployment**, select **Deploy from a branch**.

25. From the **Branch** list, select **main**.

26. Select **Save**.

27. Wait a few minutes for GitHub Pages to publish the website.

The website is published successfully. Open the GitHub Pages URL displayed in the **Pages** settings to confirm that the website loads correctly.
# Connecting your Local Repository with Remote

This guide will walk you through the steps to connect your local repository with a remote repository on GitHub.

## Steps:

1. **Create the Repository on GitHub:**
   - Go to the GitHub homepage.
   - Click on the "New" button to create a new repository.
   - Follow the prompts to complete the creation of the repository. You can choose to initialize it with a README file, add a .gitignore file, and/or a license.

2. **Generate your Java-Gradle-Groovy Project in VS Code:**
   - Set up your project in VS Code using Java, Gradle, and Groovy.

3. **Initialize a Git Repository:**
   - Open your terminal and navigate to the root directory of your project.
   - Run the following command to initialize a Git repository:
     ```
     git init
     ```

4. **Configure your Git User Information:**
   - Set your email and name associated with your GitHub account using the following commands:
     ```
     git config --global user.email "your Github registered email"
     git config --global user.name "your Name"
     ```

5. **Make your First Commit:**
   - Add your files to the staging area and commit them using the following commands:
     ```
     git add .
     git commit -m "First commit of the project"
     ```

6. **Copy the URL from GitHub Repository:**
   - Go to your GitHub repository and copy its URL.

7. **Link your Local Repository with the Remote:**
   - Back in your terminal, run the following command to link your local repository with the remote repository on GitHub:
     ```
     git remote add origin "paste URL copied"
     ```

8. **Push your Changes to the Remote Repository:**
   - Finally, push your local changes to the remote repository using the following command:
     ```
     git push origin master
     ```

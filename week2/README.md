# Pushing Java Code to GitHub using VSCode or IntelliJ IDEA

### Week-2 :: 2/1 and 2/2

## Using Visual Studio Code (VSCode):

### Prerequisites:

- Install Git: https://git-scm.com/downloads
- Install VSCode: https://code.visualstudio.com/

### Steps:

1. **Open VSCode:**

   - Launch Visual Studio Code on your computer.

2. **Open Java Project:**

   - Open your Java project in VSCode using the "File" > "Open Folder" menu.

3. **Initialize Git:**

   - Open the VSCode terminal (View > Terminal) and run the following commands:
     ```bash
     git init
     ```

4. **Add Remote Repository:**

   - Add the URL of your GitHub repository as the remote origin:
     ```bash
     git remote add origin https://github.com/yourusername/your-repository.git
     ```

5. **Stage Changes:**

   - Stage the changes you want to commit:
     ```bash
     git add .
     ```

6. **Commit Changes:**

   - Commit the staged changes with a meaningful message:
     ```bash
     git commit -m "Initial commit"
     ```

7. **Push Changes:**
   - Push the committed changes to your GitHub repository:
     ```bash
     git push -u origin master
     ```

## Using IntelliJ IDEA:

### Prerequisites:

- Install Git: https://git-scm.com/downloads
- Install IntelliJ IDEA: https://www.jetbrains.com/idea/

### Steps:

1. **Open IntelliJ IDEA:**

   - Launch IntelliJ IDEA on your computer.

2. **Open Java Project:**

   - Open your Java project in IntelliJ IDEA.

3. **Enable Version Control:**

   - Go to "VCS" > "Enable Version Control Integration" and select "Git."

4. **Add Remote Repository:**

   - Go to "VCS" > "Git" > "Remotes" > "Add" and enter the URL of your GitHub repository.

5. **Commit Changes:**

   - Make changes to your code and commit them:
     - Open the "Version Control" tool window (Alt + 9).
     - Select the files you want to commit, enter a commit message, and click the "Commit" button.

6. **Push Changes:**
   - Push the committed changes to your GitHub repository:
     - After committing changes, click the "Ctrl + Shift + K" shortcut or go to "VCS" > "Git" > "Push" to push changes to the remote repository.

# PLPBasicGitAssignment
Basic Git GitHub Workflow

STEPS:

Task 1: Repository Setup

1. GitHub Repository Creation:
    - Log in to your GitHub account.
            
            https://github.com/NMsby/

    - Create a new repository on GitHub (let's call it "PLPBasicGitAssignment") and initialize the repository with a README.md file.
            
            https://github.com/NMsby/PLPBasicGitAssignment/


Task 2: Local Setup

2.  Local Folder Setup:

    - Create a new folder on your local machine (e.g., "PLPBasicGitAssignment").
        
            $ mkdir PLPBasicGitAssignment
    
    - Open a terminal or command prompt and navigate to the created folder.
            
            $ cd PLPBasicGitAssignment

3. Git Initialization:

    - Initialize a new Git repository in your local folder.
            
            $ git init


4. Connecting to GitHub:

    - Link your local repository to the GitHub repository you created in Task 1.

            $ git remote add origin https://github.com/NMsby/PLPBasicGitAssignment

    - Pull the latest changes from the remote repository in GitHub to the local repository.
        
            $ git pull origin main --allow-unrelated-histories

Task 3: Making Changes

5. Create a File:

    - Inside your local folder, create a new text file (e.g., `hello.txt`).
        
            $ vim hello.txt

    - Add a simple text message (e.g., "Hello, Git!").
            
            Press 'i' to switch to INSERT MODE.
            Type your message "Hello, Git!"
            Press ESC to exit INSERT MODE.
            Type :wq then press ENTER to save the file and exit the editor.


6. Committing Changes:

    - Stage the changes.

            $ git add hello.txt

    - Commit the changes.

            $ git commit -m "Add hello.txt with a greeting"


Task 4: Pushing to GitHub

7. Pushing to GitHub:

    - Push the committed changes to your GitHub repository.

            $ git push -u origin main


Task 5: Verification

8. Verify on GitHub:

    - Visit your GitHub repository in a web browser and confirm that the `hello.txt` file and commit message are visible.

# Module 1 Lab Guide: GitHub, GitHub Classroom, and Codespaces Setup

**BAN 6003: Data Management and Analytics Integration**

This first lab is a setup and confidence check. The goal is to make sure you can create or use a GitHub account, accept a GitHub Classroom assignment, open your assignment repository in GitHub Codespaces, run a Jupyter notebook, save your work, and push your changes back to GitHub.

Take your time with this lab. Most later labs will use the same workflow.

## Lab File

Complete:

`Week1_introduction_to_codespaces.ipynb`

## GitHub Classroom Assignment Link

Canvas will provide the GitHub Classroom invitation link for the Module 1-2 assignment package:

**GitHub Classroom invitation link:** [to be added]

Use this link to create your own personal assignment repository. Do not work in the instructor's template repository.

## What You Need Before Starting

You need:

- a personal GitHub account
- access to the GitHub Classroom assignment link posted by your instructor, usually in Canvas
- a web browser
- enough time for GitHub Codespaces to start the first time

You do not need to install Python, Jupyter, or VS Code on your own computer for this lab. GitHub Codespaces provides the coding environment in the browser.

## Step 1: Create or Sign In to GitHub

Go to:

`https://github.com`

If you already have a GitHub account, sign in. If you do not have an account, create one.

Use an email address you can access during the semester. Choose a username that you are comfortable using for coursework. After creating the account, verify your email address if GitHub asks you to do so.

## Step 2: Open the GitHub Classroom Assignment

Your instructor will post a GitHub Classroom assignment link in Canvas.

Open this Canvas page and click the GitHub Classroom invitation link near the top. You may be asked to sign in to GitHub again.

The first time you use GitHub Classroom for this course, you may be asked to connect your GitHub account to the course roster. Select your own name or identifier carefully. If you are unsure which roster entry is yours, stop and ask your instructor before continuing.

## Step 3: Accept the Assignment

After opening the assignment link, click the button to accept the assignment. If GitHub asks you to authorize GitHub Classroom, approve it.

GitHub Classroom will create a personal copy of the assignment repository for you. This may take a moment. When it is ready, you should see a link to your repository.

Open your repository. The repository belongs to you for this assignment, but your instructor can view your submitted work.

Important: the repository link should include your GitHub username or course identifier. If the page only shows the template repository, go back to the invitation link and make sure you accepted the assignment.

## Step 4: If GitHub Says You Do Not Have Access

Sometimes GitHub Classroom creates the repository but GitHub still needs you to accept a repository or organization invitation before you can open it.

If you see a repository access message or cannot open the assignment repository:

1. Make sure you are signed in to the same GitHub account you used to accept the assignment.
2. Check the notifications inbox in the upper-right corner of GitHub.
3. You can also go directly to `https://github.com/notifications`.
4. Look for an invitation from GitHub Classroom, the course organization, or `github-classroom[bot]`.
5. Accept the pending invitation.
6. Return to the assignment repository link and refresh the page.

You may also receive an email from GitHub with a link to accept the same invitation.

## Step 5: Start GitHub Codespaces

Inside your assignment repository:

1. Click the green **Code** button.
2. Click the **Codespaces** tab.
3. Click **Create codespace on main**.
4. Wait for the Codespace to finish loading.

The first launch can take several minutes because the environment is being built. Wait until setup finishes before running the notebook.

## Step 6: Open the Notebook

In the file explorer, open:

`notebooks/Week1_introduction_to_codespaces.ipynb`

If Jupyter asks you to select a kernel, choose:

`base`

If `base` is not visible immediately, wait a little longer for Codespaces setup to finish, then try again.

## Step 7: Run and Complete the Notebook

Run each cell from top to bottom. The notebook checks that Python works, Pandas imports correctly, and the Jupyter environment is ready.

Complete any short written response requested in the notebook. Save the notebook when you finish.

## Step 8: Commit and Push Your Work

In Codespaces, open the Source Control panel or use the terminal. A typical terminal workflow is:

```bash
git status
git add .
git commit -m "Complete Module 1 readiness check"
git push
```

After pushing, refresh your GitHub repository page in the browser. You should see your latest commit.

## What Good Completion Looks Like

Your notebook should show that Python and Pandas ran successfully. Your repository should contain a saved version of the notebook, and GitHub should show your latest commit.

## If Something Goes Wrong

If the assignment link does not work, make sure you are signed in to the correct GitHub account. If you selected the wrong roster identifier, contact your instructor. If Codespaces is slow, wait a few minutes and refresh. If the notebook kernel is missing, wait for setup to finish and choose `base`.

## Minimum Completion Checklist

Before submitting, make sure:

- You signed in to GitHub.
- You accepted the GitHub Classroom assignment.
- You opened your personal assignment repository.
- You started a Codespace.
- You opened the Week 1 notebook.
- You selected the `base` kernel.
- You ran the Python and Pandas checks.
- You completed the short written response.
- You saved, committed, and pushed your work.

# Module 1 Lab Guide: GitHub, Local Jupyter, and Optional Codespaces Setup

**BAN 6003: Data Management and Analytics Integration**

This first lab is a setup and confidence check. The goal is to make sure you can access the course repository, create your own GitHub copy, run a Jupyter notebook, save your work, and submit your work through Canvas.

Most students should use GitHub Codespaces if they are new to Python setup. More experienced students may use a local computer with conda, VS Code, and Jupyter.

## Lab File

Complete:

`Week1_introduction_to_codespaces.ipynb`

## Course Repository Link

Start from this public template repository:

https://github.com/tianhaiz/ban6003-week-01-02-setup-profiling-template

Do not edit the instructor's repository directly. Create your own copy first.

## What You Need Before Starting

You need:

- a personal GitHub account
- access to Canvas
- either GitHub Codespaces or a local Python/Jupyter setup
- a way to submit your final repository link or files through Canvas

For GitHub beginners, I recommend creating a **public** GitHub repository from the template. A public repo is easiest for the instructor to inspect. If you use a private repository, you must add the instructor as a collaborator. The instructor's GitHub account is `zzz1990771`, and the associated email is `zzz1990771@gmail.com`.

## Step 1: Create or Sign In to GitHub

Go to:

`https://github.com`

If you already have a GitHub account, sign in. If you do not have an account, create one. Use an email address you can access throughout the semester. If possible, add your UTSA email to your GitHub account because it may help you verify student benefits.

## Step 2: Create Your Own Repository from the Template

1. Open the course repository link above.
2. Click **Use this template**.
3. Choose **Create a new repository**.
4. Set the owner to your own GitHub account.
5. Choose a clear repository name, such as `ban6003-week1-2-yourname`.
6. Choose **Public** unless you have a specific reason to keep it private.
7. Click **Create repository**.

After GitHub creates your repository, copy the URL. This is the repository you will work in and submit through Canvas.

## Step 3A: Recommended for Beginners - Use GitHub Codespaces

Codespaces runs VS Code and Jupyter in your browser. You do not need to install Python locally.

1. Open your own GitHub repository.
2. Click the green **Code** button.
3. Click the **Codespaces** tab.
4. Click **Create codespace on main**.
5. Wait for setup to finish.
6. Open the notebook in the `notebooks` folder.
7. If Jupyter asks for a kernel, choose the available Python kernel.

Important Codespaces quota note: personal GitHub Free accounts include 120 core hours per month. On a 2-core Codespace, that is about 60 hours of runtime. If you verify student status through GitHub Education, GitHub currently advertises 180 Codespaces hours per month. Codespaces quota can run out. Closing the browser tab does not necessarily stop the Codespace.

When you are done working:

1. Go to `https://github.com/codespaces`.
2. Find your Codespace.
3. Click the three dots.
4. Choose **Stop codespace**.

Stopping Codespaces saves compute usage. Delete old Codespaces if you no longer need them.

## Step 3B: Option for Local Work - Install Python, Conda, VS Code, and Jupyter

Use this path if you prefer running everything on your own computer.

### Windows Setup

1. Install Miniconda or Anaconda for Windows.
2. Install VS Code.
3. Install Git for Windows.
4. Open **Anaconda Prompt** from the Start menu.
5. Create the course environment:

```bash
conda create -n ban6003 python=3.12
conda activate ban6003
python -m pip install --upgrade pip
```

### Mac Setup

1. Install Miniconda or Anaconda for macOS.
2. Install VS Code.
3. Install Git if it is not already available.
4. Open **Terminal**.
5. Create the course environment:

```bash
conda create -n ban6003 python=3.12
conda activate ban6003
python -m pip install --upgrade pip
```

### Clone and Run Locally

In Terminal or Anaconda Prompt, run:

```bash
git clone YOUR_REPOSITORY_URL
cd YOUR_REPOSITORY_FOLDER
conda activate ban6003
python -m pip install -r requirements.txt
jupyter lab
```

Replace `YOUR_REPOSITORY_URL` with the URL of your own GitHub repository. JupyterLab will open in your browser. Open the notebook from the `notebooks` folder and run it from top to bottom.

## Step 4: Save, Commit, and Push

If you are using GitHub and a repository, save your notebook and push your changes.

In terminal:

```bash
git status
git add .
git commit -m "Complete Module 1 setup check"
git push
```

If you are working from a downloaded ZIP instead of GitHub, save your completed notebook and submit the required file or ZIP through Canvas.

## Step 5: Submit Through Canvas

Submit one of the following through Canvas:

1. Your GitHub repository link, if the instructor can access it.
2. A ZIP file containing your completed notebook and required files.

If your repository is private, invite `zzz1990771` as a collaborator before submitting the link.

## Minimum Completion Checklist

Before submitting, make sure:

- You created your own copy of the course repository.
- Your repository is public, or you invited the instructor if it is private.
- You opened the Week 1 notebook.
- You ran the Python and Pandas checks.
- You completed the short written response.
- You saved your work.
- You submitted your GitHub link or completed files through Canvas.

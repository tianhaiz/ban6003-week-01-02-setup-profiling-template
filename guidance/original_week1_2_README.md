# BAN 6003 Week 1–2 Starter: Codespaces, Python, Pandas, and First Data Profile

**Data Management and Analytics Integration**  
**Weeks 1–2: GitHub Codespaces + Python/Pandas Readiness**

Welcome to the first GitHub Classroom assignment. This assignment helps you confirm that your coding environment works and then practice your first data profiling workflow with Python and Pandas.

You do **not** need to be an experienced programmer. Focus on opening notebooks, running code, reading output, and writing short observations about the data.

---

## What You Will Complete

| Week | Notebook | Purpose |
|---|---|---|
| Week 1 | `Week1_introduction_to_codespaces.ipynb` | Confirm Codespaces, Python, and Pandas work; add your name and short introduction. |
| Week 2 | `Week2_lab1_python_pandas_guided_lab.ipynb` | Guided lab on Python basics, Pandas, CSV import, and data profiling. |
| Week 2 | `Week2_assignment.ipynb` | Independent checkpoint using the functions from the guided lab. |

---

## Dataset

The dataset is located in the `data/` folder:

```text
data/employee_data.csv
```

In the notebooks, the path may appear as:

```python
"../data/employee_data.csv"
```

Do not move or rename the dataset.

---

## Week 1: Codespaces Readiness Check

Open:

```text
Week1_introduction_to_codespaces.ipynb
```

Complete the notebook by doing the following:

1. Run the Python/Pandas test cell.
2. Confirm that Pandas imports successfully.
3. Add your name, section, and short self-introduction.
4. Save the notebook.
5. Commit and push your work.

Week 1 is only a readiness check. The goal is to make sure your environment works before the Week 2 data lab.

---

## Week 2: Guided Lab and Checkpoint

First complete:

```text
Week2_lab1_python_pandas_guided_lab.ipynb
```

Then complete:

```text
Week2_assignment.ipynb
```

Week 2 focuses on **data profiling**, not data cleaning. Your job is to inspect the dataset and describe its condition.

You will practice:

- `pd.read_csv()`
- `head()` and `tail()`
- `shape`, `columns`, `info()`, and `dtypes`
- `isna().sum()`
- `describe()`
- `value_counts()`
- `duplicated().sum()`
- Short written observations about data quality

---

## How to Open Codespaces

1. Open the GitHub Classroom assignment link from Canvas/LMS.
2. Accept the assignment using your own GitHub account.
3. Open your assignment repository.
4. Click the green **Code** button.
5. Select the **Codespaces** tab.
6. Click **Create codespace on main**.
7. Wait for the environment to finish loading.

If Jupyter asks for a kernel, select:

```text
base
```

---

## How to Submit

After finishing your work, open the Terminal in Codespaces.

If you do not see the Terminal, use:

```text
View → Terminal
```

Then run:

```bash
git add .
git commit -m "Completed Week 1-2 setup and data profiling assignment"
git push
```

You may commit and push multiple times before the deadline. I will grade the version available in your GitHub repository at the deadline.

---

## Completion Checklist

Before the final deadline, make sure:

- [ ] `Week1_introduction_to_codespaces.ipynb` runs successfully.
- [ ] You added your name and short introduction.
- [ ] `Week2_lab1_python_pandas_guided_lab.ipynb` has been run carefully.
- [ ] `Week2_assignment.ipynb` includes your completed code.
- [ ] You loaded the dataset with Pandas.
- [ ] You checked structure, data types, missing values, summaries, categories, and duplicate IDs.
- [ ] You wrote short data quality observations.
- [ ] All notebooks are saved.
- [ ] Your work is committed and pushed to GitHub.

---

## Codespaces Quota Reminder

When you are done working:

1. Save your notebooks.
2. Commit and push your work.
3. Stop or delete your Codespace.

Deleting a Codespace does **not** delete your GitHub repository or pushed code. However, unsaved or uncommitted work inside a Codespace may be lost.

To stop or delete a Codespace, go to your GitHub Codespaces page, click the three dots next to the Codespace, and choose **Stop** or **Delete**.

---

## Common Problems

### I cannot find the Terminal.

Use **View → Terminal**.

### I cannot select the kernel.

Wait for Codespaces to finish loading, then select `base`.

### I get a file not found error.

Check that the dataset is still in the `data/` folder and that your file path matches the notebook instructions.

### Git says there is nothing to commit.

Save your notebook first, then run:

```bash
git status
```

### I get an error when pushing.

Read the error message, run `git status`, and take a screenshot if you need help.

---

## How to Ask for Help

When asking for help, include:

- The notebook name.
- The task you are working on.
- A screenshot of the issue.
- The exact error message.
- What you already tried.

Example:

> I am working on `Week2_assignment.ipynb`. I tried to load the CSV file, but I got a file not found error. Here is my code and a screenshot.

---

## Reminder

This assignment is beginner-friendly. You are not expected to clean the data yet. This week, your job is to inspect the dataset and describe what you notice.

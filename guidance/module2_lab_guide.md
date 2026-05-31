# Module 2 Lab Guide: Python, Pandas, and First Data Profile

**BAN 6003: Data Management and Analytics Integration**

This module begins the main data workflow of the course. You will use Python and Pandas to inspect a dataset before making any cleaning or modeling decisions.

The central question is:

> What is the condition of this data?

This lab is about profiling, not fixing. Your job is to describe what the data contains, what looks useful, and what may need attention later.

## Lab Files

Complete both notebooks:

- `Week2_lab1_python_pandas_guided_lab.ipynb`
- `Week2_assignment.ipynb`

The guided lab teaches the core commands. The assignment notebook asks you to apply those commands more independently.

## Starting from GitHub Classroom

If Module 2 is part of the same Module 1-2 assignment repository, open the repository you already created in Module 1. If your instructor provides a separate GitHub Classroom link, accept that assignment link first, then open the new repository.

**GitHub Classroom invitation link:** [to be added]

If GitHub says you do not have access to the repository, check that you are signed in to the same GitHub account you used for Module 1. Then check the GitHub notifications inbox in the upper-right corner, or go to `https://github.com/notifications`, and accept any pending repository or organization invitation from GitHub Classroom.

To reopen Codespaces:

1. Go to your assignment repository on GitHub.
2. Click **Code**.
3. Click **Codespaces**.
4. Open the existing Codespace if one is listed, or create a new Codespace on `main`.
5. Wait for the environment to finish loading.

If Jupyter asks for a kernel, choose `base`.

## What You Will Practice

You will practice basic Python objects, code and markdown cells, importing Pandas, loading CSV data with `pd.read_csv()`, inspecting rows and columns, checking data types, counting missing values, creating numerical summaries, reviewing categorical values, checking possible duplicates, and writing short data quality observations.

## Recommended Workflow

1. Open the assignment repository in GitHub Codespaces.
2. Open `notebooks/Week2_lab1_python_pandas_guided_lab.ipynb`.
3. Run the guided lab from top to bottom.
4. Read the markdown explanations, not just the code.
5. Open `notebooks/Week2_assignment.ipynb`.
6. Use the guided lab as a reference while completing the assignment.
7. Write observations in plain business language.
8. Save both notebooks.
9. Commit and push your work.

## How to Think About Profiling

Profiling is the first pass through a dataset. You are looking for structure and warning signs: row counts, column meanings, missing values, suspicious data types, repeated records, unusual categories, and numerical values that may be too high, too low, or impossible.

Do not clean the dataset yet unless the notebook explicitly asks you to. A strong profile clearly describes issues so that later cleaning decisions are easier to justify.

## Minimum Completion Checklist

Before submitting, make sure:

- You opened the correct assignment repository.
- You ran the guided lab.
- You completed the assignment notebook.
- You loaded the dataset successfully.
- You checked shape, columns, and data types.
- You checked missing values.
- You created numerical and categorical summaries.
- You checked possible duplicates.
- You wrote short observations about data quality.
- You saved, committed, and pushed your work.

Suggested commit message:

```bash
git commit -m "Complete Module 2 data profiling lab"
```

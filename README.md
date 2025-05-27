# datafun-04-eda Summer 1 - module 4

## CheatSheet: Managing Virtual Environment

For **Windows PowerShell** (adjust commands if using Mac/Linux):

1. **Create a virtual environment**:
   ```powershell
   py -m venv .venv
   ```

2. Activate the virtual environment:

   ```powershell
   .\.venv\Scripts\activate
   ```

3. Upgrade pip, setuptools, and wheel:

   ```powershell
   py -m pip install --upgrade pip setuptools wheel
   ```

4. Install required packages:

   ```powershell
   py -m pip install --upgrade -r requirements.txt
   ```

## CheatSheet: Running Python Scripts

Remember to activate your `.venv` (and install packages if they haven't been installed yet) before running files. Verify that all external packages imported into a file are included in `requirements.txt` (and have NOT been commented out).

Run Python scripts using the following commands:

   ```powershell
   py demo_script.py
   py do_stats.py
   py draw_chart.py
   py greet_user.py
   ```

## Every Work Session

Many projects span several days. When starting work again, remember to:

   <https://github.com/denisecase/pro-analytics-01/tree/main/03-repeatable-workflow>

   01-git-pull-before-changes.md
   02-activate-virtual-environment.md
   03-install-dependencies.md
   04a-activate-and-run-python-script.md
   05-modify-and-test.md
   06-git-add-commit-push.md

## CheatSheet: Git Add-Commit-Push

Use the following commands to add, commit, and push changes to Git:

   ```powershell
   git clone https://github.com/youraccount/yourrepo
   git add .
   git commit -m "custom message"
   git push -u origin main
   git pull origin main
   git push
   ```

## P4 Exploratory Data Analysis

Step 1. Initial Title, Header, and Imports (pandas, seaborn, matplotlib and Axes from matplotlib.axes)
Step 2. Load Data (Iris dataset for classification and basic data task)
Step 3. Initial Data Inspection
Step 4. Initial Descriptive Statistics
Step 5. Initial Data Distribution for Numerical Columns
Step 5. Initial Data Distribution for Categorical Columns
Step 6. Initial Data Transformation and Feature Engineering
Step 7. Initial Visualizations
Step 8. Initial Insights
Step 9. Annotate Your Notebook for Storytelling and Presentation

Checklist
    Notebook has exactly one Markdown title (with a single hash).
    Notebook has useful Markdown header cell with author and purpose, and optionally, the date.
    Notebook uses numbered second level Markdown headings for organization.
    Notebook has numbered sections with useful content for:
        1. Imports
        2. Load Data
        3. Initial Data Inspection
        4. Initial Descriptive Statistics
        5. Initial Data Distribution for Numerical Columns
        6. Initial Data Transformation and Feature Engineering
        7. Initial Visualizations
        8. Initial Insights
    Notebook includes commentary as we go that tells a unique data story.
    Notebook includes unique insights into the dataset.
    Code and visuals are working, notebook is fully executed and on display in GitHub.


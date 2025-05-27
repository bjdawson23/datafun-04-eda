# datafun-04-eda Summer 1 - Module 4

## 1. Virtual Environment Management (Windows PowerShell)

1. **Create a virtual environment**
   ```powershell
   py -m venv .venv
   ```

2. **Activate the virtual environment**
   ```powershell
   .\.venv\Scripts\activate
   ```

3. **Upgrade pip, setuptools, and wheel**
   ```powershell
   py -m pip install --upgrade pip setuptools wheel
   ```

4. **Install required packages**
   ```powershell
   py -m pip install --upgrade -r requirements.txt
   ```

---

## 2. Running Python Scripts

- Activate your `.venv` and ensure all required packages are installed.
- Verify all external packages in your scripts are listed in `requirements.txt`.

**Run Python scripts:**
```powershell
py demo_script.py
py do_stats.py
py draw_chart.py
py greet_user.py
```

---

## 3. Repeatable Workflow Checklist

When resuming work on your project, follow these steps:

1. [Pull latest changes](https://github.com/denisecase/pro-analytics-01/tree/main/03-repeatable-workflow)
2. Activate virtual environment
3. Install dependencies
4. Run Python scripts
5. Modify and test code
6. Add, commit, and push changes to Git

---

## 4. Git Add-Commit-Push CheatSheet

```powershell
git clone https://github.com/youraccount/yourrepo
git add .
git commit -m "custom message"
git push -u origin main
git pull origin main
git push
```

---

## 5. P4 Exploratory Data Analysis (EDA) Notebook Structure

### Steps

1. **Initial Title, Header, and Imports**  
   *(pandas, seaborn, matplotlib, and Axes from matplotlib.axes)*
2. **Load Data**  
   *(Iris dataset for classification and basic data task)*
3. **Initial Data Inspection**
4. **Initial Descriptive Statistics**
5. **Initial Data Distribution for Numerical Columns**
6. **Initial Data Distribution for Categorical Columns**
7. **Initial Data Transformation and Feature Engineering**
8. **Initial Visualizations**
9. **Initial Insights**
10. **Annotate Your Notebook for Storytelling and Presentation**

---

### Notebook Checklist

- [ ] Exactly one Markdown title (with a single hash)
- [ ] Useful Markdown header cell with author, purpose, and optionally, the date
- [ ] Numbered second-level Markdown headings for organization
- [ ] Numbered sections with useful content for:
    1. Imports
    2. Load Data
    3. Initial Data Inspection
    4. Initial Descriptive Statistics
    5. Initial Data Distribution for Numerical Columns
    6. Initial Data Transformation and Feature Engineering
    7. Initial Visualizations
    8. Initial Insights
- [ ] Commentary throughout that tells a unique data story
- [ ] Unique insights into the dataset
- [ ] Code and visuals are working, notebook is fully executed and viewable on GitHub

---


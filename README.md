# 1.3M LinkedIn Jobs & Skills Analysis

[![Live Report](https://img.shields.io/badge/📊_Live_Report-View_Now-38bdf8?style=for-the-badge)](https://ted-m-tech.github.io/data-science-1.3M-linkedin-jobs-skills/)

> **[🔗 View the Interactive Report](https://ted-m-tech.github.io/data-science-1.3M-linkedin-jobs-skills/)** — Analysis of 1.3M+ LinkedIn IT job postings: trends, skills, and geographic insights.

![Report Thumbnail](docs/report/img/thumbnail.png)

---

## Data

Original Data is from Kaggle: [1.3M LinkedIn Jobs and Skills 2024](https://www.kaggle.com/datasets/asaniczka/1-3m-linkedin-jobs-and-skills-2024/data)

## Development Conventions

This project follows a trunk-based development branching model. The main branch is the trunk, and all development is done in short-lived feature branches.

### Branch Naming Convention

When creating a new branch, please follow this naming convention:

```
\`[developername]/issue[#]\`
```

For example: `john/issue123`

This makes it easy to identify who is working on the branch and which issue it relates to.

### Branching Strategy

```
main (trunk)
|
+-- [developername]/issue[1] (feature branch)
| |
| (commit)
| |
| (commit)
| /
+-- (merge)
|
+-- [developername]/issue[2] (feature branch)
| |
| (commit)
| /
+-- (merge)
|
(HEAD)
```

## Instructions

This is a Python-based data analysis project using Jupyter notebooks. To run this project, you will need to have Python, Jupyter Notebook or JupyterLab, and the necessary libraries installed.

### 1. Set up the Environment

It is recommended to use a virtual environment to manage project dependencies.

```bash
python -m venv venv
source venv/bin/activate
```

### 2. Install Dependencies

Install the required packages using `pip` and the `requirements.txt` file:

```bash
pip install -r requirements.txt
```

### 3. Obtain the Data

This project requires three data files to be placed in the `resources/` directory:

- `job_skills.csv`
- `job_summary.csv`
- `linkedin_job_postings.csv`

These files are not included in the repository. You can download the original data from Kaggle: [1.3M LinkedIn Jobs and Skills 2024](https://www.kaggle.com/datasets/asaniczka/1-3m-linkedin-jobs-and-skills-2024/data).

### 4. Run the Analysis

Once the environment is set up and the data is in place, you can run the analysis by starting Jupyter and opening the `eda.ipynb` notebook.

```bash
jupyter notebook codes/eda.ipynb
```

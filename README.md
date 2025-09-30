# cmpe255-heart_disease_analysis

# UCI Heart Disease — Exploratory Data Analysis (CMPE 255)

**Goal:** Perform knowledge discovery and visualization on the UCI Heart Disease dataset to identify risk factors and patterns associated with heart disease.  

---

## Dataset

- **Source:** UCI Machine Learning Repository — Heart Disease Data Set  
  https://archive.ics.uci.edu/ml/datasets/Heart+Disease  

## Project Folder Structure
```
cmpe255-heart_disease_analysis/
│── data/
│   ├── raw/               # Original datasets (unchanged)
│   ├── cleaned/         # Cleaned and transformed datasets
│
│── notebooks/             # Jupyter notebooks for analysis & experiments
│   ├── 00_data_cleaning.ipynb
│   ├── 01_xxxx.ipynb
│   └── 02_xxxx.ipynb
│
│── docs/                  # documents for the project 
│
│── reports/               # Generated reports, figures, results
│
│── .gitignore             # Git ignore rules (venv, __pycache__, etc.)
│── requirements.txt       # Python dependencies
│── README.md              # Project documentation
```

## Environmental Setup

Follow these steps if you are running the project locally on your machine (not Google Colab).

### 1. Clone the Repository

```bash
git clone https://github.com/Rodarkhen/cmpe255-heart_disease_analysis.git
cd cmpe255-heart_disease_analysis
```

### 2. Create a Virtual Environment
- This is to isolate dependencies for this project.
```
# Mac/Linux
python3 -m venv venv

# Windows
python -m venv venv
```

### 3. Activate the Virtual Environment
```
# Mac/Linux
source venv/bin/activate

# Windows (Command Prompt)
venv\Scripts\activate

# Windows (PowerShell)
venv\Scripts\Activate.ps1
```
Once activated, you should see (venv) at the start of your terminal prompt in VS Code.

### 4. Install Dependencies
Make sure pip is updated, then install from requirements.txt:
```bash
pip install --upgrade pip
pip install -r requirements.txt
```

### 5.Open in VS Code
- Open the project folder in VS Code (File → Open Folder).
- Select the Python interpreter from your virtual environment:

    Ctrl+Shift+P → Python: Select Interpreter → choose .venv or venv.
- Run notebooks/scripts in VS Code with the selected environment.

### 6. Running the Project
```bash
# Start Jupyter Notebook
jupyter notebook

# OR start JupyterLab
jupyter lab
```

### 7. Deactivate the Environment
When you're done working:
```bash
deactivate
```
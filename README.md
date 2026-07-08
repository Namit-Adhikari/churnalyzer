# Churnalyzer

A machine learning and data analysis tool designed to analyze customer behavior data and predict subscriber churn. Using customer metrics provided in `data.csv`, the project builds predictive models and outputs visualization dashboards to help identify key indicators of customer attrition.

The entire analytical workflow—ranging from data preprocessing and exploratory data analysis (EDA) to model training and evaluation—is implemented and executed in the interactive Jupyter Notebook `main.ipynb`.

## Prerequisites

- **Python**: `>= 3.14`

---

## Setup Instructions

### 1. Clone the Repository

Clone the repository and navigate into the project directory:

```bash
git clone <repository-url>
cd churnalyzer
```

### 2. Initialize Virtual Environment & Install Dependencies

Set up the virtual environment and install all packages using either **uv** or standard **pip**.

#### Option A: Using `uv` (Recommended)

Sync dependencies and automatically initialize the environment:

```bash
uv sync
```

#### Option B: Using standard `pip`

1. Create a virtual environment:

   ```bash
   python -m venv .venv
   ```

2. Activate the environment:
   - **Windows (PowerShell):**

     ```powershell
     .venv\Scripts\Activate.ps1
     ```

   - **macOS / Linux / Windows (Git Bash):**

     ```bash
     source .venv/bin/activate
     ```

3. Install dependencies:

   ```bash
   pip install --upgrade pip
   pip install -e .
   ```

### 3. Run the Project

You can run the interactive Jupyter Notebook `main.ipynb`:

- **Using `uv`:**

  ```bash
  uv run jupyter lab
  ```

- **Using standard `pip` (with your virtual environment activated):**
  Ensure Jupyter is installed and launch the lab:

  ```bash
  pip install jupyter
  jupyter lab
  ```

- **Using an IDE (e.g., VS Code):**
  Open `main.ipynb`, select the virtual environment (`.venv`) as the Python kernel, and run all cells.

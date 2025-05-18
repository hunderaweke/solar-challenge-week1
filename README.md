# Environment Setup Guide

Follow these steps to set up your Python environment for the Benin EDA Project.

## 1. Clone the Repository

```bash
git clone https://github.com/your-username/kifiya-week-0.git
cd kifiya-week-0
```

## 2. Create a Virtual Environment (Recommended)

**Using `venv`:**

```bash
python -m venv venv
```

Activate the environment:

- On Windows:
  ```bash
  venv\Scripts\activate
  ```
- On macOS/Linux:
  ```bash
  source venv/bin/activate
  ```

## 3. Install Dependencies

Install all required Python packages using pip:

```bash
pip install -r requirements.txt
```

Or, if you don’t have a `requirements.txt`, install the main dependencies:

```bash
pip install pandas numpy matplotlib seaborn scipy
```

## 4. (Optional) Using Conda

If you prefer Conda, create an environment and install dependencies:

```bash
conda create -n benin-eda python=3.11
conda activate benin-eda
pip install -r requirements.txt
```

## 5. Verify Installation

Check Python and package versions:

```bash
python --version
pip list
```

## 6. Run the Notebook

Open Jupyter Notebook or VS Code and run `notebooks/benin_eda.ipynb` step by step.

---

**Tip:**  
If you add or update packages, run `pip freeze > requirements.txt` to update your dependency list.
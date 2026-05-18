# DSA210-project
Course project for DSA 210 - Introduction to Data Science

## Reproducing the Analysis

To reproduce the analysis performed in this project, please follow the steps below:

### 1. Set up the environment
It is recommended to use a Python virtual environment. 

Create and activate a virtual environment (optional but recommended):
```bash
# For macOS/Linux
python -m venv .venv
source .venv/bin/activate

# For Windows
python -m venv .venv
.venv\Scripts\activate
```

### 2. Install Dependencies
Install all required Python packages using the provided `requirements.txt` file:
```bash
pip install -r requirements.txt
```

### 3. Run the Notebooks
Start the Jupyter environment to view and execute the notebooks:
```bash
jupyter notebook
```

The analysis is divided into three parts, located in the `notebooks/` directory. For a complete reproduction, please run the notebooks sequentially in the following order:

1. **`01_data_collection.ipynb`**: This notebook fetches and preprocesses the raw data necessary for the analysis.
2. **`02_eda_and_testing.ipynb`**: This notebook contains Exploratory Data Analysis (EDA) and various statistical tests on the collected data.
3. **`03_ml_methods.ipynb`**: This notebook applies machine learning methods to the preprocessed data to evaluate predictive models.

## AI Usage Note

An LLM was utilized during the preparation of the final report exclusively for language improvement, proofreading, and structuring the text to ensure clarity and readability.

**Example Prompts Used:**
- *"Please review this paragraph for clarity and suggest any grammatical improvements while maintaining the technical accuracy."*
- *"Rephrase this section to make it flow more logically and sound more professional."*
- *"Check this explanation of the machine learning results for any awkward phrasing and correct it."*

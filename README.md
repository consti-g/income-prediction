# Income Prediction Project

This project is part of Dataiku's Technical Assessment. This project aims to explore and predict income trends in the United States by examining demographic characteristics and identifying influential factors affecting income levels. Utilizing a dataset provided by the US Census Bureau, this study seeks to predict whether an individual earns more or less than $50,000 a year.


### Goals:
- **Examine** demographic characteristics across the US.
- **Identify** key factors influencing income prediction.
- **Predict** income levels to aid in funding allocation.

### Dataset:
- Source: US Census Bureau
- Size: ~300,000 individuals

### Project Structure:
1. **Data Analysis:** Initial insights, demographic influence analysis.
2. **Data Preparation:** Data cleaning, feature engineering, and dataset creation.
3. **Data Modeling:** Implementation and comparison of models including Random Forest, Logistic Regression, XG-Boost, and Neural Network.
4. **Model Assessment:** Model comparison and selection.
5. **Results:** Key findings and future work suggestions.

### Folder Structure:
- `/figures`: Contains all figures and images used in the slides.
- `README.md`: This README file.
- `notebook.ipynb`: Jupyter notebook with the complete analysis and modeling.
- `requirements.txt`: Lists all the dependencies required to run the project.
- `slides.pdf`: Presentation slides in PDF format detailing the project's approach and findings.

### Data Setup:
Before running the analysis, you'll need to set up the dataset used in this project. The dataset consists of information provided by the US Census Bureau and is split into training and testing sets, along with metadata that describes the dataset's features.

1. **Create a folder named `us_census_full` in the root directory of this project.** This folder will store all the dataset files required for the analysis.

2. **Download the following files into the `us_census_full` folder:**
   - `census_income_test.csv`: The testing set.
   - `census_income_learn.csv`: The training set.
   - `census_income_metadata.txt`: Metadata describing the dataset features and values.

```bash
project-directory/
│
├── figures/
│
├── notebook.ipynb
│
├── requirements.txt
│
├── slides.pdf
│
├── us_census_full/
│ ├── census_income_test.csv
│ ├── census_income_learn.csv
│ └── census_income_metadata.txt
│
└── README.md
```

### Environment Setup and Project Execution

To ensure a smooth execution of the analysis, follow these steps to set up your environment and run the project.

#### 1. Install Virtual Environment (If Not Already Installed)

If you haven't installed `virtualenv` globally:

```bash
pip install virtualenv
```

#### 2. Create and Activate Virtual Environment

- Create Virtual Environment:

Navigate to your project directory and create a virtual environment:

```bash
virtualenv venv
```

- Activate Virtual Environment:

On windows:

```bash
venv\Scripts\activate
```

On macOS and Linux:

```bash
source venv/bin/activate
```

#### 3. Install Project Dependencies

With the virtual environment activated:

```bash
pip install -r requirements.txt
```

#### 4. Run Jupyter Notebook

Still within the virtual environment, start the Jupyter Notebook:

```bash
jupyter notebook
```
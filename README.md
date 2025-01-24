# Project DA Assignment

## Overview
This project involves three main tasks designed to analyze and derive insights from customer and transaction data, build a recommendation model, and perform customer segmentation using clustering techniques. Below is a detailed description of the tasks and deliverables.

---

## Directory Structure
```
C:\Users\Manas Kumar Sinha\Downloads\Project_DA
|
|-- Intermmediate CSV
|   |-- Asia_transactions.csv
|   |-- association_rules.csv
|   |-- Customer_Segmentation_Final.csv
|   |-- Customer_Segmentation_Results.csv
|   |-- Europe_transactions.csv
|   |-- final.csv
|   |-- frequent_itemsets.csv
|   |-- Lookalike.csv
|   |-- North_America_transactions.csv
|   |-- South_America_transactions.csv
|
|-- Clustering.ipynb
|-- Clustering_documentation.md
|-- Customers.csv
|-- Data Science Intern _ Assignment.pdf
|-- EDA.ipynb
|-- Insights.pdf
|-- Insights_raw.txt
|-- Lookalike_Model.ipynb
|-- Products.csv
|-- Transactions.csv
```

---

## Task Details

### Task 1: Exploratory Data Analysis (EDA) and Business Insights
**Description:**
- Perform Exploratory Data Analysis on the dataset.
- Derive at least 5 business insights.
- Write insights concisely (maximum 100 words per insight).

**Deliverables:**
- `EDA.ipynb`: Jupyter Notebook/Python script containing EDA code.
- `Insights.pdf`: PDF report summarizing business insights (maximum 500 words).
- `Insights_raw.txt`: Draft or raw text for insights.

---

### Task 2: Lookalike Model
**Description:**
- Build a Lookalike Model to recommend 3 similar customers for a given user based on profile and transaction history.
- Incorporate both customer and product information.
- Assign similarity scores to recommendations.

**Deliverables:**
- `Lookalike_Model.ipynb`: Jupyter Notebook/Python script explaining the model development.
- `Lookalike.csv`: A mapping file containing the top 3 lookalikes and their similarity scores for customers C0001 to C0020.

**Evaluation Criteria:**
- Model accuracy and logic.
- Quality of recommendations and similarity scores.

---

### Task 3: Customer Segmentation / Clustering
**Description:**
- Perform customer segmentation using clustering techniques.
- Use both profile and transaction information.
- Choose any clustering algorithm and number of clusters (between 2 and 10).
- Evaluate clustering using the DB Index and other metrics.

**Deliverables:**
- `Clustering.ipynb`: Jupyter Notebook/Python script containing clustering code.
- `Customer_Segmentation_Final.csv`: Final segmentation results.
- `Customer_Segmentation_Results.csv`: Intermediate segmentation results.
- `Clustering_documentation.md`: Documentation detailing clustering results, DB Index value, and metrics.

**Evaluation Criteria:**
- Clustering logic and metrics.
- Visualization of clusters.

---

## File Descriptions
- **Customers.csv:** Contains customer profile information.
- **Products.csv:** Contains product details.
- **Transactions.csv:** Records customer transactions.
- **Intermmediate CSV:** Contains intermediate results and processed data for tasks.
- **Clustering.ipynb:** Notebook with clustering implementation and visualizations.
- **EDA.ipynb:** Notebook performing Exploratory Data Analysis.
- **Lookalike_Model.ipynb:** Notebook implementing the Lookalike Model.
- **Insights.pdf:** Final insights derived from EDA.
- **Insights_raw.txt:** Draft for insights before finalization.

---

## Usage Instructions
1. Open the respective Jupyter Notebooks (`EDA.ipynb`, `Lookalike_Model.ipynb`, `Clustering.ipynb`) for code execution and analysis.
2. Ensure required libraries (e.g., pandas, scikit-learn, matplotlib) are installed in your environment.
3. Review the PDF reports (`Insights.pdf`, `Clustering_documentation.md`) for insights and clustering results.
4. Intermediate CSV files are located in the `Intermmediate CSV` directory for reference and debugging.

---

## Contact
For questions or assistance, please reach out to Manas Kumar Sinha at [your email].


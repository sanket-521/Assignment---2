# Assignment---2
Assignment-2 for Star Health Internship

# Neo Vehicle Insurance Claims Analysis – April 2025

Welcome to the repository for **XYZ TECH's Neo Vehicle Insurance Claims Analysis**. This project uses raw insurance claim data from April 2025 to drive actionable business insights — including cleaning the data, classifying rejection reasons, and recommending a city for operational shutdown.

---

##  Project Objectives

1. **Preprocess Claims Data**  
   - Clean and normalize raw CSV data using **core Python only** (no pandas/numpy).  
   - Handle missing values, data inconsistencies, and type corrections.

2. **Recommend City for Shutdown**  
   - Analyze city-wise performance (claims count, premium collected, rejection rate).  
   - Identify the **least valuable city** for XYZ TECH to consider shutting down operations.

3. **Classify Rejection Reasons**  
   - Use a rule-based classifier to categorize `REJECTION_REMARKS` into standardized categories.  
   - Add a new column `REJECTION_CLASS` to the dataset.

4. **Export Cleaned Data**  
   - Save final processed data to a new CSV file for use in BI tools or reporting.

---

## Key Features

-  **City-wise Operational Insights**
-  **No dependency on external libraries**
-  **Cleaned output saved as CSV**
-  **Standardized rejection reason tagging**

---

##  Tech Stack

| Component   | Details                        |
|-------------|--------------------------------|
| Language    | Python 3.x                     |
| Libraries   | None (standard library only)   |
| Input       | `Insurance_auto_data.csv`      |
| Output      | `cleaned_insurance_data_with_classes.csv` |

---

## How to Run

This project is implemented in a **Jupyter Notebook**. Follow the steps below:

1. Open the notebook file:  
   `Insurance_Claims_Analysis.ipynb` (or your named notebook file)

2. Ensure the input CSV file `Insurance_auto_data.csv` is placed in the **same directory** as the notebook.

3. Run the notebook **cell-by-cell**, which includes:

   -  **Step 1: Preprocess Data**
   -  **Step 2: Analyze City-wise Performance**
   -  **Step 3: Classify Rejection Remarks**
   -  **Step 4: Export Cleaned Data to CSV**

4. After successful execution, the final cleaned dataset will be saved as:  
   **`cleaned_insurance_data_with_classes.csv`**

5. Use this file for any further reporting, BI tools, or analytics.

---

 You can run the notebook in:
- **Jupyter Notebook**
- **JupyterLab**
- **VSCode with Jupyter extension**
- **Google Colab** (make sure to upload the CSV first)

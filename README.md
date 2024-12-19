# Employees Burnout Analysis

## 📊 Overview
This repository contains an analytical project focused on understanding employee burnout trends using a dataset that includes key metrics like resource allocation, mental fatigue scores, and burnout rates. The goal is to provide actionable insights to improve workplace well-being and optimize employee performance.

## 📁 Dataset Description
The dataset consists of 9 columns:

| Column Name              | Description                                                                                 | Example                          |
|--------------------------|---------------------------------------------------------------------------------------------|----------------------------------|
| **Employee ID**          | Unique ID allocated for each employee.                                                     | `fife390032003000`              |
| **Date of Joining**      | Date-time when the employee joined the organization.                                        | `2008-12-30`                    |
| **Gender**               | Gender of the employee.                                                                    | `Male/Female`                   |
| **Company Type**         | Type of company where the employee works.                                                  | `Service/Product`               |
| **WFH Setup Available**  | Indicates if work-from-home facility is available.                                          | `Yes/No`                        |
| **Designation**          | Designation level in the organization, ranging from **0.0** to **5.0**.                    | Higher values indicate seniority. |
| **Resource Allocation**  | Number of working hours allocated, ranging from **1.0** to **10.0**.                       | Higher values indicate more resources. |
| **Mental Fatigue Score** | Mental fatigue level experienced by the employee, ranging from **0.0** to **10.0**.         | `0.0` (no fatigue) to `10.0` (extreme fatigue). |
| **Burnout Rate**         | Predicted burnout rate, ranging from **0.0** to **1.0**.                                    | Higher values indicate a higher likelihood of burnout. |

## 🛠️ Project Features
- **Data Cleaning & Exploration**: Prepares and explores the dataset to uncover insights.
- **Visualization**: Generates meaningful charts to depict trends and correlations.
- **Predictive Modeling**: Implements regression models to predict burnout rates based on employee metrics.
- **Evaluation Metrics**: Includes RMSE, MAE, and R² scores to assess model performance.

## 🖥️ Technology Stack
- **Programming Language**: Python
- **Libraries Used**:
  - `pandas` for data manipulation
  - `matplotlib` and `seaborn` for visualization
  - `scikit-learn` for model training and evaluation

## 🚀 Getting Started
1. Clone the repository:
   ```bash
   git clone https://github.com/Saket22-CS/Employees-Burnout-Analysis.git
   ```
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Run the Jupyter Notebook to explore the analysis:
   ```bash
   jupyter notebook Employees_Burnout_Analysis.ipynb
   ```

## 📈 Key Insights
- **Mental Fatigue Score** and **Resource Allocation** are significant predictors of employee burnout.
- Employees with higher designations show a varying but significant correlation with burnout rates.

## 🤝 Contributions
Contributions are welcome! Feel free to submit issues or pull requests for enhancements.

## 📜 License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## 📧 Contact
For queries, please reach out to [Saket Chaudhary](mailto:saket@example.com).

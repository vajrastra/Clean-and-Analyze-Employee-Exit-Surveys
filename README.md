# Employee Exit Surveys Analysis

## Overview
In this project, we analyze employee exit surveys from the Department of Education, Training and Employment (DETE) and the Technical and Further Education (TAFE) body of the Queensland government in Australia. The goal is to understand the reasons for employee resignations and identify patterns based on the length of service.

## Data Sources
- [DETE Exit Survey](https://data.gov.au/dataset/ds-qld-fe96ff30-d157-4a81-851d-215f2a0fe26d/details?q=exit%20survey)
- [TAFE Exit Survey](https://data.gov.au/dataset/ds-qld-89970a3b-182b-41ea-aea2-6f9f17b5907e/details?q=exit%20survey)

## Analysis Steps
1. **Data Cleaning**: Processed and cleaned the survey data, including handling missing values and standardizing column names.

2. **Combining Data**: Combined data from both surveys for analysis.

3. **Identifying Dissatisfaction**: Identified employees who resigned due to dissatisfaction based on specific columns.

4. **Service Categorization**: Categorized employees into service categories (New, Experienced, Established, Veteran) based on their years of service.

5. **Initial Analysis**: Analyzed the percentage of employees who resigned due to dissatisfaction in each service category.

## Key Findings
- Employees with more than 7 years of service are more likely to resign due to dissatisfaction with the job.
- Different factors contribute to employees' dissatisfaction, including job dissatisfaction, recognition, and work-life balance.

## Conclusion
This analysis provides insights into employee resignation patterns and factors affecting job satisfaction. Understanding these trends can help organizations address issues and improve employee retention.

## Repository Contents
- `dete_survey.csv`: Dataset containing DETE exit survey responses.
- `tafe_survey.csv`: Dataset containing TAFE exit survey responses.
- `employee_exit_analysis.ipynb`: Jupyter Notebook with data cleaning, analysis, and visualization code.
- `README.md`: This file, providing an overview of the project.

## Dependencies
- Python 3
- pandas
- numpy
- matplotlib

## How to Use
1. Clone the repository to your local machine.
2. Open and run the `employee_exit_analysis.ipynb` notebook to reproduce the analysis.

## Acknowledgements
Data provided by the Department of Education, Training and Employment (DETE) and the Technical and Further Education (TAFE) body of the Queensland government in Australia.

---

*Note: This README provides an overview of the project. For detailed code and analysis, refer to the Jupyter Notebook in the repository.*

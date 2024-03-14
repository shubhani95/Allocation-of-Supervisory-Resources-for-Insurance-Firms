# BOE_assessment: Allocation of Supervisory Resources for Insurance Firms

A Supervision Manager has asked for assistance in allocating scarce resources and determining which firms their team should concentrate on. Supervisory resources may be allocated based on a variety of factors, including firm size, changing business profiles, and outliers from the norm. To help with this process, certain metrics have been provided for analysis.

# Characteristics for Resource Allocation:
1. Firm Size: Larger businesses may require more attention due to their size and potential market impact.
2. Changing Business Profile: Significant changes in data year after year may indicate shifts in a company's operations or risk profile.
3. Outliers from the Norm: Firms that deviate significantly from the average within a single reporting period may necessitate further investigation to determine the reasons for the deviation.

# Provided Metrics:
The following metrics were provided for analysis:
1. Gross Written Premium (GWP): Insurer's total revenue written, equivalent to a non-insurance firm's turnover.
2. Net Written Premium (NWP): GWP minus reinsurance. NWP / GWP will indicate how much risk the firm is passing on to reinsurers.
3. SCR Coverage Ratio: A metric that indicates whether a company is meeting its prudential capital requirements. A ratio greater than 100% indicates that the capital is sufficient to meet the requirement.
4. Gross Claims Incurred: A significant cost for an insurer, so tracking changes over time is critical.
5. Net Combined Ratio = (incurred losses + expenses) / earned premiums. This ratio indicates a firm's profitability. A ratio of less than 100 percent indicates a profit.

# Notes:
1. Data Anonymization: The data has been anonymized with a random multiplier, which may result in unexpected patterns.
2. Metric Selection: While multiple metrics are available, it is not necessary to use all of them for analysis.
3. Outliers: Some data may contain outliers, which could be genuine or incorrectly reported. Distinguishing between the two is crucial.

# Tasks:
# Task I: Data Analysis and Reporting.
Using the provided data, a programming language will be selected to analyze the metrics and generate a short report with tables and charts to highlight firms that require attention.

# Task II: Machine Learning Insights.
Relevant machine-learning techniques will be used to extract additional insights from the data. These findings will be presented in an annex to the report.

# Task III: Cloud-Based Data Processing and Analytics Pipeline.
The report will be moved to cloud technologies, specifically Microsoft Azure, to create an end-to-end data processing and analytics pipeline that assumes daily batch processing of data. Considerations and tools used in this process will be discussed.

# Repository contents:
This repository contains critical resources to help the Supervision Manager allocate resources and analyze firms based on provided metrics. Below is an overview of the contents, along with a detailed explanation of each:

# 1. Analyst_Data_Science_Technical_Assessment_Data.XLSX:
Dataset: The dataset contains several insurance-related metrics, such as Gross Written Premium (GWP), Net Written Premium (NWP), SCR coverage ratio, gross claims incurred, and net combined ratio. The analysis and insights provided in the code notebook and report PDF are based on this dataset.

# 2. BOE_assessment.ipynb
The code notebook is a comprehensive guide that includes detailed implementation steps and code examples for analyzing the provided metrics and creating a short report with tables and charts highlighting firms that require attention (Task I). The notebook also demonstrates how to apply relevant machine-learning techniques to extract additional insights from the dataset. The clustering technique is used to identify patterns and trends in the data (Task II). To run this notebook the user needs to install all the relevant Python libraries such as NumPy, SciPy, Pandas, Sklearn, Tensorflow, Matplotlib, and seaborn. The best way to run the Jupyter Notebook is to create a conda env with all these libraries and use that env. Refer to this page for creating and managing conda env: https://conda.io/projects/conda/en/latest/user-guide/tasks/manage-environments.html#activating-an-environment.

# 3. BOE_assessment.pdf
Based on important metrics, the report offers a thorough analysis of the performance of insurance companies. By analyzing and visualizing large amounts of data, it finds companies that need to be closely watched because of their size, evolving business models, or notable outliers. Additional insights are extracted to support decision-making processes through the use of machine learning techniques. The report also describes how to use Microsoft Azure services to create a cloud-based analytics pipeline and data processing system for scalable and effective analysis. The report's ultimate goal is to provide the Supervision Manager with useful suggestions for maximizing resource allocation and improving supervisory activities in the insurance sector.

# 4. Outliers.csv
This file contains all the information about outliers needed by the supervision manager for allocating resources and identifying firms that require attention.

This repository aims to provide comprehensive support to the supervision manager in allocating resources and identifying firms that require attention via data analysis, machine learning insights, and a cloud-based data processing and analytics pipeline.

Credit Risk Analysis Dashboard
Project Overview

This project presents an interactive Credit Risk Analysis Dashboard designed to evaluate portfolio risk, identify key default drivers, and provide strategic insights for decision-making.

The objective of this analysis is to understand how borrower characteristics influence default behavior and to assess risk distribution across different loan segments. The dashboard focuses on identifying patterns in employment type, loan purpose, credit score, age groups, and loan term to support risk-based lending strategies.

This dashboard is intended to be clear, insightful, and easy to interpret for both technical and non-technical stakeholders.

Data Source

The dataset used in this project is the Loan Default Dataset obtained from Kaggle.

https://www.kaggle.com/datasets/nikhil1e9/loan-default


The dataset contains borrower-level information including:

Loan amount

Loan purpose

Credit score

Employment type

Age

Loan term

Default status

The dataset represents structured financial data suitable for credit risk segmentation and portfolio analysis.

Methodology

The analysis followed a structured data preparation and segmentation process:

Data Cleaning

Reviewed missing values and ensured correct data types.

Validated numerical fields such as loan amount and credit score.

Verified default classification (0 = Non-default, 1 = Default).

Feature Segmentation

Created age bins to group borrowers into meaningful categories.

Segmented credit score ranges to evaluate risk levels.

Grouped loan purposes to compare default exposure.

Categorized employment types to assess financial stability impact.

KPI Calculations

Total Loans

Total Loan Amount

Default Rate

Average Loan Amount

Risk Analysis Approach

Compared default rates across borrower segments.

Identified primary risk drivers.

Evaluated whether loan term significantly impacts default probability.

The dashboard was built using Google Looker Studio as a live, interactive reporting solution.

Dashboard Overview

The dashboard is structured into four main sections:

KPI Summary (Top Section)
Provides a high-level overview of portfolio exposure and performance.

Risk Segmentation Analysis
Visual breakdown of default behavior by:

Loan purpose

Credit score

Employment type

Age group

Loan term

Dashboard Screenshots
<img width="1080" height="805" alt="image" src="https://github.com/user-attachments/assets/af696a62-5049-46b1-b829-6f3dfa0c3afd" />




Key Insights

• The overall default rate indicates a moderate level of portfolio risk.

• Default risk varies by loan purpose, suggesting differences in inherent risk across loan categories.

• Credit score is a primary determinant of default behavior, with lower score segments showing higher risk exposure.

• Employment stability influences repayment reliability.

• Default levels show variation across age groups, reflecting financial stability differences.

• Loan term differences appear relatively consistent, indicating that duration alone is not a strong risk driver in this dataset.

Strategic Recommendations

• Strengthen underwriting standards for lower credit score segments.

• Apply risk-based pricing aligned with borrower risk profiles.

• Enhance monitoring for higher-risk loan purposes and vulnerable borrower groups.

Assumptions & Limitations

The dataset is static and does not include time-series behavior for trend analysis.

Income data is not detailed enough to measure debt-to-income impact.

The dataset represents a simplified financial scenario and may not reflect real-world banking complexity.

External macroeconomic factors are not included in the analysis.

Live Dashboard

The interactive dashboard can be accessed via the following link:

https://lookerstudio.google.com/s/hJiUizy3sa0

Prepared by: najla mohammed

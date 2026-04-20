# Linguistic-Performance-Analytics-Workforce-English-Proficiency-Mapping

📊 Linguistic Performance Analytics: Workforce English Proficiency Mapping
Analyzing CEFR-aligned English test results to drive data-informed corporate training strategies.

📋 Project Overview
This project performs an end-to-end Exploratory Data Analysis (EDA) on internal English proficiency test results from MiTek Vietnam. By cleaning and analyzing workforce scores across Listening, Reading, and Writing, the analysis identifies high-performing employee clusters, uncovers data discrepancies, and provides actionable recommendations for targeted language development programs.

🛠️ Tech Stack
Language: Python 3.x

Libraries: * Pandas (Complex data cleaning and transformation)

Matplotlib / Seaborn (Statistical visualization)

re (Regular expression for string manipulation)

Environment: Jupyter Notebook / Google Colab

🎯 The Analytical Challenges
1. Data Integrity & Cleaning
The raw dataset contained merged headers, non-standard score formats, and mixed data types across departmental categories.

Solution: Implemented robust cleaning scripts to handle multi-level headers, drop redundant columns, and standardize categorical names.

2. Proficiency Distribution Analysis
Understanding the workforce’s actual skill level required mapping raw scores to the CEFR (Common European Framework of Reference for Languages) scale.

Solution: Engineered visualizations to map the distribution of A1 through C1 levels across different staff groups, identifying that the "Unknown Group" contained some of the company’s highest-performing individuals (B2/C1 levels).

3. Discrepancy Identification
Some staff records showed an overall CEFR level despite having incomplete scores in specific skill sub-sections.

Solution: Conducted a Data Discrepancy Analysis to highlight these outliers for HR justification, ensuring the final report reflects an accurate audit of staff capabilities.

🏗️ Key Insights & Recommendations
Identify High-Potential Groups: The analysis isolated a specific high-performing group achieving C1/B2 levels, recommending them for advanced leadership roles or international collaboration.

Targeted Training: Identified specific skill gaps (e.g., Writing vs. Listening) to move away from "one-size-fits-all" training toward skill-specific modules.

Future Data Enrichment: Proposed adding "Years of Experience" and "Previous Training History" as features to build predictive models for future language acquisition.

🏗️ Project Workflow
Ingestion: Loading multi-sheet Excel data with specific header offsets.

Refactoring: Using Regex to clean departmental labels and employee identifiers.

Visualization: Generating bar charts and histograms to visualize score distributions across Listening, Reading, and Overall CEFR levels.

Strategic Synthesis: Translating statistical outputs into business-centric recommendations for training and development.

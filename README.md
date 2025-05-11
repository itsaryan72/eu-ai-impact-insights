# eu-ai-impact-insights
A data-driven exploration of the EU AI Act, its risk classifications, and AI readiness across EU nations.

Introduction

The **EU AI Act** is the European Union's first attempt to regulate Artificial Intelligence in a structured and risk-based way. As AI rapidly integrates into healthcare, transportation, law enforcement, and finance, the EU is taking steps to ensure it's used **ethically, transparently, and safely**.

This act classifies AI systems into **four risk categories**: 
- **Unacceptable Risk**
- **High Risk**
- **Limited Risk**
- **Minimal Risk**

Our project aims to explore:
- How AI is being adopted across different EU countries
- Which sectors and applications face the most scrutiny
- How prepared each country is to handle these regulations

Through data analysis and visualization, we’ll uncover which industries and nations may be most impacted — and provide insights for future readiness.



To analyze the impact of the EU AI Act, consider the following datasets:
1. Risk Classification Database by appliedAI Institute
Description: An open and free database providing practical examples of high-risk and non-high-risk AI use cases under the EU AI Act.
Access: Risk Classification Database

2. EU AI Act Risk Categories Summary
Description: Detailed explanations of the risk categories defined in the EU AI Act, including Unacceptable Risk, High Risk, and Limited or Minimal Risk.
Access: Understanding EU AI Act Risk Categories

3. EU AI Act Official Documentation
Description: The official text of the EU AI Act, providing comprehensive information on the regulation's provisions.
Access: EU AI Act Official Text

🧾 How Is the Data Structured?

The datasets typically include the following fields:
Use Case: Description of the AI application.
Risk Category: Classification under the EU AI Act (e.g., High Risk, Limited Risk).
Sector: Industry sector where the AI application is used (e.g., Healthcare, Finance).
Compliance Requirements: Specific obligations for the AI application under the EU AI Act.
Country: EU member state where the AI application is deployed (if applicable).

📊 Completed Visualizations:

Risk Class Distribution – overall view of high vs. low-risk systems.
Risk Class by Enterprise Function – shows how risk varies across business areas.
Applicable Annex Breakdown – reveals which annex is most commonly cited.
Annex vs. Risk Class – insight into the regulatory depth vs. AI system risk.
Enterprise Function Adoption – highlights which sectors are using AI the most.

EU AI Impact Insights
A data-driven exploration of the EU AI Act, its risk classifications, and AI readiness across EU nations.

📊 Overview
This project analyzes AI applications within the EU, focusing on their classification under the EU AI Act. By examining various enterprise functions and their associated risk levels, we aim to understand the regulatory landscape and its implications for AI deployment.

🔍 Key Features
Data Cleaning: Handled missing values and standardized data for accurate analysis.

Visualization: Created plots to depict the distribution of AI applications across risk categories.

Insights: Identified trends and patterns in AI risk classifications.

📁 Repository Contents
eu_ai_analysis.ipynb: Jupyter Notebook containing the data analysis and visualizations.

data/: Directory containing the dataset used for analysis.


🚀 Getting Started

Clone the Repository:
git clone https://github.com/itsaryan72/eu-ai-impact-insights.git

Navigate to the Project Directory:
cd eu-ai-impact-insights

Install Dependencies:
pip install -r requirements.txt

Run the Notebook:
Open eu_ai_analysis.ipynb in Jupyter Notebook and execute the cells sequentially.

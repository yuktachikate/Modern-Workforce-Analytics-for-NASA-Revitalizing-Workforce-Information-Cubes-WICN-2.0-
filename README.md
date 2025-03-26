# Modern Workforce Analytics for NASA: Revitalizing Workforce Information Cubes (WICN 2.0)

This project demonstrates a modern approach to workforce analytics by combining robust ETL processes, multidimensional OLAP analysis, interactive visualizations, and predictive modeling to support strategic workforce planning. It revitalizes NASA's Workforce Information Cubes (WICN) using advanced data-driven methodologies.

## Overview

The project covers the following key components:

- **ETL and Data Integration:**  
  Simulates the extraction, transformation, and loading of workforce data. Key metrics include salary, performance scores, hire dates, and computed tenure.

- **OLAP Analysis:**  
  Utilizes pivot tables to create multidimensional summaries (e.g., employee counts, salary averages, and performance metrics) across departments and positions.

- **Interactive Visualizations:**  
  Employs Plotly to generate dynamic charts (box plots, bar charts, and line charts) that reveal trends in performance, compensation, and attrition rates.

- **Predictive Modeling:**  
  Uses logistic regression to forecast attrition risk, evaluated through performance metrics including ROC curves and confusion matrices.

- **Future Directions:**  
  Provides recommendations for integrating real-time data feeds, advanced modeling techniques, interactive dashboards, and enhanced data governance.

## Project Structure

- **notebook.ipynb:**  
  A Google Colab (or Jupyter Notebook) file that contains the complete end-to-end workflow.

- **README.md:**  
  This file, which explains the project, its components, and usage instructions.

## Requirements

- Python 3.x
- Google Colab or Jupyter Notebook
- Python Libraries:
  - `pandas`
  - `numpy`
  - `matplotlib`
  - `seaborn`
  - `plotly`
  - `scikit-learn`
  - `IPython.display`

## Installation

1. **Clone or Download:**  
   Clone the repository or download the `notebook.ipynb` and `README.md` files.

2. **Install Dependencies:**  
   Ensure you have the required libraries installed. You can install missing packages using pip:

   ```bash
   pip install pandas numpy matplotlib seaborn plotly scikit-learn

# Usage
**Execute the Notebook:**
Run each cell sequentially. The notebook will:

1. Simulate and preprocess workforce data.

2. Generate OLAP pivot tables for multidimensional workforce analysis.

3. Create interactive visualizations to explore performance, salary, and attrition trends.

4. Train and evaluate a logistic regression model to predict attrition risk.

5. Provide conclusions and recommendations for future improvements.

**Review Analysis:**
Examine the outputs including pivot tables, charts, ROC curves, and feature importance plots. Use these insights to inform workforce planning strategies.

# Future Directions
**Real-time Data Feeds:**
Integrate real-time data streams from operational systems for continuous updates.

**Advanced Predictive Modeling:**
Explore ensemble methods, deep learning, or time-series models to enhance forecasting accuracy.

**Interactive Dashboards:**
Develop self-service dashboards using frameworks like Dash or Streamlit for real-time insights.

**Data Governance & Security:**
Strengthen protocols to safeguard sensitive workforce information and comply with regulatory standards.

**Ethical Analysis:**
Investigate model bias, fairness, and feature relevance to ensure equitable workforce planning.

**Refined ETL Processes:**
Continuously improve data extraction, transformation, and enrichment to boost overall data quality.

# Conclusion
This project lays a robust foundation for data-driven workforce planning at NASA by modernizing the legacy Workforce Information Cubes. It combines ETL, OLAP analysis, interactive visualization, and predictive modeling to offer actionable insights for strategic decision-making. Future enhancements will further empower workforce planners and improve the system's scalability and accuracy.

# License
This project is provided "as is" without warranty of any kind.

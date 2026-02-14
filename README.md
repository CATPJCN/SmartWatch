## Smartwatch Health Data: Exploratory Data Analysis (EDA)

### Project Overview
This project involves a comprehensive Exploratory Data Analysis (EDA) of 10,000 health observations collected from smartwatch users. The goal was to clean a "dirty" dataset and prepare it for marketing insights while maintaining high statistical integrity.

### Technical Skills Demonstrated
- Data Cleaning: Handled inconsistent strings (e.g., "Very High", "ERROR") and impossible values (negative sleep hours) using Python's pandas library.

- Statistical Reasoning: Performed a Sensitivity Analysis to validate data removal.

- Data Visualization: Built a Master EDA Dashboard using Seaborn and Matplotlib to analyze distributions and identify outliers.

### Key Statistical Findings: 
**The "0.02 Bias" Check**
A critical part of this analysis was deciding how to handle 49 non-standard "Very High" entries in the Stress Level column.

- Scenario A (Recoding): If "Very High" was forced to a value of 10.

- Scenario B (Coercion): If "Very High" was coerced to NaN

- Conclusion: Because the difference was only less than 0.02, the data was coerced to NaN to avoid "guessing" values, as the impact on the overall population density was negligible.

### Project Structure
- Smartwatch_Analysis.ipynb: The primary Python notebook containing the cleaning pipeline and visualizations.

- requirements.txt: List of necessary Python libraries (Pandas, Seaborn, etc.).

### Setup Instructions
* **Clone the repository.**

* **Create a virtual environment:**

python -m venv venv

* **Activate the environment:**

Windows: .\venv\Scripts\activate
Mac/Linux: source venv/bin/activate

* **Install dependencies:**
  
pip install -r requirements.txt

* **Run the Notebook:**

Open Smartwatch_Analysis.ipynb and select the venv kernel.
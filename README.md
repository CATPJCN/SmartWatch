# Smartwatch Health Data: Exploratory Data Analysis (EDA)


### Project Overview
This project involves a comprehensive **Exploratory Data Analysis (EDA)** of 10,000 health observations. The objective was to clean a "dirty" dataset and prepare it for marketing insights while maintaining high statistical integrity.


### Technical Skills Demonstrated
* **Data Cleaning:** Handled inconsistent strings (e.g., `"Very High"`, `"ERROR"`), impossible values,(negative sleep hours) and data mismatch using Python's `pandas` library.
* **Statistical Reasoning:** Performed a Sensitivity Analysis to validate data removal and ensure population representativeness.
* **Data Visualization:** Built a Master EDA Dashboard using `Seaborn` and `Matplotlib` to analyze distributions and identify outliers.


### Project Structure
* `Smartwatch_Analysis.ipynb`: The primary Python notebook containing the cleaning pipeline and visualizations.
* `requirements.txt`: List of necessary Python libraries (Pandas, Seaborn, etc.).
* `unclean_smartwatch_health_data.csv`: Data set used in this project from kaggle (https://www.kaggle.com/datasets/mohammedarfathr/smartwatch-health-data-uncleaned)

---
---

### Setup Instructions

#### 1. Clone the repository
```bash
git clone <SmartWatch-repository-link>
cd <your-SmartWatch-folder-name>
```

---

#### 2. Create a virtual environment

Windows: 
```bash
python -m venv venv
```

Mac/Linux: 
```bash
python3 -m venv venv
```

---

#### 3. Activate the environment:

Windows: 
```bash
.\venv\Scripts\activate
```

Mac/Linux: 
```bash
source venv/bin/activate
```

---

#### Recommenedation (Update Pip)
Windows: 
```bash
python -m pip install --upgrade pip
```

Mac/Linux: 
```bash
pip install --upgrade pip
```

---

#### 4. Install dependencies:
  
Windows: 
```bash
pip install -r requirements.txt
```

Mac/Linux: 
```bash
pip install -r requirements.txt
```

---

#### 5. Run the Analysis in IDE

1. Open the project folder in your IDE.
2. Open `Smartwatch_Analysis.ipynb`.
3. Set your kernel to the `./venv` environment.
4. Run cells directly within the editor.
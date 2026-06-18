# Screen Time Analytics Dashboard 📊

A data analytics project that combines **Python (Pandas & Matplotlib)** and **Power BI** to clean, analyze, and visualize screen-time behavior data sourced from Kaggle.

The project demonstrates an end-to-end analytics workflow, from raw data preprocessing to dashboard creation and reporting.

---

## Overview

This project follows a complete data analytics pipeline:

1. Collect data from a public Kaggle dataset
2. Clean and preprocess the data using Python and Pandas
3. Handle missing values and duplicate records
4. Perform exploratory data analysis (EDA)
5. Create visualizations using Matplotlib
6. Import the cleaned dataset into Power BI
7. Build an interactive dashboard for deeper analysis

---

## Files in this Repository

| File                      | Description                                  |
| ------------------------- | -------------------------------------------- |
| `combined_output.csv`     | Dataset used for analysis                    |
| `screen_time_analysis.py` | Python script for cleaning and visualization |
| `data_visuals.pbix`       | Power BI dashboard                           |
| `data_visuals (2).pdf`    | PDF export of the dashboard                  |
| `README.md`               | Project documentation                        |

---

## Data Cleaning Process

The dataset was cleaned using Pandas by:

* Removing duplicate records
* Removing completely empty rows
* Filling missing numerical values using the median
* Filling missing categorical values using the mode
* Verifying and validating data quality

Example:

```python
df = df.drop_duplicates()
df = df.dropna(how='all')
```

---

## Exploratory Data Analysis (Matplotlib)

The following visualizations were generated using Matplotlib:

### 1. Age Distribution

Analyzes the age demographics of participants.

### 2. Gender Distribution

Shows the distribution of users by gender.

### 3. Average Daily Screen Time by Gender

Compares average screen-time habits across genders.

### 4. Primary Device Usage

Identifies the most commonly used devices.

### 5. Urban vs Rural Distribution

Examines demographic differences between urban and rural users.

### 6. Health Impacts Analysis

Highlights the frequency of reported health impacts associated with screen usage.

---

## Power BI Dashboard

The cleaned dataset was imported into Power BI to create an interactive dashboard featuring:

* **KPI Cards** for key summary metrics
* **Bar Charts** for demographic and device analysis
* **Pie Charts** for category distribution
* **Interactive Filters and Slicers**
* **Comparative Visualizations** across user groups
* **Data Tables** for detailed record inspection

The dashboard allows users to explore relationships between screen time, demographics, device usage, and health impacts.

A static version of the dashboard is available in:

```text
data_visuals (2).pdf
```

---

## Getting Started

### Prerequisites

Install Python dependencies:

```bash
pip install pandas matplotlib
```

For dashboard exploration:

* Power BI Desktop (free)

### Run the Python Analysis

```bash
python screen_time_analysis.py
```

### Open the Power BI Dashboard

1. Open `data_visuals.pbix` in Power BI Desktop.
2. Refresh the data source if prompted.
3. Interact with filters, charts, and KPI cards.

---

## Technologies Used

| Tool             | Purpose                           |
| ---------------- | --------------------------------- |
| Python           | Data processing and analysis      |
| Pandas           | Data cleaning and manipulation    |
| Matplotlib       | Exploratory data visualization    |
| Power BI Desktop | Interactive dashboard development |
| Kaggle           | Dataset source                    |
| Git & GitHub     | Version control and collaboration |

---

## Skills Demonstrated

* Data Cleaning
* Data Preprocessing
* Exploratory Data Analysis (EDA)
* Data Visualization
* Dashboard Design
* Power BI Reporting
* Python Programming
* Working with Real-World CSV Datasets

---

## Future Improvements

* Add statistical analysis and hypothesis testing
* Introduce interactive visualizations with Plotly
* Build a Streamlit dashboard
* Automate data refresh and reporting workflows

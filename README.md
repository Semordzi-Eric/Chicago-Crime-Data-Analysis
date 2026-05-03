# Chicago Crime Data Analysis

A data analysis project focused on exploring and visualizing crime patterns in Chicago using a historical dataset. This project performs data cleaning, feature engineering, and exploratory data analysis (EDA) to identify crime trends over time and high-crime locations.

## 📊 Project Overview

This repository contains a Jupyter Notebook that processes the Chicago Crime dataset to extract meaningful insights. The analysis covers:
- Data cleaning and preprocessing (handling missing values).
- Time-series analysis of crime occurrences.
- Identification of "hot blocks" with the highest frequency of reported crimes.
- Distribution of crimes by hour, day, and month.

## 🛠️ Technologies Used

- **Python 3.x**
- **Pandas**: Data manipulation and analysis.
- **Matplotlib**: Core plotting library.
- **Seaborn**: Statistical data visualization.
- **Jupyter Notebook**: Interactive development environment.

## 📁 Dataset

The analysis is based on the **Chicago Crime Data**, which includes attributes such as:
- **ID & Case Number**: Unique identifiers for each incident.
- **Date**: Timestamp of the occurrence.
- **Primary Type**: Category of the crime (e.g., Assault, Homicide, Burglary).
- **Location Description**: Type of location (e.g., Street, Apartment).
- **Arrest**: Whether an arrest was made (True/False).
- **Coordinates**: Latitude and Longitude for spatial analysis.

## 🚀 Getting Started

### Prerequisites

Ensure you have Python installed. You can install the required libraries using pip:

```bash
pip install pandas matplotlib seaborn notebook
```

### Running the Analysis

1. Clone this repository:
   ```bash
   git clone https://github.com/Semordzi-Eric/Crime-Date-Analysis.git
   ```
2. Navigate to the project directory:
   ```bash
   cd Crime-Date-Analysis
   ```
3. Launch Jupyter Notebook:
   ```bash
   jupyter notebook
   ```
4. Open `crime_data.ipynb` and run the cells.

## 📈 Key Insights

- **Trend Analysis**: Visualized the fluctuation of crime rates over several years.
- **Location Analysis**: Identified the top 10 most dangerous blocks based on report frequency.
- **Temporal Patterns**: Analyzed how crime rates change depending on the time of day and month.

## 📜 License

This project is open-source and available under the [MIT License](LICENSE).

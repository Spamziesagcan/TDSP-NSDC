# Transportation Data Science Project (TDSP) - NSDC

## 🚗 Overview:

This project is part of the National Student Data Corps (NSDC) initiative. It uses real-world transportation data to uncover insights through Data Science techniques like EDA, clustering, and visualization to enhance urban mobility and transportation planning.

## 📌 Table of Contents:

1. Objective
2. Dataset Description
3. Technologies & Libraries Used
4. Methodology
5. Key Findings
6. How to Run
7. Contributing
8. License
9. Contact

## 🔍 Objective:

To analyze and visualize transportation patterns, identify peak travel times, and segment passengers using clustering methods to help optimize public transport operations and strategies.

## 📁 Dataset Description:

CRASH\_DATE and CRASH\_TIME: Date and time of the crash

BOROUGH: The NYC borough where the crash occurred

ZIP\_CODE: ZIP code of the crash

LATITUDE, LONGITUDE: Coordinates for geospatial analysis

LOCATION: Combined lat-long

ON\_STREET\_NAME, CROSS\_STREET\_NAME, OFF\_STREET\_NAME

NUMBER\_OF\_PERSONS\_INJURED, NUMBER\_OF\_PERSONS\_KILLED

NUMBER\_OF\_PEDESTRIANS\_INJURED, NUMBER\_OF\_PEDESTRIANS\_KILLED

NUMBER\_OF\_CYCLIST\_INJURED, NUMBER\_OF\_CYCLIST\_KILLED

NUMBER\_OF\_MOTORIST\_INJURED, NUMBER\_OF\_MOTORIST\_KILLED

CONTRIBUTING\_FACTOR\_VEHICLE\_X: Suspected causes of crash

VEHICLE\_TYPE\_CODE\_X: Type of vehicle involvedThe data has been cleaned, processed, and formatted for analysis.

## 📊 Technologies & Libraries Used:

- Python 3.8+
- pandas, numpy
- matplotlib, seaborn, plotly
- scikit-learn
- datetime

## 🧠 Methodology:

1. Data Preprocessing:

   - Handling missing values
   - Parsing and extracting date/time features

2. Exploratory Data Analysis (EDA):

   - Travel volume trends by time
   - Route and station popularity
   - Passenger segmentation

3. Clustering:

   - Used KMeans algorithm
   - Elbow method to determine optimal clusters
   - PCA for visualizing clusters

4. Visualization:

   - Time series plots
   - Route heatmaps
   - Cluster scatter plots

## 📈 Key Findings:

- Peak travel occurs during rush hours (morning & evening)
- Certain stations serve as transport hubs
- KMeans clusters revealed diverse travel behavior patterns
- Insights can inform public transport scheduling and fare models

## 🛠 How to Run:

Requirements:

- Python 3.8+
- Jupyter Notebook

Steps:

1. Clone the repository:
   git clone [https://github.com/yourusername/TDSP-NSDC.git](https://github.com/yourusername/TDSP-NSDC.git)
   cd TDSP-NSDC

2. Create and activate a virtual environment:
   python -m venv venv
   source venv/bin/activate  (on Windows: venv\Scripts\activate)

3. Install dependencies:
   pip install -r requirements.txt

4. Open the notebook:
   jupyter notebook Transportation\_Data\_Science\_Project\_(TDSP)\_NSDC.ipynb

##

## 🤝 Contributing:

1. Fork the repo
2. Create a new branch: git

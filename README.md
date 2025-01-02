# **Global Terrorism - Exploratory Data Analysis (EDA)**

An insightful data analysis project to understand global terrorism trends using Python libraries such as Pandas, NumPy, Matplotlib, and Seaborn. This project utilizes the **Global Terrorism Database (GTD)** to visualize and interpret patterns, impacts, and statistics related to terrorism worldwide.

---

## **Table of Contents**
- [Introduction](#introduction)
- [Dataset](#dataset)
- [Installation](#installation)
- [Project Workflow](#project-workflow)
- [Key Insights](#key-insights)
- [Visualizations](#visualizations)
- [Technologies Used](#technologies-used)
- [Contributing](#contributing)
- [License](#license)

---

## **Introduction**
Terrorism is one of the most pressing issues in the world today. Through this project, we aim to perform an in-depth analysis of historical terrorism data to identify trends, hotspots, and the impact of such activities globally. 

---

## **Dataset**
>> Dataset Link: https://bit.ly/2TK5Xn5

- **Source:** [Global Terrorism Database (GTD)](https://www.start.umd.edu/gtd/)
- **Description:** The dataset contains detailed information about terrorist events worldwide from 1970 to the most recent year available.
- **Attributes:** Includes information such as attack type, target type, region, country, year, fatalities, injuries, and more.

---

## **Installation**
Follow these steps to set up the project on your local system:

1. Clone the repository:
   ```bash
   git clone https://github.com/anmol2517/Global-Terrorism-EDA.git
   cd global-terrorism-eda
   ```

2. Install required libraries:
   ```bash
   pip install pandas numpy matplotlib seaborn jupyter
   ```

3. Start Jupyter Notebook:
   ```bash
   jupyter notebook
   ```

4. Open the `Global_Terrorism_EDA.ipynb` file and run the cells.

---

## **Project Workflow**
1. **Data Loading and Cleaning**:
   - Import the GTD dataset and handle missing or inconsistent data.
2. **Exploratory Data Analysis**:
   - Analyze various features such as attack types, target types, regions, and more.
   - Identify global hotspots and trends over the years.
3. **Visualizations**:
   - Generate insights using visualizations to represent trends and distributions.
4. **Insights and Reporting**:
   - Summarize findings with data-backed insights.

---

## **Key Insights**
- **Top affected regions** and countries by terrorist activities.
- **Most common attack types** and their impact (e.g., bombings, assassinations).
- **Yearly trends** in terrorism incidents, fatalities, and injuries.
- Insights into **target types** (e.g., civilians, governments).
  
---

## **Visualizations**
The project contains the following visualizations:
1. Yearly trends of terrorist incidents.
2. Heatmaps of terrorism intensity by region.
3. Distribution of attack types and their impact.
4. Pie charts for target-type distributions.
5. Correlation heatmap of fatalities and injuries.

---

## **Technologies Used**
- **Languages:** Python
- **Libraries:**
  - Pandas
  - NumPy
  - Matplotlib
  - Seaborn
- **Tools:** Jupyter Notebook

---

## **Contributing**
Contributions are welcome! Please follow the steps below:
1. Fork the repository.
2. Create a feature branch: `git checkout -b feature-name`.
3. Commit your changes: `git commit -m 'Add some feature'`.
4. Push to the branch: `git push origin feature-name`.
5. Create a pull request.

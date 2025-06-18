# PRODIGY_DS_01

📊 Task-01: Population Data Visualization
Internship Track: Data Science Intern at Prodigy InfoTech
Track Code: PRODIGY_DS_01

🎯 Objective
Visualize the distribution of a categorical or continuous variable using the World Bank Total Population Dataset.
This task focuses on analyzing either:

🟢 Categorical Data (e.g., countries or regions)

🔵 Continuous Data (e.g., population numbers)

🔗 Dataset Source
World Bank - Total Population
🔗 https://data.worldbank.org/indicator/SP.POP.TOTL


💻 Technologies Used
Python

Pandas

Matplotlib

Seaborn

Jupyter Notebook / Google Colab

🔧 Installation
Install the required libraries:

bash
Copy
Edit
pip install pandas matplotlib seaborn

📁 Steps Performed
1. Dataset Loading
CSV file downloaded from World Bank portal

Read using pandas.read_csv() (with skiprows=4 to skip metadata rows)

2. Data Filtering
Selected specific countries like India, China, USA, Brazil, etc.

Extracted latest available year for analysis (e.g., 2022)

3. Visualization
4. 
🟪 Bar Chart (Categorical)
Visualizes population distribution for selected countries.


🟦 Histogram (Continuous)
Shows how population is distributed across all countries in the dataset.

📌 Summary
Extracted relevant data from the World Bank dataset

Created bar and histogram plots using Python

Derived insights about population distribution globally and among selected countries

📁 Folder Structure

📦Task-01

 ┣ 📄 README.md
 
 ┣ 📄 population_analysis.ipynb
 
 ┗ 📄 World_Bank_Population.csv

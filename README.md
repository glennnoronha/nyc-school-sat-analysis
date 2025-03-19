nyc-school-sat-analysis
Project Overview
This project performs Exploratory Data Analysis (EDA) on NYC school SAT scores. It focuses on:

Identifying schools with strong math performance (Math SAT ≥ 640).
Ranking the top 10 schools based on total SAT scores.
Determining which borough has the largest standard deviation in total SAT scores.
Dataset
The dataset used is schools.csv, which contains information about NYC schools, including:

school_name - Name of the school
borough - Borough where the school is located
average_math - Average Math SAT score
average_reading - Average Reading SAT score
average_writing - Average Writing SAT score
Analysis Performed
Filtering Best Math Schools: Selecting schools with Math SAT ≥ 640 (80% of 800).
Top 10 Schools by Total SAT: Computing total_SAT = average_math + average_reading + average_writing and selecting the top 10 schools.
Borough with Largest SAT Score Variability: Finding the borough with the highest standard deviation of total SAT scores.
Results
Best Math Schools: Schools with Math SAT ≥ 640, sorted in descending order.
Top 10 Schools: Ranked by total SAT score.
Borough with Highest Variability: The borough with the largest SAT standard deviation.
How to Run the Project
Requirements
Ensure you have the following installed:

Python (>=3.7)
Pandas
Matplotlib
Jupyter Notebook (if running the notebook version)
Steps
Clone the repository or extract the files.
Install dependencies:
sh
Copy
Edit
pip install pandas matplotlib jupyter
Open notebook.ipynb in Jupyter Notebook and run the cells.
Check the printed outputs for insights.
File Structure
bash
Copy
Edit
workspace/
│── notebook.ipynb        # Jupyter Notebook with the analysis
│── schools.csv           # Dataset used
│── boroughs.csv          # Processed borough statistics
│── README.md             # This documentation
Notes
The analysis can be extended by exploring additional factors like school demographics or funding.
You can experiment further by modifying filtering criteria or adding new statistical insights.
License
This project is for educational purposes and follows an open-source license.

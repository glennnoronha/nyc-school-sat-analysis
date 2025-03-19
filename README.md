# nyc-school-sat-analysis
## Project Overview
This project performs **Exploratory Data Analysis (EDA)** on NYC school SAT scores. It focuses on:
- Identifying schools with **strong math performance** (Math SAT ≥ 640).
- Ranking the **top 10 schools based on total SAT scores**.
- Determining which **borough has the largest standard deviation in total SAT scores**.

## Dataset
The dataset used is **schools.csv**, which contains information about NYC schools, including:
- `school_name` - Name of the school  
- `borough` - Borough where the school is located  
- `average_math` - Average Math SAT score  
- `average_reading` - Average Reading SAT score  
- `average_writing` - Average Writing SAT score  

## Analysis Performed
1. **Filtering Best Math Schools**: Selecting schools with **Math SAT ≥ 640** (80% of 800).  
2. **Top 10 Schools by Total SAT**: Computing **total_SAT** = `average_math` + `average_reading` + `average_writing` and selecting the top 10 schools.  
3. **Borough with Largest SAT Score Variability**: Finding the borough with the **highest standard deviation of total SAT scores**.  

## Results
- **Best Math Schools**: Schools with **Math SAT ≥ 640**, sorted in descending order.  
- **Top 10 Schools**: Ranked by **total SAT score**.  
- **Borough with Highest Variability**: The borough with the **largest SAT standard deviation**.  

## How to Run the Project
### Requirements
Ensure you have the following installed:
- Python (>=3.7)
- Pandas
- Matplotlib
- Jupyter Notebook (if running the notebook version)

### Steps
1. Clone the repository or extract the files.
2. Install dependencies:
   ```sh
   pip install pandas matplotlib jupyter

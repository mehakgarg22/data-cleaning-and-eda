# Data Cleaning and Exploratory Data Analysis (EDA)

## About the Project
This project uses Python to clean and explore the Titanic passenger dataset. It focuses on handling missing values, identifying duplicate records, performing statistical analysis, and visualizing patterns related to passenger survival.

## Objectives
- Identify and handle missing values.
- Check and remove duplicate records.
- Perform descriptive statistical analysis.
- Explore relationships between passenger characteristics and survival.
- Create visualizations to communicate findings.

## Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Google Colab

## Dataset
The project uses the Titanic dataset, which contains information about passenger age, sex, passenger class, ticket fare, embarkation details, and survival status.

**Dataset Source:** [Titanic Dataset](https://github.com/mwaskom/seaborn-data/blob/master/titanic.csv)

## Project Workflow
1. Load and inspect the dataset.
2. Identify missing values.
3. Analyze duplicate records.
4. Handle missing values and clean the data.
5. Perform descriptive statistical analysis.
6. Explore survival patterns.
7. Create visualizations.
8. Summarize findings and limitations.

## Visualizations
- Passenger survival count
- Survival by gender
- Survival by passenger class
- Distribution of passenger ages
- Ticket fare distribution using a box plot
- Average ticket fare by passenger class

## Key Findings
- Overall survival rate in the cleaned dataset was approximately **41.29%**.
- Female passengers had a higher survival rate (**73.97%**) than male passengers (**21.53%**).
- First-class passengers had a survival rate of **63.33%**, compared with **50.61%** in second class and **25.94%** in third class.
- The average passenger age was approximately **29.58 years**.
- The average ticket fare was approximately **34.88**.

These findings describe patterns in the dataset and do not establish cause-and-effect relationships.

## Data Cleaning
- Dropped the `deck` column because it contained a substantial number of missing values.
- Filled missing ages using the median.
- Filled missing embarkation values using the mode.
- Checked for and removed exact duplicate rows.

**Note:** Removing duplicate rows may remove valid passenger records if different passengers share identical values across all columns. This is an important limitation of the current cleaning approach.

## Limitations
- The analysis uses historical Titanic passenger data.
- Relationships observed in the data do not prove causation.
- Missing-value handling can affect the results.
- Removing duplicate rows may affect the dataset and survival statistics.

## How to Run
1. Open `data_cleaning_and_eda.ipynb` in Google Colab or Jupyter Notebook.
2. Ensure the required Python libraries are installed.
3. Run the notebook cells in order.
4. Review the cleaning process, visualizations, and findings.

## Author
**Mehak Garg**

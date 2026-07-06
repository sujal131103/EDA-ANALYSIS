# Task 5: Exploratory Data Analysis (EDA) - Titanic Dataset

## Objective

The objective of this task is to perform Exploratory Data Analysis (EDA) on the Titanic dataset using Python. The analysis helps to understand the dataset, identify missing values, study relationships between variables, visualize patterns, and summarize important observations.

## Tools Used

- Python
- Pandas
- Matplotlib
- Seaborn
- Jupyter Notebook

## Dataset

The Titanic dataset is used for this analysis. The main file used is:

- `train.csv`

Other files available in the dataset:

- `test.csv`
- `gender_submission.csv`

The `train.csv` file contains passenger information such as age, gender, passenger class, fare, embarkation point, and survival status.

## Steps Performed

1. Imported the required Python libraries.
2. Loaded the Titanic dataset using Pandas.
3. Displayed the first few rows of the dataset.
4. Checked dataset information using `info()`.
5. Generated summary statistics using `describe()`.
6. Checked missing values using `isnull().sum()`.
7. Used `value_counts()` to understand categorical columns.
8. Created count plots, histograms, boxplots, heatmaps, and pairplots using Seaborn and Matplotlib.
9. Identified relationships and trends in the dataset.
10. Wrote final observations and summary.

## Visualizations Created

- Survival count plot
- Survival by gender
- Survival by passenger class
- Age distribution
- Fare distribution
- Age vs survival boxplot
- Fare by passenger class boxplot
- Correlation heatmap
- Pairplot of selected numerical columns

## Key Observations

- Female passengers had a higher survival rate than male passengers.
- Passengers in 1st class had a better chance of survival than passengers in 2nd and 3rd class.
- The `Age` column contains missing values.
- The `Fare` column contains outliers because some passengers paid very high ticket prices.
- Passenger class, gender, fare, and age appear to be important factors related to survival.
- Most passengers in the dataset did not survive.

## Conclusion

Exploratory Data Analysis on the Titanic dataset shows that survival was strongly influenced by gender and passenger class. Female passengers and 1st class passengers had higher survival chances. The analysis also helped identify missing values, outliers, and relationships between different features.

## How to Run

1. Open Jupyter Notebook.
2. Keep `train.csv` in the same folder as the notebook.
3. Run each code cell step by step.
4. View the outputs, charts, and final observations.

## Submitted By

Name: sujal bansode
Internship Task: Task 5 - Exploratory Data Analysis

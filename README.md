# Student Performance Data Analysis Using Python

## Project Overview
This project analyzes students' examination scores using Python. It explores Maths, Reading, and Writing marks and examines how factors such as gender, test preparation, lunch type, and parental level of education relate to students' average performance.

## Dataset
- **File:** `StudentsPerformance.csv`
- **Source:** [Students Performance in Exams – Kaggle](https://www.kaggle.com/datasets/spscientist/students-performance-in-exams)
- **Records:** 1,000 students
- **Original columns:** gender, race/ethnicity, parental level of education, lunch, test preparation course, math score, reading score, writing score.

## Tools and Libraries
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- SciPy

## Project Workflow
1. Load the CSV dataset using Pandas.
2. Explore the dataset and view descriptive statistics.
3. Clean the data by removing missing values and duplicate rows.
4. Calculate each student's average score across the three subjects.
5. Categorize students into Poor, Average, Good, and Excellent performance groups.
6. Analyze subject scores and compare average performance across gender, test preparation course, lunch type, and parental education.
7. Calculate covariance and correlation between subject scores.
8. Perform an independent two-sample t-test to compare Maths scores of students who completed test preparation with those who did not.

## Visualizations
The notebook creates:
- Bar charts for subject averages and group comparisons
- A line graph of average marks by subject
- A pie chart of performance categories
- A histogram of average marks
- A box plot comparing subject scores
- A scatter plot of Reading and Writing scores
- A heatmap showing correlations between subject scores

## Hypothesis Test
- **Null hypothesis (H0):** There is no significant difference in Maths scores between students who completed the test preparation course and students who did not.
- **Alternative hypothesis (H1):** There is a significant difference in Maths scores between the two groups.
- **Significance level:** 0.05
- **Test used:** Independent two-sample t-test

The notebook reports the t-statistic and p-value and uses the p-value to decide whether to reject the null hypothesis.

## Repository Files
- `Student_Performance.ipynb` – Jupyter Notebook containing the Python analysis.
- `StudentsPerformance.csv` – Dataset used in the analysis.

## How to Run
1. Download or clone this repository.
2. Make sure Python and Jupyter Notebook are installed.
3. Install the required libraries:
   ```bash
   pip install pandas numpy matplotlib seaborn scipy
   ```
4. Open `Student_Performance.ipynb` in Jupyter Notebook.
5. Keep `StudentsPerformance.csv` in the same folder as the notebook.
6. Run the notebook cells in order.

## Author
**Radhika Ghantasala**  
B.Tech – Computer Science and Engineering  
Registration No.: 12409908

## Course
**INT375 – Data Science Toolbox: Python Programming**

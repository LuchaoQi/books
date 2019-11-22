# Feature Engineering Made Easy

## Chapter 2

```python
# load in the data set
# https://data.sfgov.org/City-Management-and-Ethics/Salary-Ranges-by-Job-Classification/7h4w-reyq
salary_ranges = pd.read_csv('../data/Salary_Ranges_by_Job_Classification.csv')

# view the first few rows and the headers
salary_ranges.head()
# get a sense
salary_ranges.info()

salary_ranges.isnull().sum()
# distribution
salary_ranges.describe()

```




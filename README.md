# pandas-challenge

Background
--------
A school district needs to analyze the district-wide standardized test results. The dataset includes every student's math and reading scores, as well as various information on the schools they attend. Aggregate the data to showcase obvious trends in school performance.

## Objective ##

#### District Summary ####
A high-level snapshot of the district's key metrics in a DataFrame, which includes:
* Total number of unique schools

* Total students

* Total budget

* Average math score

* Average reading score

* % passing math (the percentage of students who passed math)

* % passing reading (the percentage of students who passed reading)

* % overall passing (the percentage of students who passed math AND reading)

#### School Summary ####
A dataframe that highlights key metrics about each school, which include:

* School name

* School type

* Total students

* Total school budget

* Per student budget

* Average math score

* Average reading score

* % passing math (the percentage of students who passed math)

* % passing reading (the percentage of students who passed reading)

* % overall passing (the percentage of students who passed math AND reading)

The following dataframes are created after the district and school summaries:
* Highest-Performing Schools (by % Overall Passing)
* Lowest-Performing Schools (by % Overall Passing)
* Average Math Scores by Grade
  * A DataFrame that lists the average math score for students of each grade level (9th, 10th, 11th, 12th) at each school.
* Average Reading Scores by Grade
  * A DataFrame that lists the average reading score for students of each grade level (9th, 10th, 11th, 12th) at each school.
* Scores by School Spending
  * A table that breaks down school performance based on average spending ranges (per student).
* A spending summary that groups by spending ranges per student for each of the following categories
  * Average math score
  * Average reading score
  * % passing math (the percentage of students who passed math)
  * % passing reading (the percentage of students who passed reading)
  * % overall passing (the percentage of students who passed math AND reading)
* Scores by School Size
* Scores by School Type

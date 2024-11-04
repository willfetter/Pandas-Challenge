# Pandas-Challenge
Module 4 Pandas Challenge by William Fetter

Objectives: To create and manipulate Pandas DataFrames to analyze school and standardized test data.

            You are the new Chief Data Scientist for your city's school district. In this capacity, you'll be helping the school board and mayor make strategic     
            decisions regarding future school budgets and priorities.

            As a first task, you've been asked to analyze the district-wide standardized test results. You'll be given access to every student's math and reading     
            scores, as well as various information on the schools they attend. Your task is to aggregate the data to showcase obvious trends in school performance.

            Using Pandas and Jupyter Notebook, create a report that includes the following data. Your report must include a written description of at least two
            observable trends based on the data.
            
Inputs:
   - 'PyCitySchools_starter.ipnb' as starter file for format and sample solution
   - 'Resources/schools_complete.csv' for background data
   - 'Resources/students.csv' for background data

Outputs: 
  Perform the necessary calculations and then create a high-level snapshot of the district's key metrics in a DataFrame, including:
      - Total number of unique schools
      - Total students
      - Total budget
      - Average math score
      - Average reading score
      - % passing math (the percentage of students who passed math)
      - % passing reading (the percentage of students who passed reading)
      - % overall passing (the percentage of students who passed math AND reading)

  Perform the necessary calculations and then create a DataFrame that summarizes key metrics about each school, including:
      - School name
      - School type
      - Total students
      - Total school budget
      - Per student budget
      - Average math score
      - Average reading score
      - % passing math (the percentage of students who passed math)
      - % passing reading (the percentage of students who passed reading)
      - % overall passing (the percentage of students who passed math AND reading)

  Sort the schools by % Overall Passing in descending order and display the top 5 rows.
  Save the results in a DataFrame called "top_schools".

  Sort the schools by % Overall Passing in ascending order and display the top 5 rows.
  Save the results in a DataFrame called "bottom_schools".

  Perform the necessary calculations to create a DataFrame that lists the average math score for students of each grade level (9th, 10th, 11th, 12th) at each
  school.

  Create a DataFrame that lists the average reading score for students of each grade level (9th, 10th, 11th, 12th) at each school.

  Create a table that breaks down school performance based on average spending ranges (per student). Use the code provided to create four bins with reasonable
  cutoff values to group school spending. Use pd.cut to categorize spending based on the bins. Use the provided code to then calculate mean scores per spending
  range. Use the scores to create a DataFrame called 'spending_summary', and include the following metrics in the table:
      - Average math score
      - Average reading score
      - % passing math (the percentage of students who passed math)
      - % passing reading (the percentage of students who passed reading)
      - % overall passing (the percentage of students who passed math AND reading)

  Use the provided code to create three bins with reasonable cutoff values to group school size. Use pd.cut to categorize school size based on the bins.
  Use the  provided code to then calculate mean scores per size range. Create a DataFrame called size_summary that breaks down school performance based on school
  size (small, medium, or large).
       
  Use the per_school_summary DataFrame to create a new DataFrame called type_summary. This new DataFrame should show school performance based on the "School Type".
  
Resources: 
   - Class information and videos - for basics of coding and building foundation
   - Stack overflow - for trouble shooting, and researching best code practices

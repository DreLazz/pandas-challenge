# pandas-challenge

# In this challenge I was tasked with analyzing the districts test results. This was done in the following workflow:

# District Summary 

# Perform the necessary calculations and then create a high-level snapshot of the district's key metrics in a DataFrame.
# Include the following:

# Total number of unique schools
# Total students
# Total budget
# Average math score
# Average reading score
# % passing math (the percentage of students who passed math)
# % passing reading (the percentage of students who passed reading)
# % overall passing (the percentage of students who passed math AND reading)

# School Summary

# Perform the necessary calculations and then create a DataFrame that summarizes key metrics about each school.
# Include the following:

# School name
# School type
# Total students
# Total school budget
# Per student budget
# Average math score
# Average reading score
# % passing math (the percentage of students who passed math)
# % passing reading (the percentage of students who passed reading)
# % overall passing (the percentage of students who passed math AND reading)

# Methods Used:

# Python
# Pandas
# Jupyter Notebook
# Groupby
# pd.cut

# Notes
# students_passing_reading = school_data_complete[(school_data_complete["reading_score"] >= 70)]
# school_students_passing_reading = students_passing_reading.groupby(["school_name"]).size()
# These two lines of code were given to me to help fix an error I had. I received help from sdludla on AskBCS Learning Assistants
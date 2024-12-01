# This is the ReadMe file for my github repository: pythonsessions 
 - each week has its own folder containing the the weekly notebook 
 - there is an own branch for every weekly exercise


# Week 1: 
  The Homework execises can be found at the end of the session_1.ipynb file
  ## Strcuture:

# Week 2:
  The Homework execises can be found at the end of the session_2.ipynb file
  ## Strcuture:
  
# Week 3:
  The Homework execises can be found at the end of the session_3.ipynb file
  ## Structure:
    - The file first contains some examples regarding Object Orientiated Programming (OOP) which was disussed during the lecture.
    - In the second half of the file, there are some Hands on Excercises and Homework which ount as the weekly exercises for our Python course.
    - The following excersices regading OOP were done as homework:
    1. Create a Course class, where each course has a name, a description and a list of enrolled students. You'll need to implement the next methods:
          Add a student to the course.
          Remove a student from the course.
          Show all students in the course.
    2. Create a Student class, where each student has a name, ID number, address and a list of enrolled courses with the following methods:
          Enroll in a course.
          Drop a course.
          Show all registered student courses.
    3. Create a central class that manages courses and students, Registration class, where you have a list of students and a list of courses, and methods:
          Enroll in a course.
          Drop a course.
          Show all the enrolled courses.
          Show all the students.
    4. Let's add grades to each student's course and create method that yields the GPA given a student name or ID.

 # Week 4:
 The Homework execises can be found at the end of the session_4.ipynb file
  ## Strcuture:
    - Given a zip file with a subfolder with multiple annotations, where the name convention for each one of them is:
      {DATE}{TIME}_SN{SATELLITE_NUMBER}_QUICKVIEW_VISUAL{VERSION}_{UNIQUE_REGION}.txt
    - where:
        DATE expressed as YYYYMMDD (year, month and day), e.g. 20241201, 20230321 ...
        TIME expressed as HHMMSS (hour, minutes and seconds), e.g. 2134307
        SATELLITE_NUMBER an integer that represents the satellite number.
        VERSION provides the version of the pipeline, e.g. "0_1_2", "1_3_1" ...
        UNIQUE_REGION provides a unique location in the form of a string, e.g SATL-2KM-10N_552_4164
        Find out the following thing about your data:

        How many files the annotations folder has.
        How many of them follow the name convention expressed above.
        How many of annotations you have per month and year. Which month has more annotation files.
        Create a new annotations folder with multiple folders corresponding to a month.
        Print all the annotations from the most recent to the oldest one.
        How many different satellites there are, how many annotations we have per satellite number, and which one was used in the most recent annotation file.
        How many unique regions there are.
        some tips:

        str class has a method called split, you can use it to get each field per annotation.
        you can use sort from numpy on strings.

 # Week 5:
  The Homework execises can be found at the end of the session_5.ipynb file
  ## Strcuture:
      Reusing the same annotations we work with in the previous session, answer the following items using the libraries we saw today: 
      - How many annotations you have per month and year. Which month has more annotation files.
      - Create a dictionary where each **key** is a month, and the corresponding **value** is a list containing all the annotation names with where their date corresponds to the month. 
      - Print all the annotations from the oldest ones to the newest one during the seconf half of the 2024. 

 # Week 6:
  The Homework execises can be found at the end of the session_6.ipynb file
  ## Strcuture:
    Home exercises for Netflix:
  1. Is there any missing rating?
  2. How many films in 2021 correspond to your country?
  3. What's the number of movies in 2020 with full information?
  4. Give me the year with more titles,
  5. and what has been the average in terms of releases from 2010. 
  And for Titanic:
  1. Calculate Gender-Based Survival Percentage
  2. Calculate Survival Percentage Grouped by Gender and Class

  # Week 7:
  The Homework execises can be found at the end of the session_7.ipynb file
  ## Strcuture:
   1. Create a new column called **professor_initials** that stores the initials of each professor's first and last names. Use the following data:
   2. Given the dataframe below. Use **join** to combine this new DataFrame with the original one based on the professor column.
   3. Combine the original df and df_courses DataFrames.
   4. In the professor column, create a new column professor_last_name by extracting the last name of each professor using string operations.
   
  # Week 8:
  ## Strcuture:
  The Homework execises can be found at the end of the session_8(1).ipynb file
  1. Create a *lineplot* showing how **Study Time** varies by **Student Name**. Which student has the highest study time?
  2. Plot a histogram (*histplot*) of **Grade** and determine which grade range has the highest frequency of students.
  3. Create an ECDF plot (*ecdfplot*) for **Grade**. What is the percentage of students scoring less than 85?
  4. Create a *stripplot* showing **Grade** distribution for each **Course**. Which course has the most spread in grades?
  5. Create a *swarmplot* to show the relationship between Gender and **Study Time**. Which gender has a higher average study time?
  6. Plot a *pointplot* to show the average **Grade** for each Course. Which course has the highest average grade?

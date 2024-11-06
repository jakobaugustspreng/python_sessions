# This is the ReadMe file for my github repository: pythonsessions 
 - each week has its own folder
 - each folder contains the weekly exercises for that week and a Readme file with more information regardings its structure etc. 
 - there is an own branch for every weekly exercise


# Week 1: 
  Python_Excerise_1.ipynb
  ## Strcuture:

# Week 2:
  PythonExcercise2.ipynb
  ## Strcuture:
  
# Week 3:
  session_3_exercises.ipynb
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
    The file for the exercises can be found in the Folder: Session 5 with the file name: session_5.ipynb
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
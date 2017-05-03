## Week 6 Quiz Questions and Answers

In order to prepare your Week 6 Quiz submission, please edit ***this*** document to provide substantive questions for each Quiz Problem and SAS Recipe listed below, as well as answers to at least three questions raised.

All edits should conform to GitHub Markdown specifications (https://guides.github.com/features/mastering-markdown/) and should be committed to a branch named "week-6" in your fork of this repo. Then, after all edits have been made/committed, your Week 6 Quiz should be submitted by initiating a pull request using

- the master branch of the stat6250/course_questions_wiki repo as the base fork and

- the week-6 branch of your version of the repo as the head fork.

The instructor will then review the pull request and make comments should further revision be needed. Then, after the contents of the pull request have been finalized without any merge conflicts, the instructor will merge the pull request.

********************************************************************************



[Course Textbook Chapter 12, Problem 1]
-Question (nly13-stat6250): If the 2 data sets have unequal number of rows, what will happen during the merge?
-Answer (nly13-stat6250): In the last row of observations, the SET statement will read in the observation in the first set, but will stop when there is nothing to read in from the second set. This observation will not be in the output.


[Course Textbook Chapter 12, Problem 2]
-Question (nly13-stat6250): How does the BY statement affect a one to one merge?
–Answer (nly13-stat6250): The BY statement will sort the order of the merged data set by the specified variable.


[Course Textbook Chapter 12, Problem 3]
-Question (nly13-stat6250): During concatenate, what will happen if the variable names are not the same?
-Answer (nly13-stat6250): If the variable names are not the same, it will generate a new column for each dataset.


[Course Textbook Chapter 12, Problem 4]
-Question (nly13-stat6250): If merging datasets with unequal observations, is there a benefit to not having the missing observations?


[Course Textbook Chapter 12, Problem 5]
-Question (nly13-stat6250): Is it recommended to always use the RENAME statement in order to prevent overwriting a variable? 


[Course Textbook Chapter 12, Problem 7]
-Question (nly13-stat6250): In what order to do rename statement activate in different parts of the data step.


[Course Textbook Chapter 12, Problem 9]
-Question (nly13-stat6250): Is it more efficient to use PROC SQL or DATA step to merge?


[basic_recipe_for_combining_data_horizontally (from Week 6 Overview)]
-Question (nly13-stat6250): Besides not being limited my size, are there any other advantages to using merge instead of sql?


## Week 6 Quiz Questions and Answers

In order to prepare your Week 6 Quiz submission, please edit ***this*** document to provide substantive questions for each Quiz Problem and SAS Recipe listed below, as well as answers to at least three questions raised.

All edits should conform to GitHub Markdown specifications (https://guides.github.com/features/mastering-markdown/) and should be committed to a branch named "week-6" in your fork of this repo. Then, after all edits have been made/committed, your Week 6 Quiz should be submitted by initiating a pull request using

- the master branch of the stat6250/course_questions_wiki repo as the base fork and

- the week-6 branch of your version of the repo as the head fork.

The instructor will then review the pull request and make comments should further revision be needed. Then, after the contents of the pull request have been finalized without any merge conflicts, the instructor will merge the pull request.

********************************************************************************



[Course Textbook Chapter 12, Problem 1]
- Question (akumar30−stat6250): Is the order of the smallest dataset significance in one-to-one merge SET data statement? 	



[Course Textbook Chapter 12, Problem 2]
- Question (akumar30−stat6250): How to append two dataset, when common variable has different type of data?
- Answer (akumar30−stat6250):  If the type of a variable in the DATA= data set is different than in the BASE= data set, SAS replaces all values for the variable in the DATA= data set with missing values and keeps the variable type of the variable specified in the BASE= data set



[Course Textbook Chapter 12, Problem 3]
- Question (akumar30−stat6250): What happen when if the type of common variable differ in the datasets to be concatenated?
- Answer (akumar30−stat6250):  SAS will stops process the DATA step and issues an error message stating that the variables are incompatible.



[Course Textbook Chapter 12, Problem 4]
- Question (akumar30−stat6250):  Can we concatenate more than two data set in SAS using single SAS concatenate procedure?



[Course Textbook Chapter 12, Problem 5]
- Question (akumar30−stat6250): Can we merge the two datasets with multiple common variables in single SAS Procedure by specifying multiple variable names in BY statement?



[Course Textbook Chapter 12, Problem 7]
- Question (akumar30−stat6250): How do you prevent the values of the common variable Blue from being overwritten when you merge the two data sets?
- Answer (akumar30−stat6250):  Using RENAME procedure, we can change the name of common variables to sustain its original value from both dataset and prevent overwriting,



[Course Textbook Chapter 12, Problem 9]
- Question (akumar30−stat6250): Can I get the result of one-to-one merge using PROC SQL command?


[basic_recipe_for_combining_data_horizontally (from Week 6 Overview)]
- Question (akumar30−stat6250):  Does rename option in merge statement modify the name of actual dataset or only valid for merge statement?

[optional: adv_recipe_for_combining_data_horizontally (from Week 6 Overview)]
- Question (akumar30−stat6250): Wwhich statement will have faster performance combine four dataset, using merge statement or pro sql statement?

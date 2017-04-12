## Week 3 Quiz Questions and Answers

In order to prepare your Week 3 Quiz submission, please edit ***this*** document to provide substantive questions for each Quiz Problem and SAS Recipe listed below, as well as answers to at least three questions raised.

All edits should conform to GitHub Markdown specifications (https://guides.github.com/features/mastering-markdown/) and should be committed to a branch named "week-3" in your fork of this repo. Then, after all edits have been made/committed, your Week 3 Quiz should be submitted by initiating a pull request using

- the master branch of the stat6250/course_questions_wiki repo as the base fork and

- the week-3 branch of your version of the repo as the head fork.

The instructor will then review the pull request and make comments should further revision be needed. Then, after the contents of the pull request have been finalized without any merge conflicts, the instructor will merge the pull request.

********************************************************************************

[Course Textbook Chapter 3, Problem 1]
- Question (akumar30−stat6250): Is it necessary to include a RUN statement after every DATA step or PROC step?


[Course Textbook Chapter 3, Problem 2]
- Question (akumar30−stat6250): Can we get a syntax error if data file name is same as SAS Procedure?


[Course Textbook Chapter 3, Problem 3]
- Question (akumar30−stat6250):  How to interpret the error based on log?


[Course Textbook Chapter 3, Problem 4]
- Question (akumar30−stat6250):  What is the use of RECALL command when syntax error occurs? 
- Answer (akumar30−stat6250): It is used to recall the submitted statements from the recall buffer to the Program Editor window, where you can correct the problems.



[Course Textbook Chapter 3, Problem 5]
- Question (akumar30−stat6250): What happens when program statements are not conformed to the rules of the SAS language?
- Answer (akumar30−stat6250):  A syntax error will occur. Details of syntax error can be found in log message.


[Course Textbook Chapter 3, Problem 6]
- Question (akumar30−stat6250):  What happens when SAS statement that contains an invalid option is submitted? Why this happen?
- Answer (akumar30−stat6250): A message will appears in the Log window indicating that the option is not valid or not recognized. An invalid option error occurs when you specify an option that is not valid in a particular statement.


[Course Textbook Chapter 3, Problem 7]
- Question (akumar30−stat6250):  Can SAS automatically fix misspelled words in SAS Statement?
- Answer (akumar30−stat6250):  No, You need to fix the program by interpreting the error in log message.


[Course Textbook Chapter 3, Problem 10]
- Question (akumar30−stat6250): Can Data Step debugger will be used in other than interactive mode?
- Answer (akumar30−stat6250): No.


[Course Textbook Chapter 4, Problem 1]
- Question (akumar30−stat6250):  What will be happen if a variable in the ID statement also appears in the VAR statement?
- Answer (akumar30−stat6250): The output will contains two columns for that variable.


[Course Textbook Chapter 4, Problem 3]
- Question (akumar30−stat6250): What will happen if value of number variable (fee) will be queried as below?
where fee in (‘124’,’178’);    
- Answer (akumar30−stat6250): 


[Course Textbook Chapter 4, Problem 4]
- Question (akumar30−stat6250):  Can sort statement in SAS generated the printed output?
- Answer (akumar30−stat6250): No, additional steps will be required to show the printed output.


[Course Textbook Chapter 4, Problem 7]
- Question (akumar30−stat6250): What will happen if no option define for OUT while sorting the dataset in SAS? 
- Answer (akumar30−stat6250):  The PROC SORT step permanently sorts the input data set.


[Course Textbook Chapter 4, Problem 9]
- Question (akumar30−stat6250):  Can we do grouping and sorting of variable in SAS together?


[Course Textbook Chapter 4, Problem 10]
- Question (akumar30−stat6250):   Can we change the default properties of PROC PRINT?


[recipe_to_check_for_duplicates (from Week 3 Overview)]
- Question (akumar30−stat6250): Can we compare two identical datasets and find the matching records and mismatched records using duplicate data scripts?


[recipe_for_sorting_data (from Week 3 Overview)]
- Question (akumar30−stat6250): Can indexing inside dataset will help for faster sorting results?
- Answer (akumar30−stat6250): An index doesn’t guarantee that query performance will be improve.


[recipe_for_printing_values (from Week 3 Overview)]
- Question (akumar30−stat6250): Can we directly update the value of a column inside dataset in explorer mode?


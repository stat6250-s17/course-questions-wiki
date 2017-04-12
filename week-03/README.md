## Week 3 Quiz Questions and Answers

In order to prepare your Week 3 Quiz submission, please edit ***this*** document to provide substantive questions for each Quiz Problem and SAS Recipe listed below, as well as answers to at least three questions raised.

All edits should conform to GitHub Markdown specifications (https://guides.github.com/features/mastering-markdown/) and should be committed to a branch named "week-3" in your fork of this repo. Then, after all edits have been made/committed, your Week 3 Quiz should be submitted by initiating a pull request using

- the master branch of the stat6250/course_questions_wiki repo as the base fork and

- the week-3 branch of your version of the repo as the head fork.

The instructor will then review the pull request and make comments should further revision be needed. Then, after the contents of the pull request have been finalized without any merge conflicts, the instructor will merge the pull request.

********************************************************************************


[Course Textbook Chapter 3, Problem 1]
- Question (yyan11−stat6250): How to write SAS statements?
- Answer (yyan11−stat6250): Although you can write SAS statements in almost any format, a consistent layout enhances readability and helps you understand the program’s purpose. It's a good idea to begin DATA and PROC steps in column one, indent statements within a step, begin RUN statements in column one, include a RUN statement after every DATA step or PROC step. 




[Course Textbook Chapter 3, Problem 2]
- Question (yyan11−stat6250): How to correct the error?
- Answer (yyan11−stat6250): To correct the error: 1. Remove or replace the invalid option, and check your statement syntax as needed. 2. Resubmit the corrected program. 3. Check the SAS log again to make sure there are no other errors. 




[Course Textbook Chapter 3, Problem 3]
- Question (yyan11−stat6250): What are syntax errors?
- Answer (yyan11−stat6250): Syntax errors, such as misspelled words, generally cause SAS to stop processing the step in which the error occurred.



[Course Textbook Chapter 3, Problem 4]
- Question (yyan11−stat6250): What happened when an error is submitted?
- Answer (yyan11−stat6250):  When a program that contains an error is submitted, messages regarding the problem also appear in the SAS log. When a syntax error is detected, the SAS log displays the word ERROR, identifies the possible location of the error, and gives an explanation of the error.



[Course Textbook Chapter 3, Problem 5]
- Question (yyan11−stat6250): What can help me identify syntax errors?
- Answer (yyan11−stat6250): Some SAS system options, features of the Editor window, and the DATA step debugger can help you identify syntax errors. Other types of errors include data errors, semantic errors, and execution-time errors.



[Course Textbook Chapter 3, Problem 6]
- Question (yyan11−stat6250): What should I do when the statement contains an invalid option?
- Answer (yyan11−stat6250): When you submit a SAS statement that contains an invalid option, a log message notifies you that the option is not valid or not recognized. You should recall the program, remove or replace the invalid option, check your statement syntax as needed, and resubmit the corrected program.



[Course Textbook Chapter 3, Problem 7]
- Question (yyan11−stat6250): What happened when the data step contains a misspelled keyword?
- Answer (yyan11−stat6250): This is such a common (and easily interpretable) error that SAS produces only a warning message, not an error.



[Course Textbook Chapter 3, Problem 10]
- Question (yyan11−stat6250): What are data errors?
- Answer (yyan11−stat6250): Data errors that occur when some data values are not appropriate for the SAS statements that are specified in a program.



[Course Textbook Chapter 4, Problem 1]
- Question (yyan11−stat6250): What is the WHERE statement?
- Answer (yyan11−stat6250): In the WHERE statement you can specify any variable in the SAS data set, not just the variables that are specified in the VAR statement. The WHERE statement works for both character and numeric variables.



[Course Textbook Chapter 4, Problem 3]
- Question (yyan11−stat6250): How to write the IN operator in the WHERE statement?
- Answer (yyan11−stat6250): In the WHERE statement, the IN operator enables you to select observations based on several values. You specify values in parentheses and separate them by spaces or commas. Character values must be enclosed in quotation marks and must be in the same case as in the data set.



[Course Textbook Chapter 4, Problem 4]
- Question (yyan11−stat6250): What should I do if I do not want my original data to be sorted?
- Answer (yyan11−stat6250): If you do not want your original data to be sorted permanently, you must create an output data set that contains the data in sorted order. The OUT= option in the PROC SORT statement specifies an output data set. 



[Course Textbook Chapter 4, Problem 7]
- Question (yyan11−stat6250): What can I do when I want to subtotal numeric variables?
- Answer (yyan11−stat6250): To produce subtotals, add both a SUM statement and a BY statement to your PROC PRINT step.



[Course Textbook Chapter 4, Problem 9]
- Question (yyan11−stat6250): Which operator could link sequence of expressions into compound expressions?
- Answer (yyan11−stat6250): To link a sequence of expressions into compound expressions, you use logical operators, including AND or &, OR or |.



[Course Textbook Chapter 4, Problem 10]
- Question (yyan11−stat6250): What does a PROC PRINT step list by default?
- Answer (yyan11−stat6250): By default, a PROC PRINT step lists all the observations in a data set. 



[recipe_to_check_for_duplicates (from Week 3 Overview)]
- Question (yyan11−stat6250): Does every data in a SAS dataset have a duplicate?



[recipe_for_sorting_data (from Week 3 Overview)]
- Question (yyan11−stat6250): What would happen if I do not write anything before “out=”?


[recipe_for_printing_values (from Week 3 Overview)]
- Question (yyan11−stat6250): How to copy SAS data to the system clipboard?



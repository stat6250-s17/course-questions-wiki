## Week 7 Quiz Questions and Answers

In order to prepare your Week 7 Quiz submission, please edit ***this*** document to provide substantive questions for each Quiz Problem and SAS Recipe listed below, as well as answers to at least three questions raised.

All edits should conform to GitHub Markdown specifications (https://guides.github.com/features/mastering-markdown/) and should be committed to a branch named "week-7" in your fork of this repo. Then, after all edits have been made/committed, your Week 7 Quiz should be submitted by initiating a pull request using

- the master branch of the stat6250/course_questions_wiki repo as the base fork and

- the week-7 branch of your version of the repo as the head fork.

The instructor will then review the pull request and make comments should further revision be needed. Then, after the contents of the pull request have been finalized without any merge conflicts, the instructor will merge the pull request.

********************************************************************************



[Course Textbook Chapter 10, Problem 2]
- Question (yyan11−stat6250): How to permanently assign labels and formats to variables?
- Answer (yyan11−stat6250): To permanently assign labels and formats, you use LABEL and FORMAT statements in DATA steps.



[Course Textbook Chapter 10, Problem 6]
- Question (yyan11−stat6250): What logical operators can I use when writing IF-THEN statements?
- Answer (yyan11−stat6250): Use the AND operator to execute the THEN statement if both expressions that are linked by AND are true. Use the OR operator to execute the THEN statement if either expression that is linked by OR is true. Use the NOT operator with other operators to reverse the logic of a comparison.



[Course Textbook Chapter 10, Problem 7]
- Question (yyan11−stat6250): What is a LENGTH statement？
- Answer (yyan11−stat6250): Within your program, you include a LENGTH statement to assign a length to accommodate the longest value of the variable TestLength. The longest value is Normal, which has six characters. Because TestLength is a character variable, you must follow the variable name with a dollar sign ($).



[Course Textbook Chapter 10, Problem 8]
- Question (yyan11−stat6250): When can I use the LENGTH statement?
- Answer (yyan11−stat6250): Instead of using a series of IF-THEN statements, you can use the ELSE statement to specify an alternative action to be performed when the condition in an IF-THEN statement is false. 



[Course Textbook Chapter 10, Problem 9]
- Question (yyan11−stat6250): How to determine the Length of a new variable？
- Answer (yyan11−stat6250): You can use a LENGTH statement to specify a length（the number of bytes）for TestLength before the first value is referenced elsewhere in the DATA step.



[Course Textbook Chapter 10, Problem 10]
- Question (yyan11−stat6250): How to selecting Variables that you don't want to keep in your data set？
- Answer (yyan11−stat6250): You can use the DROP= and KEEP= data set options to specify the variables that you want to drop or keep. Use the KEEP= option instead of the DROP= option if more variables are dropped than kept. You specify data set options in parentheses after a SAS data set name.



[Course Textbook Chapter 11, Problem 1]
- Question (yyan11−stat6250): Where to Specify the DROP= and KEEP= Data Set Options?
- Answer (yyan11−stat6250): You've learned that you can specify the DROP= and KEEP= data set options anywhere you name a SAS data set. 



[Course Textbook Chapter 11, Problem 2]
- Question (yyan11−stat6250): How to use the variable to select observations？
- Answer (yyan11−stat6250): If you do need to reference a variable in the original data set (in a subsetting IF statement, for example), you can specify the variable in the DROP= or KEEP= option in the DATA statement. Otherwise, the statement that references the variable uses a missing value for that variable.



[Course Textbook Chapter 11, Problem 3]
- Question (yyan11−stat6250): How to detecting the End of a Data Set？
- Answer (yyan11−stat6250): Instead of reading specific observations, you might want to determine when the last observation in an input data set has been read, so that you can perform specific processing. For example, you might want to output only one observation that contains grand totals for numeric variables.



[Course Textbook Chapter 11, Problem 8]
- Question (yyan11−stat6250): How to create a temporary numeric variable whose value is used to detect the last observation?
- Answer (yyan11−stat6250): You can use the END= option in the SET statement where variable creates and names a temporary variable that contains an end-of-file marker. The variable, which is initialized to 0, is set to 1 when the SET statement reads the last observation of the data set. This variable is not added to the data set. 



[Course Textbook Chapter 11, Problem 9]
- Question (yyan11−stat6250): Is there any observation at the bottom of the DATA step?
- Answer (yyan11−stat6250): At the bottom of the DATA step, the compilation phase is complete, and the descriptor portion of the new SAS data set is created. There are no observations because the DATA step has not yet executed.
When the compilation phase is complete, the execution phase begins.




[basic_recipe_for_combining_data_vertically(from Week 7 Overview)]
- Question (yyan11−stat6250): If datasets has more than two with the same column structure. Is it still combined vertically？



[optional: adv_recipe_for_combining_data_vertically (from Week 7 Overview)]
- Question (yyan11−stat6250): Which three substitutes can be used to combine dataset?



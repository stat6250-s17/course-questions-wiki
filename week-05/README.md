## Week 5 Quiz Questions and Answers

In order to prepare your Week 5 Quiz submission, please edit ***this*** document to provide substantive questions for each Quiz Problem and SAS Recipe listed below, as well as answers to at least three questions raised.

All edits should conform to GitHub Markdown specifications (https://guides.github.com/features/mastering-markdown/) and should be committed to a branch named "week-5" in your fork of this repo. Then, after all edits have been made/committed, your Week 5 Quiz should be submitted by initiating a pull request using

- the master branch of the stat6250/course_questions_wiki repo as the base fork and

- the week-5 branch of your version of the repo as the head fork.

The instructor will then review the pull request and make comments should further revision be needed. Then, after the contents of the pull request have been finalized without any merge conflicts, the instructor will merge the pull request.

********************************************************************************



[Course Textbook Chapter 5, Problem 1]
- Question (akumar30−stat6250): What is the significance of aggregate storage location in SAS?
* *Question (aalshehry−stat6250):* What is the general form of using FILENAME statement?
* *Answer (aalshehry−stat6250):* FILENAME fileref 'filename';



[Course Textbook Chapter 5, Problem 2]
- Question (akumar30−stat6250):  Can I reference multiple external file with a fileref that points to an aggregate storage location?
- Answer (akumar30−stat6250):  Yes, The * and ? wildcards can be used in either the external file name. Wildcards are supported for input only in the FILENAME and INFILE statements, and in member name syntax (aggregate syntax). Also allfiles command can be used to reads all files in the current working directory.
* *Question (aalshehry−stat6250):* Why does Fileref statement lose its information after ending SAS session?



[Course Textbook Chapter 5, Problem 6]
- Question (akumar30−stat6250): Can I assign a static text or conditional text (e.g.  Yes or No) to a variable in input statement?  	    
- Answer (akumar30−stat6250):  Yes, using SAS expression new variable can be created to calculate measures or display value based on certain conditions.
* *Question (aalshehry−stat6250):* In INPUT statement, what do the numbers after the variables represent? 
* *Answer (aalshehry−stat6250):* INPUT variable <$> startcol-endcol . . .; The dollar sign ($) identifies the variable type as character (if the variable is numeric, then nothing appears here), startcol represents the starting column for this variable, and endcol represents the ending column for this variable.



[Course Textbook Chapter 5, Problem 7]
- Question (akumar30−stat6250): Can we changed the order of existing raw dataset file permanently using SAS?
* *Question (aalshehry−stat6250):* What information should be provided to use INPUT statement?



[Course Textbook Chapter 5, Problem 8]
- Question (akumar30−stat6250): How to delete a column in SAS output?
- Answer (akumar30−stat6250):  Use DROP in the data option to delete a column in the SAS output.
* *Question (aalshehry−stat6250):* When you re-define the value of a variable, can you restore the orginal values?



[Course Textbook Chapter 6, Problem 1]
- Question (akumar30−stat6250): Can we increase the default size of output buffer in SAS?
- Answer (akumar30−stat6250):  Yes using BUFSIZE option we can specifies the size of a permanent buffer page for an output SAS data set.
* *Question (aalshehry−stat6250):* After the compilation phase is completed, what SAS compiler will create next?
* *Answer (aalshehry−stat6250):* The descriptor portion of the new data set will be created.



[Course Textbook Chapter 6, Problem 2]
- Question (akumar30−stat6250): How to detect and fix semantic error in SAS?
- Answer (akumar30−stat6250):  All error details can be found in log windows, using error description you can analyze the error and correct the code.
* *Question (aalshehry−stat6250):* What type of syntax errors does SAS can recognize? 



[Course Textbook Chapter 6, Problem 3]
- Question (akumar30−stat6250): Which command can be used in data step to execute multiple time for each record in the input file?
* *Question (aalshehry−stat6250):* How to change/redirect the defult Data statem?



[Course Textbook Chapter 6, Problem 4]
- Question (akumar30−stat6250): Can we change the default value of _N_ and _ERROR_ at the beginning of the execution phase?
* *Question (aalshehry−stat6250):* What is the function of _N_ and _ERROR_?



[Course Textbook Chapter 6, Problem 5]
- Question (akumar30−stat6250):  Can we find the number of errors in execution step by analyzing the value of _ERROR_ in SAS?
* *Question (aalshehry−stat6250):* What values can _ERROR_ takes?



[Course Textbook Chapter 6, Problem 6]
- Question (akumar30−stat6250): if there are independent SAS code, can we change the SAS execution processing from sequential to parallel for faster processing?
* *Question (aalshehry−stat6250):* Why SAS assigns variables in the program data vector to missing before each execution of the DATA step?



[basic_recipe_for_creating_analytic_datasets (from Week 5 Overview)]
- Question (akumar30−stat6250): Can we create new dataset from existing multiple dataset in SAS data step? (without using proc sql)
* *Question (aalshehry−stat6250):* What is the difference between "Retain" and "Keep" in DATA statement?



[optional: adv_recipe_for_creating_analytic_datasets (from Week 5 Overview)]
- Question (akumar30−stat6250):  can we create new variable using proc sql statement in SAS?
- Answer (akumar30−stat6250):  Yes, using LABEL = option we can create new variable using SAS proc sql statement.
* *Question (aalshehry−stat6250):* In SQL inquery, what is the substitue of proc means and proc freq?



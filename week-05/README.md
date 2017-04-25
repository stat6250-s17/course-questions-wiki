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
- Question (yyan11−stat6250): Can I using a FILENAME Statement referencing a Raw Data File?
- Answer (yyan11−stat6250): Yes, when reading raw data, you can use the FILENAME statement to point to the location of the external file that contains the data. Just as you assign a libref by using a LIBNAME statement, you assign a fileref by using a FILENAME statement.
- Question (rluo-stat6250): What is a raw data file, and what are its features?


[Course Textbook Chapter 5, Problem 2]
- Question (akumar30−stat6250):  Can I reference multiple external file with a fileref that points to an aggregate storage location?
- Answer (akumar30−stat6250):  Yes, The * and ? wildcards can be used in either the external file name. Wildcards are supported for input only in the FILENAME and INFILE statements, and in member name syntax (aggregate syntax). Also allfiles command can be used to reads all files in the current working directory.
* *Question (aalshehry−stat6250):* Why does Fileref statement lose its information after ending SAS session?
- Question (yyan11−stat6250): How to view active filerefs?
- Answer (yyan11−stat6250): Like librefs, the filerefs currently defined for your SAS session are listed in the SAS Explorer window. To view details about a referenced file, double-click File Shortcuts (or select File Shortcuts and then Open from the pop-up menu). Then select View→Details. Information for each file (name, size, type, and host path name) is listed.
- Question (rluo-stat6250): In order to read the raw data file, what DATA steps must be provided?


[Course Textbook Chapter 5, Problem 6]
- Question (akumar30−stat6250): Can I assign a static text or conditional text (e.g.  Yes or No) to a variable in input statement?  	    
- Answer (akumar30−stat6250):  Yes, using SAS expression new variable can be created to calculate measures or display value based on certain conditions.
* *Question (aalshehry−stat6250):* In INPUT statement, what do the numbers after the variables represent? 
* *Answer (aalshehry−stat6250):* INPUT variable <$> startcol-endcol . . .; The dollar sign ($) identifies the variable type as character (if the variable is numeric, then nothing appears here), startcol represents the starting column for this variable, and endcol represents the ending column for this variable.
- Question (yyan11−stat6250): Can I use the INPUT statement to describing the data?
- Answer (yyan11−stat6250): The INPUT statement describes the fields of raw data to be read and placed into the SAS data set.
- Question (rluo-stat6250): Besides we correct the invalid data in the data file, is there other ways that can help us deal with the invalid data without modify them?


[Course Textbook Chapter 5, Problem 7]
- Question (akumar30−stat6250): Can we changed the order of existing raw dataset file permanently using SAS?
* *Question (aalshehry−stat6250):* What information should be provided to use INPUT statement?
- Question (yyan11−stat6250): How to write an INPUT statement?
- Answer (yyan11−stat6250): For each field of raw data that you want to read into your SAS data set, you must specify the following information in the INPUT statement: a valid SAS variable name; a type (character or numeric); a range (starting column and ending column).
- Question (rluo-stat6250): Does assignment statement begin with the keyword?
- Answer (rluo-stat6250): Assignment statement does not begin with the keyword.


[Course Textbook Chapter 5, Problem 8]
- Question (akumar30−stat6250): How to delete a column in SAS output?
- Answer (akumar30−stat6250):  Use DROP in the data option to delete a column in the SAS output.
* *Question (aalshehry−stat6250):* When you re-define the value of a variable, can you restore the orginal values?
- Question (yyan11−stat6250): How to evaluate the expression when a variable name appears on both sides of the equal sign?
- Answer (yyan11−stat6250): When a variable name appears on both sides of the equal sign, the original value on the right side is used to evaluate the expression. The result is assigned to the variable on the left side of the equal sign.
- Question (rluo-stat6250): Does the subsetting IF statement have iteration function?


[Course Textbook Chapter 6, Problem 1]
- Question (akumar30−stat6250): Can we increase the default size of output buffer in SAS?
- Answer (akumar30−stat6250):  Yes using BUFSIZE option we can specifies the size of a permanent buffer page for an output SAS data set.
* *Question (aalshehry−stat6250):* After the compilation phase is completed, what SAS compiler will create next?
* *Answer (aalshehry−stat6250):* The descriptor portion of the new data set will be created.
- Question (yyan11−stat6250): What are program data vectors?
- Answer (yyan11−stat6250): The program data vector contains two automatic variables that can be used for processing but which are not written to the data set as part of an observation. _N_ counts the number of times that the DATA step begins to execute. _ERROR_ signals the occurrence of an error that is caused by the data during execution. 
- Question (rluo-stat6250): What are the two phases of SAS DATA step process?
- Answer (rluo-stat6250): Compilation phase and the execution phase.


[Course Textbook Chapter 6, Problem 2]
- Question (akumar30−stat6250): How to detect and fix semantic error in SAS?
- Answer (akumar30−stat6250):  All error details can be found in log windows, using error description you can analyze the error and correct the code.
* *Question (aalshehry−stat6250):* What type of syntax errors does SAS can recognize? 
- Question (yyan11−stat6250): What is syntax checking?
- Answer (yyan11−stat6250): During the compilation phase, SAS also scans each statement in the DATA step, looking for syntax errors. 
- Question (rluo-stat6250): What are the two automatic variables the program data vector contain?


[Course Textbook Chapter 6, Problem 3]
- Question (akumar30−stat6250): Which command can be used in data step to execute multiple time for each record in the input file?
* *Question (aalshehry−stat6250):* How to change/redirect the defult Data statem?
- Question (yyan11−stat6250): How SAS Processes Programs if the DATA step compiles successfully?
- Answer (yyan11−stat6250): If the DATA step compiles successfully, then the execution phase begins. During the execution phase, the DATA step reads and processes the input data. The DATA step executes once for each record in the input file, unless otherwise directed.
- Question (rluo-stat6250): What does the descriptor portion of the data set include?


[Course Textbook Chapter 6, Problem 4]
- Question (akumar30−stat6250): Can we change the default value of _N_ and _ERROR_ at the beginning of the execution phase?
* *Question (aalshehry−stat6250):* What is the function of _N_ and _ERROR_?
- Question (yyan11−stat6250): What is initializing variables?
- Answer (yyan11−stat6250): The remaining variables are initialized to missing. Missing numeric values are represented by periods, and missing character values are represented by blanks.
- Question (rluo-stat6250): Can the execution phase only input a portion of the dataset?


[Course Textbook Chapter 6, Problem 5]
- Question (akumar30−stat6250):  Can we find the number of errors in execution step by analyzing the value of _ERROR_ in SAS?
* *Question (aalshehry−stat6250):* What values can _ERROR_ takes?
- Question (yyan11−stat6250):What is the value of the automatic variable _ERROR_ when the observation that contains any error?
- Answer (yyan11−stat6250): _ERROR_ signals the occurrence of an error that is caused by the data during execution. The default value is 0, which means there is no error. When one or more errors occur, the value is set to 1.
- Question (rluo-stat6250): How to clean the data?
- Answer (rluo-stat6250): Use IF-THEN statement or IF-THEN-ELSE statement to valid the data.

[Course Textbook Chapter 6, Problem 6]
- Question (akumar30−stat6250): if there are independent SAS code, can we change the SAS execution processing from sequential to parallel for faster processing?
* *Question (aalshehry−stat6250):* Why SAS assigns variables in the program data vector to missing before each execution of the DATA step?
- Question (yyan11−stat6250): What is the value of the automatic variable _N_?
- Answer (yyan11−stat6250): _N_ counts the number of times that the DATA step begins to execute.
- Question (rluo-stat6250): What is the function of the PUT Statement?


[basic_recipe_for_creating_analytic_datasets (from Week 5 Overview)]
- Question (akumar30−stat6250): Can we create new dataset from existing multiple dataset in SAS data step? (without using proc sql)
* *Question (aalshehry−stat6250):* What is the difference between "Retain" and "Keep" in DATA statement?
- Question (yyan11−stat6250): Is there a limit number of specific rows or columns data that will be the subset of an SAS data set?
- Question (rluo-stat6250): 


[optional: adv_recipe_for_creating_analytic_datasets (from Week 5 Overview)]
- Question (akumar30−stat6250):  can we create new variable using proc sql statement in SAS?
- Answer (akumar30−stat6250):  Yes, using LABEL = option we can create new variable using SAS proc sql statement.
* *Question (aalshehry−stat6250):* In SQL inquery, what is the substitue of proc means and proc freq?
- Question (rluo-stat6250): 


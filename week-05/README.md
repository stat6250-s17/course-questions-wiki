## Week 5 Quiz Questions and Answers

In order to prepare your Week 5 Quiz submission, please edit ***this*** document to provide substantive questions for each Quiz Problem and SAS Recipe listed below, as well as answers to at least three questions raised.

All edits should conform to GitHub Markdown specifications (https://guides.github.com/features/mastering-markdown/) and should be committed to a branch named "week-5" in your fork of this repo. Then, after all edits have been made/committed, your Week 5 Quiz should be submitted by initiating a pull request using

- the master branch of the stat6250/course_questions_wiki repo as the base fork and

- the week-5 branch of your version of the repo as the head fork.

The instructor will then review the pull request and make comments should further revision be needed. Then, after the contents of the pull request have been finalized without any merge conflicts, the instructor will merge the pull request.

********************************************************************************



[Course Textbook Chapter 5, Problem 1]
- Question (yyan11−stat6250): Can I using a FILENAME Statement referencing a Raw Data File?
- Answer (yyan11−stat6250): Yes, when reading raw data, you can use the FILENAME statement to point to the location of the external file that contains the data. Just as you assign a libref by using a LIBNAME statement, you assign a fileref by using a FILENAME statement.



[Course Textbook Chapter 5, Problem 2]
- Question (yyan11−stat6250): How to view active filerefs?
- Answer (yyan11−stat6250): Like librefs, the filerefs currently defined for your SAS session are listed in the SAS Explorer window. To view details about a referenced file, double-click File Shortcuts (or select File Shortcuts and then Open from the pop-up menu). Then select View→Details. Information for each file (name, size, type, and host path name) is listed.



[Course Textbook Chapter 5, Problem 6]
- Question (yyan11−stat6250): Can I use the INPUT statement to describing the data?
- Answer (yyan11−stat6250): The INPUT statement describes the fields of raw data to be read and placed into the SAS data set.




[Course Textbook Chapter 5, Problem 7]
- Question (yyan11−stat6250): How to write an INPUT statement?
- Answer (yyan11−stat6250): For each field of raw data that you want to read into your SAS data set, you must specify the following information in the INPUT statement: a valid SAS variable name; a type (character or numeric); a range (starting column and ending column).


[Course Textbook Chapter 5, Problem 8]
- Question (yyan11−stat6250): How to evaluate the expression when a variable name appears on both sides of the equal sign?
- Answer (yyan11−stat6250): When a variable name appears on both sides of the equal sign, the original value on the right side is used to evaluate the expression. The result is assigned to the variable on the left side of the equal sign.




[Course Textbook Chapter 6, Problem 1]
- Question (yyan11−stat6250): What are program data vectors?
- Answer (yyan11−stat6250): The program data vector contains two automatic variables that can be used for processing but which are not written to the data set as part of an observation. _N_ counts the number of times that the DATA step begins to execute. _ERROR_ signals the occurrence of an error that is caused by the data during execution. 


[Course Textbook Chapter 6, Problem 2]
- Question (yyan11−stat6250): What is syntax checking?
- Answer (yyan11−stat6250): During the compilation phase, SAS also scans each statement in the DATA step, looking for syntax errors. 



[Course Textbook Chapter 6, Problem 3]
- Question (yyan11−stat6250): How SAS Processes Programs if the DATA step compiles successfully?
- Answer (yyan11−stat6250): If the DATA step compiles successfully, then the execution phase begins. During the execution phase, the DATA step reads and processes the input data. The DATA step executes once for each record in the input file, unless otherwise directed.



[Course Textbook Chapter 6, Problem 4]
- Question (yyan11−stat6250): What is initializing variables?
- Answer (yyan11−stat6250): The remaining variables are initialized to missing. Missing numeric values are represented by periods, and missing character values are represented by blanks.



[Course Textbook Chapter 6, Problem 5]
- Question (yyan11−stat6250):What is the value of the automatic variable _ERROR_ when the observation that contains any error?
- Answer (yyan11−stat6250): _ERROR_ signals the occurrence of an error that is caused by the data during execution. The default value is 0, which means there is no error. When one or more errors occur, the value is set to 1.



[Course Textbook Chapter 6, Problem 6]
- Question (yyan11−stat6250): What is the value of the automatic variable _N_?
- Answer (yyan11−stat6250): _N_ counts the number of times that the DATA step begins to execute.



[basic_recipe_for_creating_analytic_datasets (from Week 5 Overview)]
- Question (yyan11−stat6250): Is there a limit number of specific rows or columns data that will be the subset of an SAS data set?



[optional: adv_recipe_for_creating_analytic_datasets (from Week 5 Overview)]


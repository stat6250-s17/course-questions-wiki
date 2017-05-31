## Week 10 Quiz Questions and Answers

In order to prepare your Week 10 Quiz submission, please edit ***this*** document to provide substantive questions for each Quiz Problem and SAS Recipe listed below, as well as answers to at least three questions raised.

All edits should conform to GitHub Markdown specifications (https://guides.github.com/features/mastering-markdown/) and should be committed to a branch named "week-10" in your fork of this repo. Then, after all edits have been made/committed, your Week 10 Quiz should be submitted by initiating a pull request using

- the master branch of the stat6250/course_questions_wiki repo as the base fork and

- the week-10 branch of your version of the repo as the head fork.

The instructor will then review the pull request and make comments should further revision be needed. Then, after the contents of the pull request have been finalized without any merge conflicts, the instructor will merge the pull request.

********************************************************************************


[Course Textbook Chapter 16, Problem 1]
- Question (akumar30−stat6250): Can we change the order of variables specifies in input statement?

[Course Textbook Chapter 16, Problem 5]
- Question (akumar30−stat6250): Can we read nonstandard numeric data without using informat instructions?  
- Answer (akumar30−stat6250): No, we have to use informat instructions in specified format for each type of nonstandard numeric data.


[Course Textbook Chapter 16, Problem 7]
- Question (akumar30−stat6250): Does auto cast applies if we specified the format of numeric data as character in input statement?

[Course Textbook Chapter 16, Problem 8]
- Question (akumar30−stat6250): What is the advantage of COMMAw.d informat?
- Answer (akumar30−stat6250): It is used to read numeric values and to remove embedded blanks, commas, dashes, dollar signs, percent signs and right parentheses.


[Course Textbook Chapter 16, Problem 9]
- Question (akumar30−stat6250): How to write an input statement if we don’t know the length of each base column in raw data?


[Course Textbook Chapter 17, Problem 1]
- Question (akumar30−stat6250):  What is free-format raw data in SAS?
- Answer (akumar30−stat6250): Data that is not arranged in columns or do not begin and end in the same columns is classified as free-format raw data.


[Course Textbook Chapter 17, Problem 2]
- Question (akumar30−stat6250):  Can we use list input to convert free-format raw data to columns row data?


[Course Textbook Chapter 17, Problem 4]
- Question (akumar30−stat6250): Can we change the order of columns in free-format raw data using input statement?


[Course Textbook Chapter 17, Problem 5]
- Question (akumar30−stat6250): Can we processed one raw data using input statement which are separated by different delimiters?


[Course Textbook Chapter 17, Problem 7]
- Question (akumar30−stat6250):  What is the default length of character variable in input sttatemnet?
- Answer (akumar30−stat6250): Character Variable has default length of 8.

[Course Textbook Chapter 17, Problem 8]
- Question (akumar30−stat6250): Can we change the default value of dsd from comma ‘,’ to semicolon ‘;’?
- Answer (akumar30−stat6250): Yes, using dlm=option, we can change the default value to any acceptable delimiter.


[Course Textbook Chapter 17, Problem 10]
- Question (akumar30−stat6250): Can we use dynamic length based on max length of each variable in raw data file?


[basic_recipe_to_load_remote_delimited_file (from Week 10 Overview)]
- Question (akumar30−stat6250): How proc import identifies the variable name and its data type from external file?
- Answer (akumar30−stat6250): When PROC IMPORT used to read a CSV, tab, or other character-delimited file, the procedure does the following to identifies variable name and its data type
   - scans the first 20 records
   - collects the variable names from the first row
   - scans the remaining 19 rows and determines the variable types
   - assigns an informat and a format to each variable
   - creates an INPUT statement
   - submits all of the code to the DATA step compiler, which, in turn, executes the code


[adv_recipe_to_load_remote_delimited_file (from Week 10 Overview)]
- Question (akumar30−stat6250): What is the maximum file size limit of tempfile in SAS to load data directly from webpage?
 


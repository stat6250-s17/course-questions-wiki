## Week 7 Quiz Questions and Answers

In order to prepare your Week 7 Quiz submission, please edit ***this*** document to provide substantive questions for each Quiz Problem and SAS Recipe listed below, as well as answers to at least three questions raised.

All edits should conform to GitHub Markdown specifications (https://guides.github.com/features/mastering-markdown/) and should be committed to a branch named "week-7" in your fork of this repo. Then, after all edits have been made/committed, your Week 7 Quiz should be submitted by initiating a pull request using

- the master branch of the stat6250/course_questions_wiki repo as the base fork and

- the week-7 branch of your version of the repo as the head fork.

The instructor will then review the pull request and make comments should further revision be needed. Then, after the contents of the pull request have been finalized without any merge conflicts, the instructor will merge the pull request.

********************************************************************************



[Course Textbook Chapter 10, Problem 2]
- Question (akumar30−stat6250): Does any variable formatted in the PROC PRINT output statement override the same variable formatted in DATA step?
- Answer (akumar30−stat6250):  Yes, any format option that are done in a PROC PRINT step supersede the data step format assignments for same variable.

[Course Textbook Chapter 10, Problem 6]
- Question (akumar30−stat6250): What is the order of execution in case of multiple IF-THEN statement?
- Answer (akumar30−stat6250):  Each IF statement is evaluated in order it define, even if the first condition is true. 


[Course Textbook Chapter 10, Problem 7]
- Question (akumar30−stat6250): What happen if LENGTH statement appears after any other reference to the variable in the DATA step?
- Answer (akumar30−stat6250):  If the variable has been created by another statement, then a later use of the LENGTH statement will not change its length.

[Course Textbook Chapter 10, Problem 8]
- Question (akumar30−stat6250): Which one has better performance in SAS, multiple if then statement or nested if else statement?

[Course Textbook Chapter 10, Problem 9]
- Question (akumar30−stat6250): What is the ideal position to define the length statement so that the program can run successfully?
- Answer (akumar30−stat6250):  The LENGTH statement should appears before any other reference to the variable in the DATA step.

[Course Textbook Chapter 10, Problem 10]
- Question (akumar30−stat6250): Can we create a new calculated variable in data step which doesn’t exists in keep statement?

[Course Textbook Chapter 11, Problem 1]
- Question (akumar30−stat6250): Does drop statement delete the variables from its original dataset?

[Course Textbook Chapter 11, Problem 2]
- Question (akumar30−stat6250):  Can Data and set option have same dataset name to override the existing dataset?

[Course Textbook Chapter 11, Problem 3]
- Question (akumar30−stat6250): Can we specify multiple variables together in BY statement for multiple group observations for processing at same time?

[Course Textbook Chapter 11, Problem 8]
- Question (akumar30−stat6250): What is the major difference between END=options and POINT= options statement?

[Course Textbook Chapter 11, Problem 9]
- Question (akumar30−stat6250):  What is the content of program data vector after compilation phase is completed of data step?
- Answer (akumar30−stat6250):  The descriptor portion of the new SAS
Data set is created after compilation phase of data step is complete. There are no observations because the DATA step has not yet executed.

[basic_recipe_for_combining_data_vertically (from Week 7 Overview)]
- Question (akumar30−stat6250): If there are two data set having same data structure but variable names and position are different? Can we combine this dataset vertically by using additional keep and retain statement?

[optional: adv_recipe_for_combining_data_vertically (from Week 7 Overview)]
- Question (akumar30−stat6250): How to rewrite concat statement using pro sql?
- Answer (akumar30−stat6250):  The two data sets can be combined vertically, or concatenated, in a DATA step by naming them both in a single SET statement. Here is the example where two dataset 'one' and 'two' are being concatenated:
DATA concat; 
SET one 
        two; 
RUN;

The equivalent SQL statement of concatenated is:
CREATE TABLE concat AS
SELECT *
FROM one
OUTER UNION CORRESPONDING
SELECT *
FROM two
;



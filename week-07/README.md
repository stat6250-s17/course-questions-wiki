## Week 7 Quiz Questions and Answers

In order to prepare your Week 7 Quiz submission, please edit ***this*** document to provide substantive questions for each Quiz Problem and SAS Recipe listed below, as well as answers to at least three questions raised.

All edits should conform to GitHub Markdown specifications (https://guides.github.com/features/mastering-markdown/) and should be committed to a branch named "week-7" in your fork of this repo. Then, after all edits have been made/committed, your Week 7 Quiz should be submitted by initiating a pull request using

- the master branch of the stat6250/course_questions_wiki repo as the base fork and

- the week-7 branch of your version of the repo as the head fork.

The instructor will then review the pull request and make comments should further revision be needed. Then, after the contents of the pull request have been finalized without any merge conflicts, the instructor will merge the pull request.

********************************************************************************



[Course Textbook Chapter 10, Problem 2]
- Question (mcardoso3-stat6250):  Does the 'Amount' label cover only numeric variables?
- Question (akumar30−stat6250): Does any variable formatted in the PROC PRINT output statement override the same variable formatted in DATA step?
- Answer (akumar30−stat6250):  Yes, any format option that are done in a PROC PRINT step supersede the data step format assignments for same variable.



[Course Textbook Chapter 10, Problem 6]
- Question (mcardoso3-stat6250):  How many different ways are there of writing an IF-THEN statement in SAS?
- Question (akumar30−stat6250): What is the order of execution in case of multiple IF-THEN statement?
- Answer (akumar30−stat6250):  Each IF statement is evaluated in order it define, even if the first condition is true. 



[Course Textbook Chapter 10, Problem 7]
- Question (mcardoso3-stat6250):  How long can a new variable be by using the LENGTH statement?
- Question (akumar30−stat6250): What happen if LENGTH statement appears after any other reference to the variable in the DATA step?
- Answer (akumar30−stat6250):  If the variable has been created by another statement, then a later use of the LENGTH statement will not change its length.



[Course Textbook Chapter 10, Problem 8]
- Question (mcardoso3-stat6250):  What is the benefit of using ELSE in an IF-THEN statement?
- Answer (mcardoso3-stat6250):  In a IF-THEN statement with ELSE, SAS executes IF-THEN statements until it encounters the first true statment.
- Question (akumar30−stat6250): Which one has better performance in SAS, multiple if then statement or nested if else statement?



[Course Textbook Chapter 10, Problem 9]
- Question (mcardoso3-stat6250):  Is there a limit to including how many LENGTH statements you type in SAS?
- Question (akumar30−stat6250): What is the ideal position to define the length statement so that the program can run successfully?
- Answer (akumar30−stat6250):  The LENGTH statement should appears before any other reference to the variable in the DATA step.



[Course Textbook Chapter 10, Problem 10]
- Question (mcardoso3-stat6250):  What are the possible errors that you can commit while writing a LENGTH, INFILE, or IF-THEN statement?
- Question (akumar30−stat6250): Can we create a new calculated variable in data step which doesn’t exists in keep statement?



[Course Textbook Chapter 11, Problem 1]
- Question (mcardoso3-stat6250):  Is it required to have both the DROP and KEEP data set options within the same statement?
- Answer (mcardoso3-stat6250):  If certain variables are not referenced, you can use the DROP= option in the SET statement, which doesn't require yo to use the KEEP= option.
- Question (akumar30−stat6250): Does drop statement delete the variables from its original dataset?



[Course Textbook Chapter 11, Problem 2]
- Question (mcardoso3-stat6250):  Will the new data set being created always come before the previous data set has ben specified?
- Question (akumar30−stat6250):  Can Data and set option have same dataset name to override the existing dataset?



[Course Textbook Chapter 11, Problem 3]
- Question (mcardoso3-stat6250):  Why is there no 'middle' variable in each BY group?
- Question (akumar30−stat6250): Can we specify multiple variables together in BY statement for multiple group observations for processing at same time?



[Course Textbook Chapter 11, Problem 8]
- Question (mcardoso3-stat6250):  How would continous looping happen when submitting a program?
- Answer (mcardoso3-stat6250):  The POINT= option reads only specified observations, so SAS can't read an end-of-file indicator as it would if the file was read sequentially.
- Question (akumar30−stat6250): What is the major difference between END=options and POINT= options statement?



[Course Textbook Chapter 11, Problem 9]
- Question (mcardoso3-stat6250):  How soon would observations be revealed when the DATA step has been executed?
- Question (akumar30−stat6250):  What is the content of program data vector after compilation phase is completed of data step?
- Answer (akumar30−stat6250):  The descriptor portion of the new SAS Data set is created after compilation phase of data step is complete. There are no observations because the DATA step has not yet executed.



[basic_recipe_for_combining_data_vertically (from Week 7 Overview)]
- Question (mcardoso3-stat6250):  Why would a length statement need to appear when creating wider character variable?
- Question (akumar30−stat6250): If there are two data set having same data structure but variable names and position are different? Can we combine this dataset vertically by using additional keep and retain statement?



[optional: adv_recipe_for_combining_data_vertically (from Week 7 Overview)]
- Question (mcardoso3-stat6250):  What would be the best option to combine datasets in SAS?
- Question (akumar30−stat6250): How to rewrite concat statement using pro sql?
- Answer (akumar30−stat6250):  The two data sets can be combined vertically, or concatenated, in a DATA step by naming them both in a single SET statement. Here is the example where two dataset 'one' and 'two' are being concatenated:
```SAS
DATA concat; 
SET one two; 
RUN;

*The equivalent SQL statement of concatenated is;
CREATE TABLE concat AS
SELECT *
FROM one
OUTER UNION CORRESPONDING
SELECT *
FROM two
;
```



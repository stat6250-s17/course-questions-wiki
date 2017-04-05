## Week 2 Quiz Questions and Answers

In order to prepare your Week 2 Quiz submission, please edit ***this*** document to provide substantive questions for each Quiz Problem and SAS Recipe listed below, as well as answers to at least three questions raised.

All edits should conform to GitHub Markdown specifications (https://guides.github.com/features/mastering-markdown/) and should be committed to a branch named "week-2" in your fork of this repo. Then, after all edits have been made/committed, your Week 2 Quiz should be submitted by initiating a pull request using

- the master branch of the stat6250/course_questions_wiki repo as the base fork and

- the week-2 branch of your version of the repo as the head fork.

The instructor will then review the pull request and make comments should further revision be needed. Then, after the contents of the pull request have been finalized without any merge conflicts, the instructor will merge the pull request.

********************************************************************************



[Course Textbook Chapter 1, Problem 1]
- Question (yyan11−stat6250): What are observations and variables?
- Answer (yyan11−stat6250): Rows in the data set are called observations, and columns are called variables. 


[Course Textbook Chapter 1, Problem 2]
- Question (yyan11−stat6250): What are DATA steps and PROC steps?
- Answer (yyan11−stat6250): DATA steps typically create or modify SAS data sets. PROC steps are pre-written routines that enable you to analyze and process the data in a SAS data set and to present the data in the form of a report.


[Course Textbook Chapter 1, Problem 3]
- Question (yyan11−stat6250): What is a variable's type?
- Answer (yyan11−stat6250): A variable's type is either character or numeric.


[Course Textbook Chapter 1, Problem 4]
- Question (yyan11−stat6250): What are Numeric variables?
- Answer (yyan11−stat6250): Numeric variables, such as Policy and Total (shown below), can contain only
numeric values (the digits 0 through 9, +, -, ., and E for scientific notation).


[Course Textbook Chapter 1, Problem 5]
- Question (yyan11−stat6250): What are valid variable names? 
- Answer (yyan11−stat6250): Variable names can be 1 to 32 characters long, must begin with a letter (A–Z, either uppercase or lowercase) or an underscore, and can continue with any combination of numbers, letters, or underscores.


[Course Textbook Chapter 1, Problem 8]
- Question (yyan11−stat6250): How many bytes in a numeric variable?
- Answer (yyan11−stat6250): All numeric variables have a default length of 8.


[Course Textbook Chapter 2, Problem 3]
- Question (yyan11−stat6250): Does the YEARCUTOFF= option affectdate values that have four-digit years?
- Answer (yyan11−stat6250): No, the YEARCUTOFF= option doesn't affect date values that have four-digit years.


[Course Textbook Chapter 2, Problem 7]
- Question (yyan11−stat6250): How long are Librefs?
- Answer (yyan11−stat6250): Librefs must be 1 to 8 characters long, must begin with a letter or underscore, and can contain only letters, numbers, or underscores.


[Course Textbook Chapter 2, Problem 8]
- Question (yyan11−stat6250): How the YEARCUTOFF= Option Works?
- Answer (yyan11−stat6250): When a two-digit year value is read, SAS interprets it based on a 100-year span that starts with the YEARCUTOFF= value. 


[Course Textbook Chapter 2, Problem 9]
- Question (yyan11−stat6250): what is the LIBNAME statement?


[loading_data_from_remote_Excel_file SAS Recipe (from Week 2 Overview)]
Question (yyan11−stat6250): what are macros?

* *Question (aalshehry−stat6250):* Wht is themaximum number of observations per dataset? What about variables/columns?
- Question (lzhao4−stat6250): Do missing values affect the structure of the data set?



[Course Textbook Chapter 1, Problem 2]
* *Question (aalshehry−stat6250):* Why should we use “run;” steatment many times within SAS program instead of one time at the end?
* *Answer (aalshehry−stat6250):* The "run;" statement is often not strictly required, as SAS will assume you want to start a new step when it sees data or proc. However your code will be clearer and easier to understand if you make the end of each step explicit.
- Question (lzhao4−stat6250): Add run statement after each program step is an essential?character variable is valid when contains letters and underscores.



[Course Textbook Chapter 1, Problem 3]
* *Question (aalshehry−stat6250):* How many type of variables does SAS support?
- Question (lzhao4−stat6250): Can numeric variable contains letter and underscore?
- Answer (lzhao4−stat6250): A numeric variable can only contain numeric values. A 



[Course Textbook Chapter 1, Problem 4]
* *Question (aalshehry−stat6250):* How to represent missing data in SAS dataset?
- Question (lzhao4−stat6250): Can missing value indicates a different type of variable?



[Course Textbook Chapter 1, Problem 5]
* *Question (aalshehry−stat6250):* Can a character variable begins with a number?
- Question (lzhao4−stat6250): What is the basic rule to set a valid variable name in SAS?



[Course Textbook Chapter 1, Problem 8]
* *Question (aalshehry−stat6250):* Considering all numeric variables have a default length of 8 bytes, what is the maximum value that can SAS accept for a numeric variable?
* *Answer (aalshehry−stat6250):* 
![8 byte](https://github.com/aalshehry-stat6250/course-questions-wiki/blob/Week-2/week-02/8byte.JPG?raw=true)
- Question (lzhao4−stat6250): No matter a numeric variable contains how many digits it has a default length of 8?
- Answer (lzhao4−stat6250): Numeric variable balance always has a default length of 8 unless you set a specific length.



[Course Textbook Chapter 2, Problem 3]
* *Question (aalshehry−stat6250):* Where and how to use YEARCUTOFF option?
- Question (lzhao4−stat6250):  YEARCUTOFF= option has no effect in some cases?
- Answer (lzhao4−stat6250): The YEARCUTOFF= option has no effect when processing dates with four-digits years, processing dates already stored as SAS date values, and displaying dates with SAS date formats.



[Course Textbook Chapter 2, Problem 7]
* *Question (aalshehry−stat6250):* How to save your dataset in the permanent library?
- Question (lzhao4−stat6250): How to correctly assign a SAS libref?



[Course Textbook Chapter 2, Problem 8]
* *Question (aalshehry−stat6250):* Without using the YEARCUTOFF= option, how would SAS interpret 11/11/20? Is it 1920 or 2020?
* *Answer (aalshehry−stat6250):* The default value of YEARCUTOFF= is 1920.
- Question (lzhao4−stat6250): How does YEARCUTOFF= option work on the interpretation of two-digits years?



[Course Textbook Chapter 2, Problem 9]
* *Question (aalshehry−stat6250):* If a SAS session is ended or a libref is deleted, does the library still exist?
* **Answer (aalshehry−stat6250): In these cases, SAS no longer has access to the files in the library.
- Question (lzhao4−stat6250): Libref exists only during the session in which it is created?



[basic_recipe_for_loading_data_from_remote_Excel_file (from Week 2 Overview)]
* *Question (aalshehry−stat6250):* Is it mandatory to use “filename tempfile clear;” step? Why?
- Question (lzhao−stat6250): Do we possible to transfer data from SAS dataset to an excel file? How? 



[optional: bonus_advanced_recipe_for_loading_data_from_remote_Excel_file (from Week 2 Overview)]


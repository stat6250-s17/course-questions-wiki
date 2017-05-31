## Week 10 Quiz Questions and Answers

In order to prepare your Week 10 Quiz submission, please edit ***this*** document to provide substantive questions for each Quiz Problem and SAS Recipe listed below, as well as answers to at least three questions raised.

All edits should conform to GitHub Markdown specifications (https://guides.github.com/features/mastering-markdown/) and should be committed to a branch named "week-10" in your fork of this repo. Then, after all edits have been made/committed, your Week 10 Quiz should be submitted by initiating a pull request using

- the master branch of the stat6250/course_questions_wiki repo as the base fork and

- the week-10 branch of your version of the repo as the head fork.

The instructor will then review the pull request and make comments should further revision be needed. Then, after the contents of the pull request have been finalized without any merge conflicts, the instructor will merge the pull request.

********************************************************************************



[Course Textbook Chapter 16, Problem 1]
* *Question (aalshehry−stat6250):* In INPUT statement, can you re-read the fields? 
* *Answer (aalshehry−stat6250):* Yes, Fields or parts of fields can be re-read.
- Question (dlee117−stat6250): When using column input, can it read character variable values that contain embedded blanks?
- Answer (dlee117-stat6250): Yes, column input can be used to read values that contain embedded blanks. You just need to specify the correct column locations and it will be able to read it.
- Question (akumar30−stat6250): Can we change the order of variables specifies in input statement?
- Question (rluo-stat6250): What is the function of the column input?
- Answer (rluo-stat6250): Column input can be used to read raw data that is stored in an external file. 



[Course Textbook Chapter 16, Problem 5] 
* *Question (aalshehry−stat6250):* What kind of delimiter does INFORMAT contains?
* *Answer (aalshehry−stat6250):*  INFORMAT contains a period which is a required delimiter.
- Question (dlee117−stat6250): What does the informat $w. do? 
- Answer (dlee117-stat6250): It enables you to read character data. The w represents the field width.
- Question (akumar30−stat6250): Can we read nonstandard numeric data without using informat instructions?  
- Answer (akumar30−stat6250): No, we have to use informat instructions in specified format for each type of nonstandard numeric data.
- Question (rluo-stat6250): What are the features of the column input?



[Course Textbook Chapter 16, Problem 7]
* *Question (aalshehry−stat6250):* In INPUT statement, what do “+” and “@” do? 
* *Answer (aalshehry−stat6250):* The + moves the pointer forward ,however, @ moves the pointer back
- Question (dlee117−stat6250): Are there any informats that do not contain a period?
- Answer (dlee117-stat6250): No, each informat always contains a period because it is a required delimiter.
- Question (akumar30−stat6250): Does auto cast applies if we specified the format of numeric data as character in input statement?
- Question (rluo-stat6250): What is standard numeric data?



[Course Textbook Chapter 16, Problem 8] 
* *Question (aalshehry−stat6250):* What does COMMAw.d informat used for?
- Question (dlee117−stat6250): What is the difference between @n column pointer control and +n pointer control?
- Question (akumar30−stat6250): What is the advantage of COMMAw.d informat?
- Answer (akumar30−stat6250): It is used to read numeric values and to remove embedded blanks, commas, dashes, dollar signs, percent signs and right parentheses.
- Question (rluo-stat6250): What does nonstandard numeric dat include?
- Answer (rluo-stat6250): values that contain special characters, date and time values, and data in fraction, binary and hexadecimal.



[Course Textbook Chapter 16, Problem 9] 
* *Question (aalshehry−stat6250):* What does “w” and “d” represent in COMMAw.d informat?
- Question (dlee117−stat6250): If the first field is located in column 1, do you need to use column pointer control to read this field?
- Question (akumar30−stat6250): How to write an input statement if we don’t know the length of each base column in raw data?
- Question (rluo-stat6250): What styles can we choose when encountering raw data that is organized into fixed fields?



[Course Textbook Chapter 17, Problem 1] 
* *Question (aalshehry−stat6250):* How is a free-format different from a formatted input?
- Question (dlee117−stat6250): What is the definition and purpose of a delimiter?
- Question (akumar30−stat6250):  What is free-format raw data in SAS?
- Answer (akumar30−stat6250): Data that is not arranged in columns or do not begin and end in the same columns is classified as free-format raw data.
- Question (rluo-stat6250): What is free-format data?



[Course Textbook Chapter 17, Problem 2] 
* *Question (aalshehry−stat6250):* Do we have to use the dollar sign before a character variable?
- Question (dlee117−stat6250): What is the definition and purpose of a delimiter?
- Question (akumar30−stat6250):  Can we use list input to convert free-format raw data to columns row data?
- Question (rluo-stat6250): Can list input read both standard and nonstandard free-format data?
- Answer (rluo-stat6250): Yes, it can read both.



[Course Textbook Chapter 17, Problem 4] 
* *Question (aalshehry−stat6250):* Can list INPUT skip or re-read fields?
- Question (dlee117−stat6250): When using List Input, do you have to read all of the data or can you use it to only read certain columns? 
- Question (akumar30−stat6250): Can we change the order of columns in free-format raw data using input statement?
- Question (rluo-stat6250): What is the rule of using list input?



[Course Textbook Chapter 17, Problem 5] 
* *Question (aalshehry−stat6250):* When to use DLM= option in the INFILE statement?
- Question (dlee117−stat6250): When trying to specify a delimiter, what happens when that delimiter is also a character that occurs in a data value?
- Question (akumar30−stat6250): Can we processed one raw data using input statement which are separated by different delimiters?
- Question (rluo-stat6250): What is the limitations of list input?



[Course Textbook Chapter 17, Problem 7] 
* *Question (aalshehry−stat6250):* Does the order of the variables matter when using the LENGTH statement?
- Question (dlee117−stat6250): When do you need to enclose your variable list and $ symbol in parentheses when specifying a range of variables?
- Question (akumar30−stat6250):  What is the default length of character variable in input sttatemnet?
- Answer (akumar30−stat6250): Character Variable has default length of 8.
- Question (rluo-stat6250): What is the function of the MISSOVER option?



[Course Textbook Chapter 17, Problem 8] 
* *Question (aalshehry−stat6250):* What does modified list input used for?
- Question (dlee117−stat6250): What should you do if there are missing values that occur at the end of a record?
- Question (akumar30−stat6250): Can we change the default value of dsd from comma ‘,’ to semicolon ‘;’?
- Answer (akumar30−stat6250): Yes, using dlm=option, we can change the default value to any acceptable delimiter.
- Question (rluo-stat6250): What is the function of the LENGTH statement?



[Course Textbook Chapter 17, Problem 10] 
* *Question (aalshehry−stat6250):* when do we use mixed input style?
- Question (dlee117−stat6250): What does the & symbol do when reading raw data values?
- Question (akumar30−stat6250): Can we use dynamic length based on max length of each variable in raw data file?
- Question (rluo-stat6250): How to create a free-format dataset?



[basic_recipe_to_load_remote_delimited_file (from Week 10 Overview)]
* *Question (aalshehry−stat6250):* Is there another effieciant way to determine the longest width for each variable rather than set the width to 100 for all columns?
- Question (dlee117−stat6250): Are there other file types besides .csv that use delimiters besides commas?
- Question (akumar30−stat6250): How proc import identifies the variable name and its data type from external file?
- Answer (akumar30−stat6250): When PROC IMPORT used to read a CSV, tab, or other character-delimited file, the procedure does the following to identifies variable name and its data type
   - scans the first 20 records
   - collects the variable names from the first row
   - scans the remaining 19 rows and determines the variable types
   - assigns an informat and a format to each variable
   - creates an INPUT statement
   - submits all of the code to the DATA step compiler, which, in turn, executes the code
- Question (rluo-stat6250): How can we import delimited text file?



[adv_recipe_to_load_remote_delimited_file (from Week 10 Overview)]
* *Question (aalshehry−stat6250):* Who to deal with TAB as delimitor in INFILE statement?
- Question (dlee117−stat6250): What is the purpose of using the firstobs option and is it necessary?
- Question (akumar30−stat6250): What is the maximum file size limit of tempfile in SAS to load data directly from webpage?
- Question (rluo-stat6250): What is the function of the INFORMAT statement?



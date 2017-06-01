## Week 10 Quiz Questions and Answers

In order to prepare your Week 10 Quiz submission, please edit ***this*** document to provide substantive questions for each Quiz Problem and SAS Recipe listed below, as well as answers to at least three questions raised.

All edits should conform to GitHub Markdown specifications (https://guides.github.com/features/mastering-markdown/) and should be committed to a branch named "week-10" in your fork of this repo. Then, after all edits have been made/committed, your Week 10 Quiz should be submitted by initiating a pull request using

- the master branch of the stat6250/course_questions_wiki repo as the base fork and

- the week-10 branch of your version of the repo as the head fork.

The instructor will then review the pull request and make comments should further revision be needed. Then, after the contents of the pull request have been finalized without any merge conflicts, the instructor will merge the pull request.

********************************************************************************



[Course Textbook Chapter 16, Problem 1]

- Question (yzhu12-stat6250): What are the two input styles for reading data in fixed fields and what's the function of them?
- Answer (yzhu12-stat6250): They are column input and format input. Column input reads standard data only and format input read both standard and nonstandard data.

[Course Textbook Chapter 16, Problem 5]

- Question (yzhu12-stat6250): What's the difference between standard numeric data and nonstandard numeric data?
- Answer (yzhu12-stat6250): Standard numeric data values are values that contain only numbers, scientific notation, decimal points, and plus and minus signs. When numeric data contains characters such as commas or dollar signs, the data is considered to be nonstandard. 

[Course Textbook Chapter 16, Problem 7]

- Question (yzhu12-stat6250): What are the two most common types of record formats?
- Answer (yzhu12-stat6250): Fixed-length records and variable length records. 
  

[Course Textbook Chapter 16, Problem 8]

- Question (yzhu12-stat6250): When reading variable-length records that contain fixed-field data, you can avoid problems by using which statement in the INFILE statement?
- Answer (yzhu12-stat6250): You can use the PAD option.


[Course Textbook Chapter 16, Problem 9]

- Question (yzhu12-stat6250): What is the function of @n?
- Answer (yzhu12-stat6250): The @n is an absolute pointer control that moves the input pointer to a specific column number. You can read columns in any order with the @n column pointer control. 

[Course Textbook Chapter 17, Problem 1]

- Question (yzhu12-stat6250): When can you specify a range of variables in the INPUT statement? 
- Answer (yzhu12-stat6250): You can also specify a range of variables in the INPUT statement when the variable values in the raw data file are sequential and are separated by blanks (or by some other delimiter).

[Course Textbook Chapter 17, Problem 2]

- Question (yzhu12-stat6250): What can you do if your data contains missing values at the end of a record to prevent SAS from reading the next record to find the missing values?
- Answer (yzhu12-stat6250): You can use the INFILE statement with the MISSOVER option.

[Course Textbook Chapter 17, Problem 4]

- Question (yzhu12-stat6250): What's the main differences between DSD option and DLM= option in the INFILE statement?

[Course Textbook Chapter 17, Problem 5]

- Question (yzhu12-stat6250): Under what condition does the DSD option be used to read raw data when there is a missing value at the beginning of a record?
- Answer (yzhu12-stat6250): As long as a delimiter precedes the first value in the record. 

[Course Textbook Chapter 17, Problem 7]

- Question (yzhu12-stat6250): How does the informats work differently in modified list input compared to that they do in formatted input?


[Course Textbook Chapter 17, Problem 8]

- Question (yzhu12-stat6250): How to create a delimited raw data file?
- Answer (yzhu12-stat6250): You can use the DLM= option with a FILE statement to create a delimited raw data file.


[Course Textbook Chapter 17, Problem 10]

- Question (yzhu12- stat6250): When do you need to specify the variable type again when you use the LENGTH statement?
 


[basic_recipe_to_load_remote_delimited_file (from Week 10 Overview)]

- Question (yzhu12-stat6250): The proc import can be hit or miss with delimited text files, then how can we prove the programming performance?

[adv_recipe_to_load_remote_delimited_file (from Week 10 Overview)]

- Question (yzhu12-stat6250): We can convert columns to numeric using recipe of drop and swap, what recipe can we use if we want to convert columns to category?

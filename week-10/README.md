## Week 10 Quiz Questions and Answers

In order to prepare your Week 10 Quiz submission, please edit ***this*** document to provide substantive questions for each Quiz Problem and SAS Recipe listed below, as well as answers to at least three questions raised.

All edits should conform to GitHub Markdown specifications (https://guides.github.com/features/mastering-markdown/) and should be committed to a branch named "week-10" in your fork of this repo. Then, after all edits have been made/committed, your Week 10 Quiz should be submitted by initiating a pull request using

- the master branch of the stat6250/course_questions_wiki repo as the base fork and

- the week-10 branch of your version of the repo as the head fork.

The instructor will then review the pull request and make comments should further revision be needed. Then, after the contents of the pull request have been finalized without any merge conflicts, the instructor will merge the pull request.

********************************************************************************



[Course Textbook Chapter 16, Problem 1]

- Question (yzhu12-stat6250): How to specify array elements.
- Answer (yzhu12-stat6250): You can use a variable list to specify array elements.

[Course Textbook Chapter 16, Problem 5]

- Question (yzhu12-stat6250): Why you don't need to re-specify the stop value of a DO statement if you change the dimension of the array  when you use the DIM function?

[Course Textbook Chapter 16, Problem 7]

- Question (yzhu12-stat6250): What is the difference between FIND function and INDEX function?
- Answer (yzhu12-stat6250):  The FIND function is similar to the INDEX function, but the FIND function enables you to ignore character case in your search and to trim trailing blanks. 

[Course Textbook Chapter 16, Problem 8]

- Question (yzhu12-stat6250): How to assign initial values to character variables?
- Answer (yzhu12-stat6250): You enclose each value in quotation marks and separate the values with commas.

[Course Textbook Chapter 16, Problem 9]

- Question (yzhu12-stat6250): How to create temporary array elements for DATA step processing without creating additional variables?
- Answer (yzhu12-stat6250): Just specify _TEMPORARY_ after the array name and dimension.

[Course Textbook Chapter 17, Problem 1]

- Question (yzhu12-stat6250): What are the two input styles for reading data in fixed fields?
- Answer (yzhu12-stat6250): column input and formatted input.

[Course Textbook Chapter 17, Problem 2]

- Question (yzhu12-stat6250): Why the +n pointer control cannot move backward?

[Course Textbook Chapter 17, Problem 4]

- Question (yzhu12-stat6250): What are the two most common types of record formats?
- Answer (yzhu12-stat6250): Fixed-length records and variable length records. 

[Course Textbook Chapter 17, Problem 5]

- Question (yzhu12-stat6250): When reading variable-length records that contain fixed-field data, you can avoid problems by using which statement in the INFILE statement?
- Answer (yzhu12-stat6250): You can use the PAD option.


[Course Textbook Chapter 17, Problem 7]

- Question (yzhu12-stat6250): What is the function of @n?
- Answer (yzhu12-stat6250): The @n is an absolute pointer control that moves the input pointer to a specific column number. You can read columns in any order with the @n column pointer control. 


[Course Textbook Chapter 17, Problem 8]

- Question (yzhu12-stat6250): What's the difference between standard numeric data and nonstandard numeric data?
- Answer (yzhu12-stat6250): Standard numeric data values are values that contain only numbers, scientific notation, decimal points, and plus and minus signs. When numeric data contains characters such as commas or dollar signs, the data is considered to be nonstandard. 


[Course Textbook Chapter 17, Problem 10]

- Question (yzhu12- stat6250): What's the function of format input?
- Answer (yzhu12-stat6250): Formatted input uses column pointer controls to position the input pointer on a specified column. 


[basic_recipe_to_load_remote_delimited_file (from Week 10 Overview)]

- Question (yzhu12-stat6250): The proc import can be hit or miss with delimited text files, then how can we prove the programming performance?

[adv_recipe_to_load_remote_delimited_file (from Week 10 Overview)]

- Question (yzhu12-stat6250): We can convert columns to numeric using recipe of drop and swap, what recipe can we use if we want to convert columns to category?

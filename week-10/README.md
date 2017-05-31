## Week 10 Quiz Questions and Answers

In order to prepare your Week 10 Quiz submission, please edit ***this*** document to provide substantive questions for each Quiz Problem and SAS Recipe listed below, as well as answers to at least three questions raised.

All edits should conform to GitHub Markdown specifications (https://guides.github.com/features/mastering-markdown/) and should be committed to a branch named "week-10" in your fork of this repo. Then, after all edits have been made/committed, your Week 10 Quiz should be submitted by initiating a pull request using

- the master branch of the stat6250/course_questions_wiki repo as the base fork and

- the week-10 branch of your version of the repo as the head fork.

The instructor will then review the pull request and make comments should further revision be needed. Then, after the contents of the pull request have been finalized without any merge conflicts, the instructor will merge the pull request.

********************************************************************************



[Course Textbook Chapter 16, Problem 1]
- Question (yyan11−stat6250): How many input styles does SAS provide?
- Answer (yyan11−stat6250): SAS provides three primary input styles: column input, formatted input, and list input. 



[Course Textbook Chapter 16, Problem 5]
- Question (yyan11−stat6250): What does the $w. represent?
- Answer (yyan11−stat6250): The $w. informat enables you to read character data. The w represents the field width of the data value (the total number of columns that contain the raw data field).



[Course Textbook Chapter 16, Problem 7]
- Question (yyan11−stat6250): Which one could be used to read numeric values?
- Answer (yyan11−stat6250): The COMMAw.d informat is used to read numeric values and to remove embedded blanks, commas, dashes, dollar signs, percent signs, right parentheses, left parentheses, which are interpreted as minus signs.



[Course Textbook Chapter 16, Problem 8]
- Question (yyan11−stat6250): What are three parts of the COMMAw.d informat?
- Answer (yyan11−stat6250): 1. the informat name COMMA; 2. a value that specifies the width of the field to be read (including dollar signs, decimal w. places, or other special characters), followed by a period; 3. an optional value that specifies the number of implied decimal places for a value (not d necessary if the value already contains decimal places).



[Course Textbook Chapter 16, Problem 9]
- Question (yyan11−stat6250): How to use the @n column pointer control?
- Answer (yyan11−stat6250): The @n is an absolute pointer control that moves the input pointer to a specific column number. The @ moves the pointer to column n, which is the first column of the field that is being read.




[Course Textbook Chapter 17, Problem 1]
- Question (yyan11−stat6250): What is Free-format?
- Answer (yyan11−stat6250): Free-format is not arranged in fixed fields, the fields are often separated by blanks or by some other delimiter. In this case, column input and formatted input that you might have used before to read standard and nonstandard data in fixed fields will not enable you to read all of the values in the raw data file.



[Course Textbook Chapter 17, Problem 2]
- Question (yyan11−stat6250): What is the list input?
- Answer (yyan11−stat6250): List input is a powerful tool for reading both standard and nonstandard free-format data.



[Course Textbook Chapter 17, Problem 4]
- Question (yyan11−stat6250): How to output with missing data records?
- Answer (yyan11−stat6250): You can use the Delimiter Sensitive Data (DSD) option in the INFILE statement to correctly read the raw data. The DSD option changes how SAS treats delimiters when list input is used.



[Course Textbook Chapter 17, Problem 5]
- Question (yyan11−stat6250): How to output using sequential variable names?
- Answer (yyan11−stat6250): You can also specify a range of variables using formatted input. If you specify a range of variables using formatted input, both the variable list and the informat must be enclosed in parentheses, regardless of the variable's type.



[Course Textbook Chapter 17, Problem 7]
- Question (yyan11−stat6250): How to use the LENGTH statement with the INPUT statement?
- Answer (yyan11−stat6250): The LENGTH statement extends the length of the character variable. The LENGTH statement should precede the INPUT statement so that the correct length is defined.



[Course Textbook Chapter 17, Problem 8]
- Question (yyan11−stat6250): How to use modify list input?
- Answer (yyan11−stat6250): There are two modifiers that can be used with list input.The ampersand (&) modifier is used to read character values that contain embedded blanks. The colon (:) modifier is used to read nonstandard data values and character values that are longer than eight characters, but which contain no embedded blanks.



[Course Textbook Chapter 17, Problem 10]
- Question (yyan11−stat6250): Can the modified list input be used to read values that contain embedded blank and nonstandard values?
- Answer (yyan11−stat6250): Yes, modified list input can be used to read values that contain embedded blanks and nonstandard values.



[basic_recipe_to_load_remote_delimited_file (from Week 10 Overview)]
- Question (yyan11−stat6250): Why the errors will occur, if the first few values in a column are numeric and a numerie informat is assumed?



[adv_recipe_to_load_remote_delimited_file (from Week 10 Overview)]
- Question (yyan11−stat6250): Why the informat statement seta each column type to character-values vith width 100?
- Answer (yyan11−stat6250): It' a common convention to use when using disk space usage is less inportant than the time it could take to carefully determine an optimal maximum length or value type for each column.

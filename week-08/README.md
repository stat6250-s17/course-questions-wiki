## Week 8 Quiz Questions and Answers

In order to prepare your Week 8 Quiz submission, please edit ***this*** document to provide substantive questions for each Quiz Problem and SAS Recipe listed below, as well as answers to at least three questions raised.

All edits should conform to GitHub Markdown specifications (https://guides.github.com/features/mastering-markdown/) and should be committed to a branch named "week-8" in your fork of this repo. Then, after all edits have been made/committed, your Week 8 Quiz should be submitted by initiating a pull request using

- the master branch of the stat6250/course_questions_wiki repo as the base fork and

- the week-8 branch of your version of the repo as the head fork.

The instructor will then review the pull request and make comments should further revision be needed. Then, after the contents of the pull request have been finalized without any merge conflicts, the instructor will merge the pull request.

********************************************************************************



[Course Textbook Chapter 13, Problem 1]
- Question (yzhu12-stat6250): What will happen if the SUBSTR function is on the left side of an assignment? How about on the right side of an assignment?
- Answer (yzhu12-stat6250): When the SUBSTR function is on the left side of an assignment statement, it replaces variable values. When SUBSTR is on the right side of an assignment statement, it extracts variable values. 
- Question (akumar30−stat6250): What will be the output of mean function if all arguments has missing values?
- Answer (akumar30−stat6250): It will return a missing value.



[Course Textbook Chapter 13, Problem 2]
- Question (yzhu12-stat6250): What statement do we use if we want to ensure that all forms of a character string are found?
- Answer (yzhu12-stat6250): We can use the UPCASE or LOWCASE function with the INDEX function.
- Question (akumar30−stat6250): Can I use character variable to a function that requires numeric arguments?
- Answer (akumar30−stat6250): Yes, Automatic character-to-numeric conversion occurs when a character value is specified in a function that requires numeric arguments.



[Course Textbook Chapter 13, Problem 3]
- Question (yzhu12-stat6250): What will happen if you specify an invalid data in the MDY function?
- Answer (yzhu12-stat6250):  A missing value will be assigned to the target variable.
- Question (akumar30−stat6250): What will happen if length specifies in input or put statement less than length of new variable?



[Course Textbook Chapter 13, Problem 4]
- Question (yzhu12-stat6250): What kind of error will occur if you don't place the LENGTH statement before the assignment statements that contain the SCAN function?
- Question (akumar30−stat6250): Can I use ANSCI character chr(10) to concatenate multiple values separated by new line ?



[Course Textbook Chapter 13, Problem 5]
- Question (yzhu12-stat6250): Even if a function doesn't require arguments, the function name must still be followed by what?
- Answer (yzhu12-stat6250): It still need to be followed by parentheses.
- Question (akumar30−stat6250): How to extract SAS date from numeric Date?



[Course Textbook Chapter 13, Problem 6]
- Question (yzhu12-stat6250): What do we need to do when specifying a variable list or an array as a function argument?
- Answer (yzhu12-stat6250): We need to precede the list or the array with the word OF.
- Question (akumar30−stat6250): Can I get fiscal calendar date, time and year in SAS?



[Course Textbook Chapter 13, Problem 7]
- Question (yzhu12-stat6250): What function can you use if you want to replace or remove patterns of characters in the values of character variables?
- Answer (yzhu12-stat6250): You can use TRANWRD function.
- Question (akumar30−stat6250): What will be happen if third argument will be missing from SUBSTR function?
- Answer (akumar30−stat6250):  If third argument (n) is omitted, all remaining characters are replaced.



[Course Textbook Chapter 13, Problem 10]
- Question (yzhu12-stat6250): How can you test character values for the presence of a string?
- Answer (yzhu12-stat6250): You need to  use the INDEX function and specify, in parentheses, the name of the variable and the string enclosed in quotation marks.
- Question (akumar30−stat6250): Can I use trim function to store the variable with no trailing spaces?
- Answer (akumar30−stat6250): TRIM function does not affect how a variable is stored. The trimmed values are padded with trailing blanks again if the values are shorter than the length of the new variable.



[recipe_for_isolating_all_duplicates (from Week 8 Overview)]
- Question (yzhu12-stat6250): In the example, the code first*School_Code*last*School_Code=0 is used to ensure that if and only if a value of School_Code only appears exactly once in a dataset. So why doesn't it has the same code to analysis the County_Code and District_Code?
- Question (akumar30−stat6250): If we are removing duplicates in SAS, does also remove duplicate missing value?



[recipe_for_drop_and_swap (from Week 8 Overview)]
- Question (yzhu12-stat6250): What statement can you use if you only want to drop several rows from a particular variable?
- Question (akumar30−stat6250): How to remove special character from SAS Dataset and convert them in to decimal variable?
- Answer (akumar30−stat6250):  using compress (id,'0123456789.','k') option result will show only decimal variable. Here id contains the special character. 



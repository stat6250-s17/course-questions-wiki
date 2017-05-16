## Week 8 Quiz Questions and Answers

In order to prepare your Week 8 Quiz submission, please edit ***this*** document to provide substantive questions for each Quiz Problem and SAS Recipe listed below, as well as answers to at least three questions raised.

All edits should conform to GitHub Markdown specifications (https://guides.github.com/features/mastering-markdown/) and should be committed to a branch named "week-8" in your fork of this repo. Then, after all edits have been made/committed, your Week 8 Quiz should be submitted by initiating a pull request using

- the master branch of the stat6250/course_questions_wiki repo as the base fork and

- the week-8 branch of your version of the repo as the head fork.

The instructor will then review the pull request and make comments should further revision be needed. Then, after the contents of the pull request have been finalized without any merge conflicts, the instructor will merge the pull request.

********************************************************************************



[Course Textbook Chapter 13, Problem 1]
- Question (akumar30−stat6250): What will be the output of mean function if all arguments has missing values?
- Answer (akumar30−stat6250): It will return a missing value.

[Course Textbook Chapter 13, Problem 2]
- Question (akumar30−stat6250): Can I use character variable to a function that requires numeric arguments?
- Answer (akumar30−stat6250): Yes, Automatic character-to-numeric conversion occurs when a character value is specified in a function that requires numeric arguments.

[Course Textbook Chapter 13, Problem 3]
- Question (akumar30−stat6250): What will happen if length specifies in input or put statement less than length of new variable?

[Course Textbook Chapter 13, Problem 4]
- Question (akumar30−stat6250): Can I use ANSCI character chr(10) to concatenate multiple values separated by new line ?

[Course Textbook Chapter 13, Problem 5]
- Question (akumar30−stat6250): How to extract SAS date from numeric Date?

[Course Textbook Chapter 13, Problem 6]
- Question (akumar30−stat6250): Can I get fiscal calendar date, time and year in SAS?

[Course Textbook Chapter 13, Problem 7]
- Question (akumar30−stat6250): What will be happen if third argument will be missing from SUBSTR function?
- Answer (akumar30−stat6250):  If third argument (n) is omitted, all remaining characters are replaced.

[Course Textbook Chapter 13, Problem 10]
- Question (akumar30−stat6250): Can I use trim function to store the variable with no trailing spaces?
- Answer (akumar30−stat6250): TRIM function does not affect how a variable is stored. The trimmed values are padded with trailing blanks again if the values are shorter than the length of the new variable.

[recipe_for_isolating_all_duplicates (from Week 8 Overview)]
- Question (akumar30−stat6250): If we are removing duplicates in SAS, does also remove duplicate missing value?

[recipe_for_drop_and_swap (from Week 8 Overview)]
- Question (akumar30−stat6250): How to remove special character from SAS Dataset and convert them in to decimal variable?
- Answer (akumar30−stat6250):  using compress (id,'0123456789.','k') option result will show only decimal variable. Here id contains the special character. 


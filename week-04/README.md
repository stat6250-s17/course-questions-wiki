## Week 4 Quiz Questions and Answers

In order to prepare your Week 4 Quiz submission, please edit ***this*** document to provide substantive questions for each Quiz Problem and SAS Recipe listed below, as well as answers to at least three questions raised.

All edits should conform to GitHub Markdown specifications (https://guides.github.com/features/mastering-markdown/) and should be committed to a branch named "week-4" in your fork of this repo. Then, after all edits have been made/committed, your Week 4 Quiz should be submitted by initiating a pull request using

- the master branch of the stat6250/course_questions_wiki repo as the base fork and

- the week-4 branch of your version of the repo as the head fork.

The instructor will then review the pull request and make comments should further revision be needed. Then, after the contents of the pull request have been finalized without any merge conflicts, the instructor will merge the pull request.

********************************************************************************



[Course Textbook Chapter 7, Problem 3]
Question (nly13-stat6250): Is it possible to take a range of items, and format them into a number?


[Course Textbook Chapter 7, Problem 4]
Question (nly13-stat6250): In most cases, if there is a missing value, will other=’unknown’ just replace the ‘.’ For missing vlaules with ‘unknown’?


[Course Textbook Chapter 7, Problem 5]
Question (nly13-stat6250):  If there are a mix of numeric and characters in a range, is the best course of action to use 2 separate VALUE statements?


[Course Textbook Chapter 7, Problem 6]
Question (nly13-stat6250): Does the limit of characters on Label have to with how many bytes it can store?


[Course Textbook Chapter 7, Problem 7]
Question (nly13-stat6250): if you use the value statement ‘Low-High’ will that cover the entire range?


[Course Textbook Chapter 7, Problem 8]
Question (nly13-stat6250): Can your format an output statement?


[Course Textbook Chapter 8, Problem 1]
Question (nly13-stat6250): Why are median and range not set as a default of PROC MEANS?


[Course Textbook Chapter 8, Problem 2]
Question (nly13-stat6250): Does the order of the specified variables in PROC MEANS determine the order of the output?
Answer (nly13-stat6250): Generally yes, since SAS usually processes statements in the order given.

[Course Textbook Chapter 8, Problem 4]
Question (nly13-stat6250): What are the differences between CLASS and BY?
Answer (nly13-stat6250): BY processing requires that the data is already sorted or indexed.

[Course Textbook Chapter 8, Problem 7]
Question (nly13-stat6250): How does PROC FREQ order the tables?
Answer (nly13-stat6250): the order of variables for the ‘tables’ statement determines the order.

[Course Textbook Chapter 8, Problem 8]
Question (nly13-stat6250): If you only have numeric values, is it best to turn them into a categorical variable of a range, ex. ‘1- 10’ and then using PROC FREQ?


[Course Textbook Chapter 8, Problem 10]
Question (nly13-stat6250): Are ‘nofreq’, ‘nocol’, ‘norow’, and ‘nopercent’ only used for PROC FREQ?


[Recipe Quantitative]
1.	Question (nly13-stat6250): From the PROC MEANS var statement, it generates a column for variable and label, is there a reason why it
does both since they are the same?


[Recipe Qualitative]
Question (nly13-stat6250): Is it better to use the list option for comparing multiple variables for PROC Freq, rather than letting the standard cross?


[Recipe Bin Value]
Question (nly13-stat6250): If there is a ‘low’ and high’ value setting, is there something that indicates the mean or median for the range?

## Week 4 Quiz Questions and Answers

In order to prepare your Week 4 Quiz submission, please edit ***this*** document to provide substantive questions for each Quiz Problem and SAS Recipe listed below, as well as answers to at least three questions raised.

All edits should conform to GitHub Markdown specifications (https://guides.github.com/features/mastering-markdown/) and should be committed to a branch named "week-4" in your fork of this repo. Then, after all edits have been made/committed, your Week 4 Quiz should be submitted by initiating a pull request using

- the master branch of the stat6250/course_questions_wiki repo as the base fork and

- the week-4 branch of your version of the repo as the head fork.

The instructor will then review the pull request and make comments should further revision be needed. Then, after the contents of the pull request have been finalized without any merge conflicts, the instructor will merge the pull request.

********************************************************************************



[Course Textbook Chapter 7, Problem 3]

- Question (yzhu12-stat6250): Which sign do we must begin with when the name of a format that is created with a VALUE statement?
- Answer (yzhu12-stat6250): A dollar sign must be used.

[Course Textbook Chapter 7, Problem 4]

- Question (yzhu12-stat6250): What does VALUE statement begin with and end with?
- Answer (yzhu12-stat6250): A VALUE statement begins with VALUE and ends with a semicolon after all the labels are defined.

[Course Textbook Chapter 7, Problem 5]

- Question (yzhu12-stat6250): If a value is combined with both numeric and characters, what will happen?
- Answer (yzhu12-stat6250): A value must contain either all numeric or character, or an error will be occurred.

[Course Textbook Chapter 7, Problem 6]

- Question (yzhu12-stat6250): What do you use when you want an apostrophe to appear in a label?
- Answer (yzhu12-stat6250): We need to use two double quotation marks.

[Course Textbook Chapter 7, Problem 7]

- Question (yzhu12-stat6250): Why MISS and MISSING are invalid keywords in SAS?

[Course Textbook Chapter 7, Problem 8]

- Question (yzhu12-stat6250): How to  associate user-defined formats with variables in the FORMAT statement?
- Answer (yzhu12-stat6250): We use the same format names in both the FORMAT and VALUE statements, but place a period at the end of the format name when it is used in the FORMAT statement.


[Course Textbook Chapter 8, Problem 1]

- Question (yzhu12-stat6250): What happens if PROC REPORT can't create groups?
- Answer (yzhu12-stat6250): It displays group variables as order variables.


[Course Textbook Chapter 8, Problem 2]

- Question (yzhu12-stat6250): What is the limitation of using order variables?
- Answer (yzhu12-stat6250): You can't use order variables in a summary report.

[Course Textbook Chapter 8, Problem 4]

- Question (yzhu12-stat6250): What does SAS display if a PROC REPORT can't create groups?
- Answer (yzhu12-stat6250): It displays group variables as order variables. 

[Course Textbook Chapter 8, Problem 7]

- Question (yzhu12-stat6250): How can you specify a split character?

[Course Textbook Chapter 8, Problem 8]

- Question (yzhu12-stat6250): By default, PROC REPORT uses character variables and numeric variables as what kinds of variables, respectively?


[Course Textbook Chapter 8, Problem 10]

- Question (yzhu12-stat6250): Why you can't change the usage of a computed variable?

[recipe_for_summarizing_quantitative_values (from Week 4 Overview)]

- Question (yzhu12-stat6250): What's the method we should use when computing two variables with respect to more than two classification variables?

[recipe_for_summarizing_qualitative_values (from Week 4 Overview)]
 
- Question (yzhu12-stat6250): Why do we need to exclude "missing norow nocol nopercent" in the line operation? WHat's those comments for, respectively?

[recipe_for_temporarily_binning_values discussed (from Week 4 Overview)]

- Question (yzhu12-stat6250): How does SAS sort discrete quantitative variable, qualitative variable, continuous quantitative variable?

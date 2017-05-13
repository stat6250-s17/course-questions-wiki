## Week 7 Quiz Questions and Answers

In order to prepare your Week 7 Quiz submission, please edit ***this*** document to provide substantive questions for each Quiz Problem and SAS Recipe listed below, as well as answers to at least three questions raised.

All edits should conform to GitHub Markdown specifications (https://guides.github.com/features/mastering-markdown/) and should be committed to a branch named "week-7" in your fork of this repo. Then, after all edits have been made/committed, your Week 7 Quiz should be submitted by initiating a pull request using

- the master branch of the stat6250/course_questions_wiki repo as the base fork and

- the week-7 branch of your version of the repo as the head fork.

The instructor will then review the pull request and make comments should further revision be needed. Then, after the contents of the pull request have been finalized without any merge conflicts, the instructor will merge the pull request.

********************************************************************************



[Course Textbook Chapter 10, Problem 2]

- Question (yzhu12-stat6250): Which statement can you use to specify a length before the variable's first value that referred in the DATA step?
- Answer (yzhu12-stat6250): You can use Length statement.

[Course Textbook Chapter 10, Problem 6]

- Question (yzhu12-stat6250): Which statement would you use if you need to read and process variables that you don't want to keep in the dataset?
- Answer (yzhu12-stat6250): You need to use DROP= and KEEP= data set options.

[Course Textbook Chapter 10, Problem 7]

- Question (yzhu12-stat6250): What is the alternative statement of IF-THEN/ELSE statements when you perform conditional processing?
- Answer (yzhu12-stat6250): You can use SELECT groups.

[Course Textbook Chapter 10, Problem 8]

- Question (yzhu12-stat6250):  How can you assign an initial value to a variable whose value is assigned by a sum statement?
- Answer (yzhu12-stat6250): You can use RETAIN statement.

[Course Textbook Chapter 10, Problem 9]

- Question (yzhu12-stat6250): How can you perform many statements as part of the conditional action?
- Answer (yzhu12-stat6250): You can use DO groups.

[Course Textbook Chapter 10, Problem 10]

- Question (yzhu12-stat6250): Why the LENGTH statement has to be before any other reference to the variable in the DATA step?

[Course Textbook Chapter 11, Problem 1]

- Question (yzhu12-stat6250): If there are more than one WHEN statement that has a true when-expression, how many WHEN statements will be used?
- Answer (yzhu12-stat6250): Only the first WHEN statement is used.

[Course Textbook Chapter 11, Problem 2]

- Question (yzhu12-stat6250): When you create a new variable in SAS, what will happen if the variable has been created by another statement instead of the LENGTH statement?
- Answer (yzhu12-stat6250): Then a later use of the LENGTH statement will not change its size.

[Course Textbook Chapter 11, Problem 3]

- Question (yzhu12-stat6250): Is there any other type of comparisons that goes before logistic comparison in SAS?

[Course Textbook Chapter 11, Problem 8]

- Question (yzhu12-stat6250): What's the alternative statement that works the same as the ELSE statement in SAS?

[Course Textbook Chapter 11, Problem 9]

- Question (yzhu12-stat6250): Why you can't use DROP or KEEP statements in PROC steps?

[basic_recipe_for_combining_data_vertically (from Week 7 Overview)]

- Question (yzhu12-stat6250): In what situation that the indicator variables are not eligible?

[optional: adv_recipe_for_combining_data_vertically (from Week 7 Overview)]

- Question (yzhu12-stat6250): The statement "union all corr" can include all the columns with the corresponding names, does that mean the missing columns are skipped automatically and the remained ones are matched up with each other precisely?

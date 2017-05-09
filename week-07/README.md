## Week 7 Quiz Questions and Answers

In order to prepare your Week 7 Quiz submission, please edit ***this*** document to provide substantive questions for each Quiz Problem and SAS Recipe listed below, as well as answers to at least three questions raised.

All edits should conform to GitHub Markdown specifications (https://guides.github.com/features/mastering-markdown/) and should be committed to a branch named "week-7" in your fork of this repo. Then, after all edits have been made/committed, your Week 7 Quiz should be submitted by initiating a pull request using

- the master branch of the stat6250/course_questions_wiki repo as the base fork and

- the week-7 branch of your version of the repo as the head fork.

The instructor will then review the pull request and make comments should further revision be needed. Then, after the contents of the pull request have been finalized without any merge conflicts, the instructor will merge the pull request.

********************************************************************************



[Course Textbook Chapter 10, Problem 2]

- Question (yzhu12-stat6250): During Opening and Closing ODS destinations, what's a good choice you should make if you don't need to create listing output?
- Answer (yzhu12-stat6250): It's a good idea to close the Listing destination.

[Course Textbook Chapter 10, Problem 6]

- Question (yzhu12-stat6250): How can you close the several opening ODS destinations all?
- Answer (yzhu12-stat6250): You can close them all by using the ODS_ALL_CLOSE statement.

[Course Textbook Chapter 10, Problem 7]

- Question (yzhu12-stat6250): Which statements will you use if your goal is to create a table of contents that links to your HTML output?
- Answer (yzhu12-stat6250): You can use the CONTENTS= and FRAME= options with the ODS HTML statement.

[Course Textbook Chapter 10, Problem 8]

- Question (yzhu12-stat6250): Why you don't need to specify the complete pathname for the body, contents, or frame files when you use the PATH= option?

[Course Textbook Chapter 10, Problem 9]

- Question (yzhu12-stat6250): What good step you should take before you create HTML output and re-open the Listing destination after you close the HTML destination?
- Answer (yzhu12-stat6250): It's a good idea to close the Listing destination.

[Course Textbook Chapter 10, Problem 10]

- Question (yzhu12-stat6250): How can you change the appearance of HTML output?
- Answer (yzhu12-stat6250): By using the STYLE= option in the ODS HTML statement. 

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

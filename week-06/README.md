larry- Question (ilankham鈭抯tat6250): ## Week 6 Quiz Questions and Answers

In order to prepare your Week 6 Quiz submission, please edit ***this*** document to provide substantive questions for each Quiz Problem and SAS Recipe listed below, as well as answers to at least three questions raised.

All edits should conform to GitHub Markdown specifications (https://guides.github.com/features/mastering-markdown/) and should be committed to a branch named "week-6" in your fork of this repo. Then, after all edits have been made/committed, your Week 6 Quiz should be submitted by initiating a pull request using

- the master branch of the stat6250/course_questions_wiki repo as the base fork and

- the week-6 branch of your version of the repo as the head fork.

The instructor will then review the pull request and make comments should further revision be needed. Then, after the contents of the pull request have been finalized without any merge conflicts, the instructor will merge the pull request.

********************************************************************************



[Course Textbook Chapter 12, Problem 1]
- Question (hhu9-stat6250): In one-to-one matching, if thay have different number of observations, what will happen when been merged?
- Answer (hhu9-stat6250): the number of observations in new data set is the number of observations in the smallest original data set.  

[Course Textbook Chapter 12, Problem 2]
- Question (hhu9-stat6250): What order should "BY" variables be followed in new data set? I mean in this case, should “larry" be above than second "curly"?

[Course Textbook Chapter 12, Problem 3]
- Question (hhu9-stat6250): What will happen if the first table have a long list of observations? we will not see the observations of second table in new table, so why dont the new table pull all observations of second table to parallel with the observations of first table. 

[Course Textbook Chapter 12, Problem 4]
- Question (hhu9-stat6250): Can we use concatenate when there are missing variables?
- Answer (hhu9-stat6250): no, the concatenate data set is read sequentially, if there are missing variables or different columns, the new table will not contain some useful information.

[Course Textbook Chapter 12, Problem 5]
- Question (hhu9-stat6250): What will happen will two input data set has same variable?
- Answer (hhu9-stat6250): the variable in second data set will cover first one. And why the new data set do not defaultly list the same variable as "variable1" and "variable2"? 

[Course Textbook Chapter 12, Problem 7]
- Question (hhu9-stat6250): Is the same that we use"RENAME" to change the name of variable in first data set or second? 

[Course Textbook Chapter 12, Problem 9]
- Question (hhu9-stat6250): How to represent missing numeric value? 
- Answer (hhu9-stat6250): we use "."to represent the missing numeric value?

[basic_recipe_for_combining_data_horizontally (from Week 6 Overview)] 
- Question (hhu9-stat6250): when should we use"update" instead of "merge"?

[optional: adv_recipe_for_combining_data_horizontally (from Week 6 Overview)] 
- Question (hhu9-stat6250): What is the fuction of output statement? how can we use it to get a table from one column data source?？

## Week 6 Quiz Questions and Answers

In order to prepare your Week 6 Quiz submission, please edit ***this*** document to provide substantive questions for each Quiz Problem and SAS Recipe listed below, as well as answers to at least three questions raised.

All edits should conform to GitHub Markdown specifications (https://guides.github.com/features/mastering-markdown/) and should be committed to a branch named "week-6" in your fork of this repo. Then, after all edits have been made/committed, your Week 6 Quiz should be submitted by initiating a pull request using

- the master branch of the stat6250/course_questions_wiki repo as the base fork and

- the week-6 branch of your version of the repo as the head fork.

The instructor will then review the pull request and make comments should further revision be needed. Then, after the contents of the pull request have been finalized without any merge conflicts, the instructor will merge the pull request.

********************************************************************************



[Course Textbook Chapter 12, Problem 1]
Question (cyuan10-stat6250): Can you merge together two table sets with different number of records? 
Answer (cyuan10-stat6250): Yes, in one-to-one merging for example will simply take the first observation from one table and merge with the first observation from the second table and so on - they do not have to be of equal number of observations.



[Course Textbook Chapter 12, Problem 2]
Question (cyuan10-stat6250): Can you move two tables based on an unique identifier vs. based on order of observation?
Answer (cyuan10-stat6250): Yes, you can still do this with one-to-one merging. You can sort both variables based on the single unique identifier and then merge the two.



[Course Textbook Chapter 12, Problem 3]
Question (cyuan10-stat6250): What does concatenate do and how is it different from one-to-one merging?
Answer (cyuan10-stat6250): Concatenate is another way of merging data tables. However, records of the 2nd table is appended or added on to the first table. So if you have 6 records in the 1st and 6 in the 2nd, you will end up with 12 total records in the concatenate table.



[Course Textbook Chapter 12, Problem 4]
Question (cyuan10-stat6250): What is the benefit of using interleaving data step and when do you gain an advantage when using it?



[Course Textbook Chapter 12, Problem 5]
Question (cyuan10-stat6250): What is the difference with Match-merging vs. using one-to-one merge with sort? And how is missing values dealt with?



[Course Textbook Chapter 12, Problem 7]
Question (cyuan10-stat6250): Can you use match-merging on two different variables for matching? For example, if variable 1 matches, check variable 2 before merging?



[Course Textbook Chapter 12, Problem 9]
Question (cyuan10-stat6250): How are duplicative records handled? Is this something that will be called out in any way during the table merge step or compilation step?



[basic_recipe_for_combining_data_horizontally (from Week 6 Overview)]
Question (cyuan10-stat6250): What are some of the best practices when it comes to renaming columns in newly merged datasets? Does it help to add a specific identifier to these columns so that we know which ones are merged?

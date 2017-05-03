## Week 6 Quiz Questions and Answers

In order to prepare your Week 6 Quiz submission, please edit ***this*** document to provide substantive questions for each Quiz Problem and SAS Recipe listed below, as well as answers to at least three questions raised.

All edits should conform to GitHub Markdown specifications (https://guides.github.com/features/mastering-markdown/) and should be committed to a branch named "week-6" in your fork of this repo. Then, after all edits have been made/committed, your Week 6 Quiz should be submitted by initiating a pull request using

- the master branch of the stat6250/course_questions_wiki repo as the base fork and

- the week-6 branch of your version of the repo as the head fork.

The instructor will then review the pull request and make comments should further revision be needed. Then, after the contents of the pull request have been finalized without any merge conflicts, the instructor will merge the pull request.

********************************************************************************



[Course Textbook Chapter 12, Problem 1]
- Question (yyan11−stat6250): How One-to-One Merging Selects Data?
- Answer (yyan11−stat6250): When you perform one-to-one merging, the new data set contains all the variables from all the input data sets. If the data sets contain variables that have the same names, the values that are read from the last data set overwrite the values that were read from earlier data sets.



[Course Textbook Chapter 12, Problem 2]
- Question (yyan11−stat6250): How Interleaving Selects Data?
- Answer (yyan11−stat6250): When SAS interleaves data sets, observations in each BY group in each data set in the SET statement are read sequentially, in the order in which the data sets and BY variables are listed, until all observations have been processed. The new data set includes all the variables from all the input data sets, and it contains the total number of observations from all input data sets.



[Course Textbook Chapter 12, Problem 3]
- Question (yyan11−stat6250): How Concatenating Selects Data?
- Answer (yyan11−stat6250): When a program concatenates data sets, all of the observations are read from the first data set listed in the SET statement. Then all of the observations are read from the second data set listed, and so on, until all of the listed data sets have been read. The new data set contains all of the variables and observations from all of the input data sets.



[Course Textbook Chapter 12, Problem 4]
- Question (yyan11−stat6250): How to read the concatenated data sets?
- Answer (yyan11−stat6250):  The concatenated data sets are read sequentially, in the order in which they are listed in the SET statement. 



[Course Textbook Chapter 12, Problem 5]
- Question (yyan11−stat6250): What happen if have the same name variables in more than one input data set?
- Answer (yyan11−stat6250): If you have variables with the same name in more than one input data set, values of the same-named variable in the first data set in which it appears are overwritten by values of the same-named variable in subsequent data sets. 




[Course Textbook Chapter 12, Problem 7]
- Question (yyan11−stat6250): How to prevent the values from being overwritten when you merge the two data sets?
- Answer (yyan11−stat6250): To prevent overwriting, you can rename variables by using the RENAME= data set option in the MERGE statement.



[Course Textbook Chapter 12, Problem 9]
- Question (yyan11−stat6250): How Match-Merging Selects Data?
- Answer (yyan11−stat6250): Generally speaking, during match-merging, SAS sequentially checks each observation of each data set to see whether the BY values match, and then writes the combined observation to the new data set.



[basic_recipe_for_combining_data_horizontally (from Week 6 Overview)]
- Question (yyan11−stat6250): What happen if two datasets have the same name column?



## Week 6 Quiz Questions and Answers

In order to prepare your Week 6 Quiz submission, please edit ***this*** document to provide substantive questions for each Quiz Problem and SAS Recipe listed below, as well as answers to at least three questions raised.

All edits should conform to GitHub Markdown specifications (https://guides.github.com/features/mastering-markdown/) and should be committed to a branch named "week-6" in your fork of this repo. Then, after all edits have been made/committed, your Week 6 Quiz should be submitted by initiating a pull request using

- the master branch of the stat6250/course_questions_wiki repo as the base fork and

- the week-6 branch of your version of the repo as the head fork.

The instructor will then review the pull request and make comments should further revision be needed. Then, after the contents of the pull request have been finalized without any merge conflicts, the instructor will merge the pull request.

********************************************************************************

[Course Textbook Chapter 12, Problem 1]

* *Question (aalshehry−stat6250):* What is the right way to concatenate two datasets in a new one?

* *Answer (aalshehry−stat6250):* 

By using the following syntax: 

DATA SAS-data-set;
       SET SAS-data-set1 SAS-data-set2 ...;
RUN;


[Course Textbook Chapter 12, Problem 2]

* *Question (aalshehry−stat6250):* What is the main difference between using SET and Merge statements in DATA step?



[Course Textbook Chapter 12, Problem 3]

* *Question (aalshehry−stat6250):* What is the default oreder of the output obsevations when SET statement is used to combine two datasets?




[Course Textbook Chapter 12, Problem 4]

* *Question (aalshehry−stat6250):* Before concatenate datasets, what should we pay attention to?

* *Answer (aalshehry−stat6250):*  It is important to know the structure and contents of the input datasets by checking the describtive part and the data as well.




[Course Textbook Chapter 12, Problem 5]

* *Question (aalshehry−stat6250):* What is the best way to combine multiple datasets which have a primar-key variable?



[Course Textbook Chapter 12, Problem 7]

* *Question (aalshehry−stat6250):* In MERGE statement, what the possible values for IN option? and how it can be utilized?

* *Answer (aalshehry−stat6250):*  The IN= variables have two possible values: 0 and 1 which indicates whether a data set contributed information to the observation.

MERGE SAS-data-set1 <(IN=variable)>...



[Course Textbook Chapter 12, Problem 9]

* *Question (aalshehry−stat6250):* What will happen if two datasets were combined with the same variable name but with different type?


[Recipes TBA]

* *Question (aalshehry−stat6250):* Using Program Data Vector (PDV) has many advantages, but what are its disadvantages?

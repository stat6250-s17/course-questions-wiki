## Week 7 Quiz Questions and Answers

In order to prepare your Week 7 Quiz submission, please edit ***this*** document to provide substantive questions for each Quiz Problem and SAS Recipe listed below, as well as answers to at least three questions raised.

All edits should conform to GitHub Markdown specifications (https://guides.github.com/features/mastering-markdown/) and should be committed to a branch named "week-7" in your fork of this repo. Then, after all edits have been made/committed, your Week 7 Quiz should be submitted by initiating a pull request using

- the master branch of the stat6250/course_questions_wiki repo as the base fork and

- the week-7 branch of your version of the repo as the head fork.

The instructor will then review the pull request and make comments should further revision be needed. Then, after the contents of the pull request have been finalized without any merge conflicts, the instructor will merge the pull request.

********************************************************************************



[Course Textbook Chapter 10, Problem 2]

* *Question (aalshehry−stat6250):* How to assign the formats permanently?

* *Answer (aalshehry−stat6250):*  Formats can be assigned temporarily in PROC steps and permanently in DATA steps.

[Course Textbook Chapter 10, Problem 6]

* *Question (aalshehry−stat6250):* When we use IF-THEN statement, how to differenciate between variable type?

[Course Textbook Chapter 10, Problem 7]

* *Question (aalshehry−stat6250):* Why we might want to specify a length for a character variable, rather than let the first assigned value determine the length?


[Course Textbook Chapter 10, Problem 8]

* *Question (aalshehry−stat6250):* What is the benifit of using ELSE in IF-THEN statement?

* *Answer (aalshehry−stat6250):* SAS wont evaluate the code that included within ELSE statement unless all previous IF's are not meet the condition which can save some resources.


[Course Textbook Chapter 10, Problem 9]

* *Question (aalshehry−stat6250):* In case of using LENGTH statement to assign a length to a character variable, where it supposed to be located?

* *Answer (aalshehry−stat6250):* It must be the first reference to the character variables in the DATA step. Therefore, the best position in the DATA step for a LENGTH statement is immediately after the DATA statement.



[Course Textbook Chapter 10, Problem 10]

* *Question (aalshehry−stat6250):* What are the  differences between the DROP & KEEP statements and the DROP= & KEEP= data set options?


[Course Textbook Chapter 11, Problem 1]

* *Question (aalshehry−stat6250):* If you use more than one data set option or a combination of data set options and statements, what is the order that SAS applying for drops, keeps, and renames variables?

[Course Textbook Chapter 11, Problem 2]

* Question (aalshehry−stat6250): What kind of IF logical operators can we use within a DATA step?

[Course Textbook Chapter 11, Problem 3]

* *Question (aalshehry−stat6250):* Can we use multiple BY statements within a DATA step?

* *Answer (aalshehry−stat6250):* Only one BY statement can accompany each SET statement in a DATA step.


[Course Textbook Chapter 11, Problem 8]

* *Question (aalshehry−stat6250):* What is the value of the END= variable when random access is used?

[Course Textbook Chapter 11, Problem 9]

* *Question (aalshehry−stat6250):* What are the added values of using program data vector (PDV) compared to the other database platforms?

[basic_recipe_for_combining_data_vertically (from Week 7 Overview)]


* *Question (aalshehry−stat6250):* What is the main advantage of using "IN=" Statement?

[optional: adv_recipe_for_combining_data_vertically (from Week 7 Overview)]

* *Question (aalshehry−stat6250):* How to sort the selected data using PROQ SQL?


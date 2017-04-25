## Week 5 Quiz Questions and Answers

In order to prepare your Week 5 Quiz submission, please edit ***this*** document to provide substantive questions for each Quiz Problem and SAS Recipe listed below, as well as answers to at least three questions raised.

All edits should conform to GitHub Markdown specifications (https://guides.github.com/features/mastering-markdown/) and should be committed to a branch named "week-5" in your fork of this repo. Then, after all edits have been made/committed, your Week 5 Quiz should be submitted by initiating a pull request using

- the master branch of the stat6250/course_questions_wiki repo as the base fork and

- the week-5 branch of your version of the repo as the head fork.

The instructor will then review the pull request and make comments should further revision be needed. Then, after the contents of the pull request have been finalized without any merge conflicts, the instructor will merge the pull request.

********************************************************************************



[Course Textbook Chapter 5, Problem 1]
* *Question (aalshehry−stat6250):* What is the general form of using FILENAME statement?

* *Answer (aalshehry−stat6250):* FILENAME fileref 'filename';


[Course Textbook Chapter 5, Problem 2]
* *Question (aalshehry−stat6250):* Why does Fileref statement lose its information after ending SAS session?

[Course Textbook Chapter 5, Problem 6]

* *Question (aalshehry−stat6250):* In INPUT statement, what do the numbers after the variables represent? 

* *Answer (aalshehry−stat6250):* 

INPUT variable <$> startcol-endcol . . .;

The dollar sign ($) identifies the variable type as character (if the variable is numeric, then nothing appears here)
startcol represents the starting column for this variable
endcol represents the ending column for this variable.

[Course Textbook Chapter 5, Problem 7]

* *Question (aalshehry−stat6250):* What information should be provided to use INPUT statement?


[Course Textbook Chapter 5, Problem 8]

* *Question (aalshehry−stat6250):* When you re-define the value of a variable, can you restore the orginal values?


[Course Textbook Chapter 6, Problem 1]

* *Question (aalshehry−stat6250):* After the compilation phase is completed, what SAS compiler will create next.

* *Answer (aalshehry−stat6250):* The descriptor portion of the new data set will be created.



[Course Textbook Chapter 6, Problem 2]

* *Question (aalshehry−stat6250):* What type of syntax errors does SAS can recognize? 


[Course Textbook Chapter 6, Problem 3]

* *Question (aalshehry−stat6250):* How to change/redirect the defult Data statem?


[Course Textbook Chapter 6, Problem 4]

* *Question (aalshehry−stat6250):* What is the function of _N_ and _ERROR_?


[Course Textbook Chapter 6, Problem 5]

* *Question (aalshehry−stat6250):* What values can _ERROR_ takes?


[Course Textbook Chapter 6, Problem 6]

* *Question (aalshehry−stat6250):* Why SAS assigns variables in the program data vector to missing before each execution of the DATA step?



[basic_recipe_for_creating_analytic_datasets (from Week 5 Overview)]

* *Question (aalshehry−stat6250):* What os the difference between "Retain" and "Keep" in DATA statement?
 

[optional: adv_recipe_for_creating_analytic_datasets (from Week 5 Overview)]

* *Question (aalshehry−stat6250):* In SQL inquery, what is the substitue of proc means and proc freq?



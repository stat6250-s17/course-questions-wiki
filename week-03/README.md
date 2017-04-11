## Course Structure Quiz Problems

In order to prepare your Week 3 Quiz submission, please edit ***this*** document to provide substantive questions for each Quiz Problem and SAS Recipe listed below, as well as answers to at least three questions raised.

All edits should conform to GitHub Markdown specifications (https://guides.github.com/features/mastering-markdown/) and should be committed to a branch named "week-3" or "week-03" in your fork of this repo. Then, after all edits have been made/committed, your Week 3 Quiz should be submitted by initiating a pull request using

- the master branch of the stat6250/course_questions_wiki repo as the base fork and

- the week-03 branch of your version of the repo as the head fork.

The instructor will then review the pull request and make comments should further revision be needed. Then, after the contents of the pull request have been finalized without any merge conflicts, the instructor will merge the pull request.

********************************************************************************


[Course Textbook Chapter 3, Problem 1]
* *Question (aalshehry−stat6250):* Why code formatting is important?
* *Answer (aalshehry−stat6250):* Even though, SAS statements can be written in any format, a consistent layout improve readability and helps understand the program's purpose easily.



[Course Textbook Chapter 3, Problem 2]
* *Question (aalshehry−stat6250):* How can we clear the output window and the log window?



[Course Textbook Chapter 3, Problem 3]
* *Question (aalshehry−stat6250):* Can we specify more than one “BY variable”?
* *Answer (aalshehry−stat6250):*  You can specify as many BY variables as you wish for example:
```SAS
PROC SORT;
      BY variable-1 ... variable-n;
```
 
 
 
[Course Textbook Chapter 3, Problem 4]
* *Question (aalshehry−stat6250):* What will SAS display in the log window when a syntax error detected?
* *Answer (aalshehry−stat6250):*  it will displays the word ERROR, identifies the possible location of the error, and gives an explanation of the error.



[Course Textbook Chapter 3, Problem 5]
* *Question (aalshehry−stat6250):* What type of errors can SAS detect?



[Course Textbook Chapter 3, Problem 6]
* *Question (aalshehry−stat6250):* What is an invalid option?



[Course Textbook Chapter 3, Problem 7]
* *Question (aalshehry−stat6250):* What are data errors?



[Course Textbook Chapter 3, Problem 10]
* *Question (aalshehry−stat6250):* Is there a situation where “Run;” statement is not required?



[Course Textbook Chapter 4, Problem 1]
* *Question (aalshehry−stat6250):* How to change the name of a variable(column)?



[Course Textbook Chapter 4, Problem 3]
* *Question (aalshehry−stat6250):* How to use WHERE statement to select multiple values from numerical observations?



[Course Textbook Chapter 4, Problem 4]
* *Question (aalshehry−stat6250):* What will happen if you run a PROC SORT statement without OUT= option?



[Course Textbook Chapter 4, Problem 7]
* *Question (aalshehry−stat6250):* Is “BY” statement required in “PROC SORT”?



[Course Textbook Chapter 4, Problem 9]
* *Question (aalshehry−stat6250):* What symbols represent “not equal to” operator in SAS?



[Course Textbook Chapter 4, Problem 10]
* *Question (aalshehry−stat6250):* What does “NOOBS” in “PROC PRINT” do?



[recipe_to_check_for_duplicates (from Week 3 Overview)]
* *Question (aalshehry−stat6250):* Does “DUPOUT” save unique observations without the duplicated rows or does it save only the duplicated observations?



[recipe_for_sorting_data (from Week 3 Overview)]
* *Question (aalshehry−stat6250):* What is the default sorting option? Is it ascending or descending?



[recipe_for_printing_values (from Week 3 Overview)]
* *Question (aalshehry−stat6250):* How to PROC PRINT to print a specific range of data (i.e. rows from 20 to 30)?




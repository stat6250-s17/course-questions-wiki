## Week 3 Quiz Questions and Answers

In order to prepare your Week 3 Quiz submission, please edit ***this*** document to provide substantive questions for each Quiz Problem and SAS Recipe listed below, as well as answers to at least three questions raised.

All edits should conform to GitHub Markdown specifications (https://guides.github.com/features/mastering-markdown/) and should be committed to a branch named "week-3" in your fork of this repo. Then, after all edits have been made/committed, your Week 3 Quiz should be submitted by initiating a pull request using

- the master branch of the stat6250/course_questions_wiki repo as the base fork and

- the week-3 branch of your version of the repo as the head fork.

The instructor will then review the pull request and make comments should further revision be needed. Then, after the contents of the pull request have been finalized without any merge conflicts, the instructor will merge the pull request.

********************************************************************************


[Course Textbook Chapter 3, Problem 1]

* *Question (aalshehry−stat6250):* Why code formatting is important?
* *Answer (aalshehry−stat6250):* Even though, SAS statements can be written in any format, a consistent layout improve readability and helps understand the program's purpose easily.

- Question (yzhu12-stat6250): It's a good idea to begin DATA steps, proc steps, and RUN statements on which side to indent statements within a step?
- Answer (yzhu12-stat6250): On the left side.



[Course Textbook Chapter 3, Problem 2]

* *Question (aalshehry−stat6250):* How can we clear the output window and the log window?

- Question (yzhu12-stat6250): When a Syntex error occurs and SAS displays the word ERROR, what information will it identify?
- Answer (yzhu12-stat6250): It will identify the location of the error and explans the cause of error.




[Course Textbook Chapter 3, Problem 3]

* *Question (aalshehry−stat6250):* Can we specify more than one “BY variable”?
* *Answer (aalshehry−stat6250):*  You can specify as many BY variables as you wish for example:
```SAS
PROC SORT;
      BY variable-1 ... variable-n;
      
```

- Question (yzhu12-stat6250): How to correct the program that contains syntax error?
- Answer (yzhu12-stat6250): You can correct the errors in the Editor window and then resubmit the revised program. You can delete any error-free steps from a revised program before resubmitting it. 
 
 
 
[Course Textbook Chapter 3, Problem 4]

* *Question (aalshehry−stat6250):* What will SAS display in the log window when a syntax error detected?
* *Answer (aalshehry−stat6250):*  it will displays the word ERROR, identifies the possible location of the error, and gives an explanation of the error.

- Question (yzhu12-stat6250): What does SAS reflect if you submit a statement that contains an invalid option?
- Answer (yzhu12-stat6250): A log message will appear to notify you that the option is not valid or recognized.


[Course Textbook Chapter 3, Problem 5]

* *Question (aalshehry−stat6250):* What type of errors can SAS detect?

- Question (yzhu12-stat6250): Will missing RUN statements, missing semicolons, unbalanced quotation marks, and invalid options cause error or just make SAS produce a warning message?




[Course Textbook Chapter 3, Problem 6]

* *Question (aalshehry−stat6250):* What is an invalid option?

- Question (yzhu12-stat6250): What will cause syntax error and what will cause data error? What is the difference between the main causes?



[Course Textbook Chapter 3, Problem 7]

* *Question (aalshehry−stat6250):* What are data errors?

- Question (yzhu12-stat6250): When a SAS program that contains errors is submitted, error messages appear in the Log window. How many types of SAS errors can be detected?
- Answer (yzhu12-stat6250): Three types of errors can be detected: syntax, execution-time and data. 


[Course Textbook Chapter 3, Problem 10]

* *Question (aalshehry−stat6250):* Is there a situation where “Run;” statement is not required?

- Question (yzhu12-stat6250): How to look for and replace text using the editor Window?

[Course Textbook Chapter 4, Problem 1]

* *Question (aalshehry−stat6250):* How to change the name of a variable(column)?

- Question (yzhu12-stat6250): You can refine a basic report by sort the data, generate columns totals for numeric variables or?
- Answer (yzhu12-stat6250): You can also select which variables and observations are processed.

[Course Textbook Chapter 4, Problem 3]

* *Question (aalshehry−stat6250):* How to use WHERE statement to select multiple values from numerical observations?

- Question (yzhu12-stat6250): In Where statement, Character values must be enclosed in quotation marks and must be in the same case as in the data set, is that true?


[Course Textbook Chapter 4, Problem 4]

* *Question (aalshehry−stat6250):* What will happen if you run a PROC SORT statement without OUT= option?

- Question (yzhu12-stat6250): In a PROC SORT step, what method should you use for specifying an output data?

[Course Textbook Chapter 4, Problem 7]

* *Question (aalshehry−stat6250):* Is “BY” statement required in “PROC SORT”?

- Question (yzhu12-stat6250): Why does the step PROC SORT fails if it doesn't contain BY statement?

[Course Textbook Chapter 4, Problem 9]

* *Question (aalshehry−stat6250):* What symbols represent “not equal to” operator in SAS?

- Question (yzhu12-stat6250): How can we assign a descriptive label to a variable?
- Answer (zhu12-stat6250): We use the LABEL statement.


[Course Textbook Chapter 4, Problem 10]

* *Question (aalshehry−stat6250):* What does “NOOBS” in “PROC PRINT” do?

- Question (yzhu12-stat6250): What statements do remain in effect only for the PROC step in which they appear?
- Answer (yzhu12-stat6250): VAR, WHERE and SUM.

[recipe_to_check_for_duplicates (from Week 3 Overview)]

* *Question (aalshehry−stat6250):* Does “DUPOUT” save unique observations without the duplicated rows or does it save only the duplicated observations?

- Question (yzhu12-stat6250): If the out=option is set to anything other than the null data set _null_, then a deduplicated could also be formed- so what other function will cause the same problem?




[recipe_for_sorting_data (from Week 3 Overview)]

* *Question (aalshehry−stat6250):* What is the default sorting option? Is it ascending or descending?

- Question (yzhu12-stat6250): How can we sort numerical variables out of all the variables and assign specific group of values to them using SAS?


[recipe_for_printing_values (from Week 3 Overview)]

* *Question (aalshehry−stat6250):* How to PROC PRINT to print a specific range of data (i.e. rows from 20 to 30)?


- Question (yzhu12-stat6250): In the example, SAS print out var and id as rows and columns. How does "Explorer" look like when it print out and when should we use "Explorer"?


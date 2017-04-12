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
- Question (kveng−stat6250): Does the code still work without indenting the statements within step?
- Answer (kveng−stat6250): I tested it. The code still work but it's a good idea indeed to indent the statements for better reading.



[Course Textbook Chapter 3, Problem 2]
* *Question (aalshehry−stat6250):* How can we clear the output window and the log window?
- Question (kveng−stat6250): Do we need to clear the log window?
- Answer (kveng−stat6250): I tested it. Even we don't clear the log window, we still can correct the errors and resubmit the program.



[Course Textbook Chapter 3, Problem 3]
* *Question (aalshehry−stat6250):* Can we specify more than one “BY variable”?
* *Answer (aalshehry−stat6250):*  You can specify as many BY variables as you wish for example:
```SAS
PROC SORT;
      BY variable-1 ... variable-n;
```
- Question (kveng−stat6250): The error in this problem is that it didn't close the quote in proc print statement?
- Answer (kveng−stat6250): Yes, it's supposed to be 'Recovery Heart Rate' not 'Recovery Heart Rate. 

 
 
[Course Textbook Chapter 3, Problem 4]
* *Question (aalshehry−stat6250):* What will SAS display in the log window when a syntax error detected?
* *Answer (aalshehry−stat6250):*  it will displays the word ERROR, identifies the possible location of the error, and gives an explanation of the error.
- Question (kveng−stat6250): Does SAS have any better system to detect syntax error like with Microsoft Visual studio where it shows immediately if you have made any syntax error on the editor script.


[Course Textbook Chapter 3, Problem 5]
* *Question (aalshehry−stat6250):* What type of errors can SAS detect?
- Question (kveng−stat6250): What is the best way to get better and memorizing syntax?


[Course Textbook Chapter 3, Problem 6]
* *Question (aalshehry−stat6250):* What is an invalid option?
- Question (kveng−stat6250): What does the word "option" refers to in SAS? Is this like a function?


[Course Textbook Chapter 3, Problem 7]
* *Question (aalshehry−stat6250):* What are data errors?
- Question (kveng−stat6250): Does SAS always has to start with "proc" and end with "run"?


[Course Textbook Chapter 3, Problem 10]
* *Question (aalshehry−stat6250):* Is there a situation where “Run;” statement is not required?
- Question (kveng−stat6250): Is it always the case that when we forget to end the DATA step with a RUN statement, the window always displays the message "DATA step running"?


[Course Textbook Chapter 4, Problem 1]
* *Question (aalshehry−stat6250):* How to change the name of a variable(column)?
- Question (kveng−stat6250): What other statements can be controlled in the PRINT procedure in SAS? Like ID, VAR, SUM, etc?


[Course Textbook Chapter 4, Problem 3]
* *Question (aalshehry−stat6250):* How to use WHERE statement to select multiple values from numerical observations?
- Question (kveng−stat6250): Are the text data always in string format which is why we have to use quote? 


[Course Textbook Chapter 4, Problem 4]
* *Question (aalshehry−stat6250):* What will happen if you run a PROC SORT statement without OUT= option?
- Question (kveng−stat6250): What other statements can be controlled in the SORT procedure in SAS? Like NODUPLICATES, NODUPKEY, etc?


[Course Textbook Chapter 4, Problem 7]
* *Question (aalshehry−stat6250):* Is “BY” statement required in “PROC SORT”?
- Question (kveng−stat6250): Why does PROC SORT step generate errors and stops processing with this code?


[Course Textbook Chapter 4, Problem 9]
* *Question (aalshehry−stat6250):* What symbols represent “not equal to” operator in SAS?
- Question (kveng−stat6250): Does "eq" refer to equal sign in SAS?


[Course Textbook Chapter 4, Problem 10]
* *Question (aalshehry−stat6250):* What does “NOOBS” in “PROC PRINT” do?
- Question (kveng−stat6250): Can we customize the PROC PRINT output like choosing which font we want and how big the table is?


[recipe_to_check_for_duplicates (from Week 3 Overview)]
* *Question (aalshehry−stat6250):* Does “DUPOUT” save unique observations without the duplicated rows or does it save only the duplicated observations?
- Question (kveng−stat6250): What does w.r.t mean?


[recipe_for_sorting_data (from Week 3 Overview)]
* *Question (aalshehry−stat6250):* What is the default sorting option? Is it ascending or descending?
- Question (kveng−stat6250): After we sort we make a copy and keep the original file. How and where does the sorted copy file is stored?


[recipe_for_printing_values (from Week 3 Overview)]
* *Question (aalshehry−stat6250):* How to PROC PRINT to print a specific range of data (i.e. rows from 20 to 30)?
- Question (kveng−stat6250): Can we perform some calculation in a PRINT procedure like performing average on the variable then print only the data that are above average?



[Course Textbook Chapter 3, Problem 1]
 Question (aalshehry−stat6250): Why code formatting is important?
 Answer (aalshehry−stat6250): Even though, SAS statements can be written in any format, a consistent layout improve readability and helps understand the program's purpose easily.
 
[Course Textbook Chapter 3, Problem 1]
 Question (lzhao4−stat6250): How to write SAS statements in a most readable format?

[Course Textbook Chapter 3, Problem 2]
 Question (aalshehry−stat6250): How can we clear the output window and the log window?
 
[Course Textbook Chapter 3, Problem 2]
 Question (lzhao−stat6250): After correcting the errors do we have to clear the log window?
	Answer (lzhao4−stat6250):  Clear the messages from the Log window can avoid confusing between old error messages and the new messages. 

[Course Textbook Chapter 3, Problem 3]
 Question (aalshehry−stat6250): Can we specify more than one “BY variable”?
 Answer (aalshehry−stat6250): You can specify as many BY variables as you wish for example:
PROC SORT;
      BY variable-1 ... variable-n;
     
[Course Textbook Chapter 3, Problem 3]
 Question (lzhao4−stat6250): Do SAS able to resolve the PROC step when it appears at the top of the active window?
  
[Course Textbook Chapter 3, Problem 4]
 Question (aalshehry−stat6250): What will SAS display in the log window when a syntax error detected?
 Answer (aalshehry−stat6250): it will displays the word ERROR, identifies the possible location of the error, and gives an explanation of the error.
 
[Course Textbook Chapter 3, Problem 4]
 Question (lzhao4−stat6250): When your Log window displays the word “ERROR” how can you know what’s the error is? 
	Answer (lzhao4−stat6250):  When the Log window displays the word ERROR to mention you that a syntax error is detected, it will identify the possible location of the error and explains the error as well.

[Course Textbook Chapter 3, Problem 5]
 Question (aalshehry−stat6250): What type of errors can SAS detect?
 
[Course Textbook Chapter 3, Problem 5]
 Question (lzhao4−stat6250): Besides the syntax error, can SAS identify other types of error?

[Course Textbook Chapter 3, Problem 6]
 Question (aalshehry−stat6250): What is an invalid option?
 
[Course Textbook Chapter 3, Problem 6]
	Question (lzhao4−stat6250): What should you do when a log message indicates you that an option is not valid or not recognized?

[Course Textbook Chapter 3, Problem 7]
 Question (aalshehry−stat6250): What are data errors?
 
[Course Textbook Chapter 3, Problem 7]
	Question (lzhao4−stat6250): Can a syntax error be caused by misspelling?

[Course Textbook Chapter 3, Problem 10]
 Question (aalshehry−stat6250): Is there a situation where “Run;” statement is not required?
 
[Course Textbook Chapter 3, Problem 10]
	Question (lzhao4−stat6250): What will happen if you miss the RUN statement?
	Answer (lzhao4−stat6250):  The active window will display the message "DATA step running". And the DATA step won’t execute.

[Course Textbook Chapter 4, Problem 1]
 Question (aalshehry−stat6250): How to change the name of a variable(column)?
 
[Course Textbook Chapter 4, Problem 1]
	Question (lzhao4−stat6250): When to use the ID statement?

[Course Textbook Chapter 4, Problem 3]
 Question (aalshehry−stat6250): How to use WHERE statement to select multiple values from numerical observations?

[Course Textbook Chapter 4, Problem 3]
 Question (lzhao4−stat6250): How to format multiple values in one WHERE statement?

[Course Textbook Chapter 4, Problem 4]
 Question (aalshehry−stat6250): What will happen if you run a PROC SORT statement without OUT= option?
 
[Course Textbook Chapter 4, Problem 4]
	Question (lzhao4−stat6250): Any difference when using PROC SORT to sort multiple datasets?

[Course Textbook Chapter 4, Problem 7]
 Question (aalshehry−stat6250): Is “BY” statement required in “PROC SORT”?
 
[Course Textbook Chapter 4, Problem 7]
 Question (lzhao4−stat6250): Can PROC SORT step successfully run without the BY statement?

[Course Textbook Chapter 4, Problem 9]
 Question (aalshehry−stat6250): What symbols represent “not equal to” operator in SAS?
 
[Course Textbook Chapter 4, Problem 9]
	Question (lzhao4−stat6250): Is parentheses required when group data?

[Course Textbook Chapter 4, Problem 10]
 Question (aalshehry−stat6250): What does “NOOBS” in “PROC PRINT” do?
 
[Course Textbook Chapter 4, Problem 10]
 Question (lzhao−stat6250): Any default can refine? step?

[recipe_to_check_for_duplicates (from Week 3 Overview)]
 Question (aalshehry−stat6250): Does “DUPOUT” save unique observations without the duplicated rows or does it save only the duplicated observations?
 
[recipe_to_check_for_duplicates (from Week 3 Overview)]
	Question (lzhao4−stat6250): What step we can do to sort a dataset while simultaneously keeping duplicates?

[recipe_for_sorting_data (from Week 3 Overview)]
 Question (aalshehry−stat6250): What is the default sorting option? Is it ascending or descending?
 
[recipe_for_sorting_data (from Week 3 Overview)]
	Question (lzhao4−stat6250): When sorting in descending order will missing values appear last?

[recipe_for_printing_values (from Week 3 Overview)]
 Question (aalshehry−stat6250): How to PROC PRINT to print a specific range of data (i.e. rows from 20 to 30)?

[recipe_for_printing_values (from Week 3 Overview)]
 Question (lzhao4−stat6250): What’s the specific step to use “Explorer”?


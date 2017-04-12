## Week 3 Quiz Questions and Answers

In order to prepare your Week 3 Quiz submission, please edit ***this*** document to provide substantive questions for each Quiz Problem and SAS Recipe listed below, as well as answers to at least three questions raised.

All edits should conform to GitHub Markdown specifications (https://guides.github.com/features/mastering-markdown/) and should be committed to a branch named "week-3" in your fork of this repo. Then, after all edits have been made/committed, your Week 3 Quiz should be submitted by initiating a pull request using

The instructor will then review the pull request and make comments should further revision be needed. Then, after the contents of the pull request have been finalized without any merge conflicts, the instructor will merge the pull request.

********************************************************************************


[Course Textbook Chapter 3, Problem 1]
* *Question (aalshehry−stat6250):* Why code formatting is important?
* *Answer (aalshehry−stat6250):* Even though, SAS statements can be written in any format, a consistent layout improve readability and helps understand the program's purpose easily.
- Question (yzhu12-stat6250): It's a good idea to begin DATA steps, proc steps, and RUN statements on which side to indent statements within a step?
- Answer (yzhu12-stat6250): On the left side.
- Question (kveng−stat6250): Does the code still work without indenting the statements within step?
- Answer (kveng−stat6250): I tested it. The code still work but it's a good idea indeed to indent the statements for better reading.
-*Question* (lwang30-stat6250) : What are the consequences if you do not end with a *run* statement ?
- Question (yyan11−stat6250): How to write SAS statements?
- Answer (yyan11−stat6250): Although you can write SAS statements in almost any format, a consistent layout enhances readability and helps you understand the program’s purpose. It's a good idea to begin DATA and PROC steps in column one, indent statements within a step, begin RUN statements in column one, include a RUN statement after every DATA step or PROC step. 



[Course Textbook Chapter 3, Problem 2]
* *Question (aalshehry−stat6250):* How can we clear the output window and the log window?
- Question (yzhu12-stat6250): When a Syntex error occurs and SAS displays the word ERROR, what information will it identify?
- Answer (yzhu12-stat6250): It will identify the location of the error and explans the cause of error.
- Question (kveng−stat6250): Do we need to clear the log window?
- Answer (kveng−stat6250): I tested it. Even we don't clear the log window, we still can correct the errors and resubmit the program.
-*Question* (lwang30-stat6250) : What would the log window display if you commit a syntax error ?
- Question (yyan11−stat6250): How to correct the error?
- Answer (yyan11−stat6250): To correct the error: 1. Remove or replace the invalid option, and check your statement syntax as needed. 2. Resubmit the corrected program. 3. Check the SAS log again to make sure there are no other errors. 



[Course Textbook Chapter 3, Problem 3]
* *Question (aalshehry−stat6250):* Can we specify more than one “BY variable”?
* *Answer (aalshehry−stat6250):*  You can specify as many BY variables as you wish for example:
```SAS
PROC SORT;
      BY variable-1 ... variable-n;
```
- Question (yzhu12-stat6250): How to correct the program that contains syntax error?
- Answer (yzhu12-stat6250): You can correct the errors in the Editor window and then resubmit the revised program. You can delete any error-free steps from a revised program before resubmitting it. 
- Question (kveng−stat6250): The error in this problem is that it didn't close the quote in proc print statement?
- Answer (kveng−stat6250): Yes, it's supposed to be 'Recovery Heart Rate' not 'Recovery Heart Rate. 
-*Question* (lwang30-stat6250) : What is the function of the *label* option in the *proc print* statement ? 
 - Question (yyan11−stat6250): What are syntax errors?
- Answer (yyan11−stat6250): Syntax errors, such as misspelled words, generally cause SAS to stop processing the step in which the error occurred.

 
 
[Course Textbook Chapter 3, Problem 4]
* *Question (aalshehry−stat6250):* What will SAS display in the log window when a syntax error detected?
* *Answer (aalshehry−stat6250):*  it will displays the word ERROR, identifies the possible location of the error, and gives an explanation of the error.
- Question (yzhu12-stat6250): What does SAS reflect if you submit a statement that contains an invalid option?
- Answer (yzhu12-stat6250): A log message will appear to notify you that the option is not valid or recognized.
- Question (kveng−stat6250): Does SAS have any better system to detect syntax error like with Microsoft Visual studio where it shows immediately if you have made any syntax error on the editor script.
-*Question* (lwang30-stat6250) : What are considered syntax errors ? Give some examples. 
- Question (yyan11−stat6250): What happened when an error is submitted?
- Answer (yyan11−stat6250):  When a program that contains an error is submitted, messages regarding the problem also appear in the SAS log. When a syntax error is detected, the SAS log displays the word ERROR, identifies the possible location of the error, and gives an explanation of the error.



[Course Textbook Chapter 3, Problem 5]
* *Question (aalshehry−stat6250):* What type of errors can SAS detect?
- Question (yzhu12-stat6250): Will missing RUN statements, missing semicolons, unbalanced quotation marks, and invalid options cause error or just make SAS produce a warning message?
- Question (kveng−stat6250): What is the best way to get better and memorizing syntax?
-*Question* (lwang30-stat6250) : What other kinds of error is log window able to show ?
- Question (yyan11−stat6250): What can help me identify syntax errors?
- Answer (yyan11−stat6250): Some SAS system options, features of the Editor window, and the DATA step debugger can help you identify syntax errors. Other types of errors include data errors, semantic errors, and execution-time errors.



[Course Textbook Chapter 3, Problem 6]
* *Question (aalshehry−stat6250):* What is an invalid option?
- Question (yzhu12-stat6250): What will cause syntax error and what will cause data error? What is the difference between the main causes?
- Question (kveng−stat6250): What does the word "option" refers to in SAS? Is this like a function?
-*Question* (lwang30-stat6250) : What are other ways by which you can detect an invalid option ?
-*Answer* (lwang30-stat6250) : Appropriate use of valid options will be shown in different colors in the enhanced editor window.
- Question (yyan11−stat6250): What should I do when the statement contains an invalid option?
- Answer (yyan11−stat6250): When you submit a SAS statement that contains an invalid option, a log message notifies you that the option is not valid or not recognized. You should recall the program, remove or replace the invalid option, check your statement syntax as needed, and resubmit the corrected program.



[Course Textbook Chapter 3, Problem 7]
* *Question (aalshehry−stat6250):* What are data errors?
- Question (yzhu12-stat6250): When a SAS program that contains errors is submitted, error messages appear in the Log window. How many types of SAS errors can be detected?
- Answer (yzhu12-stat6250): Three types of errors can be detected: syntax, execution-time and data. 
- Question (kveng−stat6250): Does SAS always has to start with "proc" and end with "run"?
-*Question* (lwang30-stat6250) : In what situations do you need to use the quotation mark ?
- Question (yyan11−stat6250): What happened when the data step contains a misspelled keyword?
- Answer (yyan11−stat6250): This is such a common (and easily interpretable) error that SAS produces only a warning message, not an error.



[Course Textbook Chapter 3, Problem 10]
* *Question (aalshehry−stat6250):* Is there a situation where “Run;” statement is not required?
- Question (yzhu12-stat6250): How to look for and replace text using the editor Window?
- Question (kveng−stat6250): Is it always the case that when we forget to end the DATA step with a RUN statement, the window always displays the message "DATA step running"?
-*Question* (lwang30-stat6250) : What are the options that you can use in a data step ?
- Question (yyan11−stat6250): What are data errors?
- Answer (yyan11−stat6250): Data errors that occur when some data values are not appropriate for the SAS statements that are specified in a program.



[Course Textbook Chapter 4, Problem 1]
* *Question (aalshehry−stat6250):* How to change the name of a variable(column)?
- Question (yzhu12-stat6250): You can refine a basic report by sort the data, generate columns totals for numeric variables or?
- Answer (yzhu12-stat6250): You can also select which variables and observations are processed.
- Question (kveng−stat6250): What other statements can be controlled in the PRINT procedure in SAS? Like ID, VAR, SUM, etc?
-*Question* (lwang30-stat6250) : What would the output be if the variable *date* is not specified in the *id* option ?
- Question (yyan11−stat6250): What is the WHERE statement?
- Answer (yyan11−stat6250): In the WHERE statement you can specify any variable in the SAS data set, not just the variables that are specified in the VAR statement. The WHERE statement works for both character and numeric variables.



[Course Textbook Chapter 4, Problem 3]
* *Question (aalshehry−stat6250):* How to use WHERE statement to select multiple values from numerical observations?
- Question (yzhu12-stat6250): In Where statement, Character values must be enclosed in quotation marks and must be in the same case as in the data set, is that true?
- Question (kveng−stat6250): Are the text data always in string format which is why we have to use quote? 
-*Question* (lwang30-stat6250) : What are the functions of parentheses and quotation mark in the *where* option ?
- Question (yyan11−stat6250): How to write the IN operator in the WHERE statement?
- Answer (yyan11−stat6250): In the WHERE statement, the IN operator enables you to select observations based on several values. You specify values in parentheses and separate them by spaces or commas. Character values must be enclosed in quotation marks and must be in the same case as in the data set.



[Course Textbook Chapter 4, Problem 4]
* *Question (aalshehry−stat6250):* What will happen if you run a PROC SORT statement without OUT= option?
- Question (yzhu12-stat6250): In a PROC SORT step, what method should you use for specifying an output data?
- Question (kveng−stat6250): What other statements can be controlled in the SORT procedure in SAS? Like NODUPLICATES, NODUPKEY, etc?
-*Question* (lwang30-stat6250) : Is it okay not to include **work.** in the *out=* option ?
- *Answer* (lwang30-stat6250) : Yes, the work library is the default temperary library in the current SAS session, and a one-level filename is automatically considered to be in the work library.
- Question (yyan11−stat6250): What should I do if I do not want my original data to be sorted?
- Answer (yyan11−stat6250): If you do not want your original data to be sorted permanently, you must create an output data set that contains the data in sorted order. The OUT= option in the PROC SORT statement specifies an output data set. 



[Course Textbook Chapter 4, Problem 7]
* *Question (aalshehry−stat6250):* Is “BY” statement required in “PROC SORT”?
- Question (yzhu12-stat6250): Why does the step PROC SORT fails if it doesn't contain BY statement?
- Question (kveng−stat6250): Why does PROC SORT step generate errors and stops processing with this code?
-*Question* (lwang30-stat6250) : In what other proc step is "BY" statement required ?
- Question (yyan11−stat6250): What can I do when I want to subtotal numeric variables?
- Answer (yyan11−stat6250): To produce subtotals, add both a SUM statement and a BY statement to your PROC PRINT step.



[Course Textbook Chapter 4, Problem 9]
* *Question (aalshehry−stat6250):* What symbols represent “not equal to” operator in SAS?
- Question (yzhu12-stat6250): How can we assign a descriptive label to a variable?
- Answer (yzhu12-stat6250): We use the LABEL statement.
- Question (kveng−stat6250): Does "eq" refer to equal sign in SAS?
-*Question* (lwang30-stat6250) : What rules does SAS follow to perform calculations in the *where* option ?
-*Answer* (lwang30-stat6250) : The rules are the same as that in mathematical calculations. For example, what's in the parentheses will be calculated first. 
- Question (yyan11−stat6250): Which operator could link sequence of expressions into compound expressions?
- Answer (yyan11−stat6250): To link a sequence of expressions into compound expressions, you use logical operators, including AND or &, OR or |.
   


[Course Textbook Chapter 4, Problem 10]
* *Question (aalshehry−stat6250):* What does “NOOBS” in “PROC PRINT” do?
- Question (yzhu12-stat6250): What statements do remain in effect only for the PROC step in which they appear?
- Answer (yzhu12-stat6250): VAR, WHERE and SUM.
- Question (kveng−stat6250): Can we customize the PROC PRINT output like choosing which font we want and how big the table is?
-*Question* (lwang30-stat6250) : Which option can you use to alternate the observation column to a variable that you want to display on the far left side ? 
- Question (yyan11−stat6250): What does a PROC PRINT step list by default?
- Answer (yyan11−stat6250): By default, a PROC PRINT step lists all the observations in a data set. 



[recipe_to_check_for_duplicates (from Week 3 Overview)]
* *Question (aalshehry−stat6250):* Does “DUPOUT” save unique observations without the duplicated rows or does it save only the duplicated observations?
- Question (yzhu12-stat6250): If the out=option is set to anything other than the null data set _null_, then a deduplicated could also be formed- so what other function will cause the same problem?
- Question (kveng−stat6250): What does w.r.t mean?
-*Question* (lwang30-stat6250) : How do we tell from the log window if the dataset we are using has duplicates or not ?
- Question (yyan11−stat6250): Does every data in a SAS dataset have a duplicate?


[recipe_for_sorting_data (from Week 3 Overview)]
* *Question (aalshehry−stat6250):* What is the default sorting option? Is it ascending or descending?
- Question (yzhu12-stat6250): How can we sort numerical variables out of all the variables and assign specific group of values to them using SAS?
- Question (kveng−stat6250): After we sort we make a copy and keep the original file. How and where does the sorted copy file is stored?
-*Question* (lwang30-stat6250) : When several variable appear in the *sort* option, what is the order by which those variables will be sorted by SAS ? Will the variable on the left be sorted first ?
- Question (yyan11−stat6250): What would happen if I do not write anything before “out=”?



[recipe_for_printing_values (from Week 3 Overview)]
* *Question (aalshehry−stat6250):* How to PROC PRINT to print a specific range of data (i.e. rows from 20 to 30)?
- Question (yzhu12-stat6250): In the example, SAS print out var and id as rows and columns. How does "Explorer" look like when it print out and when should we use "Explorer"?
- Question (kveng−stat6250): Can we perform some calculation in a PRINT procedure like performing average on the variable then print only the data that are above average?
-*Question* (lwang30-stat6250) : What other modifications of the data is the *proc print* step able to do ?
- Question (yyan11−stat6250): How to copy SAS data to the system clipboard?



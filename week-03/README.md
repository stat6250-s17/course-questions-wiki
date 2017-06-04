

## Week 3 Quiz Questions and Answers

In order to prepare your Week 3 Quiz submission, please edit ***this*** document to provide substantive questions for each Quiz Problem and SAS Recipe listed below, as well as answers to at least three questions raised.

All edits should conform to GitHub Markdown specifications (https://guides.github.com/features/mastering-markdown/) and should be committed to a branch named "week-3" in your fork of this repo. Then, after all edits have been made/committed, your Week 3 Quiz should be submitted by initiating a pull request using

- the master branch of the stat6250/course_questions_wiki repo as the base fork and

- the week-3 branch of your version of the repo as the head fork.

The instructor will then review the pull request and make comments should further revision be needed. Then, after the contents of the pull request have been finalized without any merge conflicts, the instructor will merge the pull request.

********************************************************************************


[Course Textbook Chapter 3, Problem 1]
- Question (mcardoso3-stat6250):  Why must each SAS statement begin with a DATA or PROC?
* *Question (aalshehry−stat6250):* Why code formatting is important?
* *Answer (aalshehry−stat6250):* Even though, SAS statements can be written in any format, a consistent layout improve readability and helps understand the program's purpose easily.
- Question (yzhu12-stat6250): It's a good idea to begin DATA steps, proc steps, and RUN statements on which side to indent statements within a step?
- Answer (yzhu12-stat6250): On the left side.
- Question (kveng−stat6250): Does the code still work without indenting the statements within step?
- Answer (kveng−stat6250): I tested it. The code still work but it's a good idea indeed to indent the statements for better reading.
- *Question* (lwang30-stat6250) : What are the consequences if you do not end with a *run* statement ?
-Answer (mcardoso3-stat6250):  Not ending statements with run would lead to missing output or results and thus the SAS statement would be incomplete.
- Question (meisenbach-stat6250): Should you place a run statement after every DATA or PROC step?
- Question (nly13-stat6250): Some SAS code has QUIT; after RUN;, does this make a significant difference in procedural steps?
- Answer (nly13-stat6250): QUIT can be optional, as it will end the procedure.
- Question (yyan11−stat6250): How to write SAS statements?
- Answer (yyan11−stat6250): Although you can write SAS statements in almost any format, a consistent layout enhances readability and helps you understand the program’s purpose. It's a good idea to begin DATA and PROC steps in column one, indent statements within a step, begin RUN statements in column one, include a RUN statement after every DATA step or PROC step. 
- Question (rluo-stat6250): In what kind of situation do we use "include" command to open a SAS program?
-Answer (mcardoso3-stat6250):  We can use the INCLUDE command for including a SAS program in the Windows operating environment.
- Question (dlee117−stat6250): Why is it useful to write your SAS programs in a consistent layout?
- Answer (dlee117-stat6250): This is because a consistent layout enhances readability and helps you understand the program’s purpose.
- Question (akumar30−stat6250): Is it necessary to include a RUN statement after every DATA step or PROC step?
- Question (hhu9−stat6250): Is there a std for writing SAS statement?
- Answer (hhu9−stat6250): no, there is many format to write SAS statement.
- Question (aoneill2-stat6250): What happens if there is more than one data step in a program, but only one RUN statement at the end of the program, instead of at the end of each data step?
- Answer (aoneill2-stat6250): A "missing RUN statement" error is generated in the log window.
- Question (yren10-stat6250) : Is that important to follow a standard formating or steps when doing SAS coding?
- Question (cyuan10-stat6250): What purpose does indenting within a step do? Is it more stylistic or functional?
- Answer (cyuan10-stat6250): It is for both purposes. It is importantly to make your code consistent in style so that other users can read and understand it.
- Question (lzhao4−stat6250): How to write SAS statements in a most readable format?



[Course Textbook Chapter 3, Problem 2]
- Question (mcardoso3-stat6250):  Is there a quicker way in editing mistakes made in SAS statements?
* *Question (aalshehry−stat6250):* How can we clear the output window and the log window?
- Question (yzhu12-stat6250): When a Syntex error occurs and SAS displays the word ERROR, what information will it identify?
- Answer (yzhu12-stat6250): It will identify the location of the error and explans the cause of error.
- Question (kveng−stat6250): Do we need to clear the log window?
- Answer (kveng−stat6250): I tested it. Even we don't clear the log window, we still can correct the errors and resubmit the program.
- *Question* (lwang30-stat6250) : What would the log window display if you commit a syntax error ?
- Question (meisenbach-stat6250): What is the difference between the Program Editor and the Editor?
-Answer (mcardoso3-stat6250):  Program Editor can be used to submit and edit SAS programs while the Editor, or "text editor" is just used for running the SAS commands with text.
- Question (nly13-stat6250): R is CAPS sensitive, is there are reason why SAS isn’t?
- Question (yyan11−stat6250): How to correct the error?
- Answer (yyan11−stat6250): To correct the error: 1. Remove or replace the invalid option, and check your statement syntax as needed. 2. Resubmit the corrected program. 3. Check the SAS log again to make sure there are no other errors. 
- Question (rluo-stat6250): What is abbreviation and its function?
- Answer (rluo-stat6250): Abbreviation is marco that inserts one or more lines of text, and it can reduce the length of character string.
- Question (dlee117−stat6250): What are the two ways that you can clear the contents of the SAS programming windows?
- Question (akumar30−stat6250): Can we get a syntax error if data file name is same as SAS Procedure?
- Question (hhu9−stat6250): what is the steps to resubmit SAS program which contains spelling errors?
- Answer (hhu9−stat6250): 1.correct the errors 2.clear the log window 3.resubmit the program 4.check the log window.
- Question (aoneill2-stat6250): Can syntax error messages be generated by logical programming errors that have no actual syntax errors?
- Answer (aoneill2-stat6250): A specific error message is generated in the log window that refers to the particular syntax error made. If a semicolon is omitted, the error message reads, "missing semicolon;" if the syntax error is a missing quotation mark, the error message is "unbalanced quotation marks;" and for another common syntax error of chossing an option that doesn't exist, the error message reads, "invalid option," all of which are self-explanatory. 
- Question (yren10-stat6250) : If i have a error, Will the log message indicates my error comes out all the time, or its depends on what error I had?
-Answer (mcardoso3-stat6250):  When a program containing an error is submitted, messages will appear in the Log window regardless of the type of error.
- Question (cyuan10-stat6250): Do spelling errors really matter beyond standard commands and does the program highlight spelling error?
- Answer (cyuan10-stat6250): No, but it is important you are referring to the correct spelling or variables or command. Also, other readers of your code should be able to understand your coding so correct naming is important.
- Question (lzhao−stat6250): After correcting the errors do we have to clear the log window?
- Answer (lzhao4−stat6250):  Clear the messages from the Log window can avoid confusing between old error messages and the new messages. 



[Course Textbook Chapter 3, Problem 3]
- Question (mcardoso3-stat6250):  Is there any difference to having a space between SAS statements or not?
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
- *Question* (lwang30-stat6250) : What is the function of the *label* option in the *proc print* statement ? 
- Question (meisenbach-stat6250): What state is the program in when there is an unbalanced quote and the rest of the program is fairly short?
-Answer (mcardoso3-stat6250):  SAS is unable to detect the end of the statement in which it occurs, and therefore the statement needs to be cancelled or submitting a line of SAS code.
- Question (nly13-stat6250): Can sets of ‘’ and “ “ be used as interchangeable sets in single program?
- Question (yyan11−stat6250): What are syntax errors?
- Answer (yyan11−stat6250): Syntax errors, such as misspelled words, generally cause SAS to stop processing the step in which the error occurred.
- Question (rluo-stat6250): What is the command that clears the contents of output window, editor window, and log window?
- Question (dlee117−stat6250): What is the benefit of issuing the RECALL command or selected Run -> Recall Last Submit?
- Answer (dlee117-stat6250): This allows you to obtain the statements you just submitted. This allows you to edit your code easily when you run into syntax errors.
- Question (akumar30−stat6250):  How to interpret the error based on log?
-Answer (mcardoso3-stat6250):  When a program is submitted, the Log winow will indicate the error, a misspelled word, misplaced quote, etc. that was not found.  It would then note that SAS stopped processing due to errors and real that no output was processed.
- Question (hhu9−stat6250): why SAS is unable to resolve the PROC step in Q3?
- Answer (hhu9−stat6250):  we should focus that there is a missing quatation mark after 'rate'.
 - Question (aoneill2-stat6250): Is the SUM statement in the code only applied to rows of data that satisfy the WHERE condition that precedes it? In other words, is the SUM statement nested within the WHERE statement?
 - Answer (aoneill2-stat6250): I believe the label option gives the column variable a name, often used to shorten or consolidate the name to make it convenient for printed summary reports, and otherwise to give it a descriptive name.
- Question (yren10-stat6250) : What exactly we use "BY variable" for, and why its a "BY variable"?
- Question (cyuan10-stat6250): What does the aprotrasphe do and how is it used different in the 5th line (before Recovery Heart Rate) vs. the 7th line (before and after I)?
- Question (lzhao4−stat6250): Do SAS able to resolve the PROC step when it appears at the top of the active window?


 
[Course Textbook Chapter 3, Problem 4]
- Question (mcardoso3-stat6250): How many different possible syntax errors are there?
* *Question (aalshehry−stat6250):* What will SAS display in the log window when a syntax error detected?
* *Answer (aalshehry−stat6250):*  it will displays the word ERROR, identifies the possible location of the error, and gives an explanation of the error.
- Question (yzhu12-stat6250): What does SAS reflect if you submit a statement that contains an invalid option?
- Answer (yzhu12-stat6250): A log message will appear to notify you that the option is not valid or recognized.
- Question (kveng−stat6250): Does SAS have any better system to detect syntax error like with Microsoft Visual studio where it shows immediately if you have made any syntax error on the editor script.
- *Question* (lwang30-stat6250) : What are considered syntax errors ? Give some examples. 
- Question (meisenbach-stat6250): How can you prevent syntax errors?
- Answer (meisenbach-stat6250): In the Enhanced Editor, text with syntax error is colored red.
- Question (nly13-stat6250): Is there software that helps fix SAS code, for minor mistakes like spell check?
-Answer (mcardoso3-stat6250):  You can opt for the online Help menu to find information about fixing specific errors, or select SAS on the Web for links to Technical Support and Frequently Asked Questions.
- Question (yyan11−stat6250): What happened when an error is submitted?
- Answer (yyan11−stat6250):  When a program that contains an error is submitted, messages regarding the problem also appear in the SAS log. When a syntax error is detected, the SAS log displays the word ERROR, identifies the possible location of the error, and gives an explanation of the error.
- Question (rluo-stat6250): What is synetx error?
- Answer (rluo-stat6250): Synetx error is SAS language grammar error that happens when program statements do not obey the rules of the SAS language.
- Question (dlee117−stat6250): When debugging your programs, can you just look at the Output window?
-Answer (mcardoso3-stat6250):  Problems with your statement may not be evident in the Output window, so it is important to review the Log before debugging.
- Question (akumar30−stat6250):  What is the use of RECALL command when syntax error occurs? 
- Answer (akumar30−stat6250): It is used to recall the submitted statements from the recall buffer to the Program Editor window, where you can correct the problems.
- Question (hhu9−stat6250): Syntax error will lead to what probelm?
- Answer (hhu9−stat6250):  In SAS, the process step will stop if the syntax is founded, and log window will report the error.
- Question (aoneill2-stat6250): When an error is encountered, does SAS stop running altogether, or does it just stop processing that particular data step?
- Question (yren10-stat6250) : When we got Syntax errors，it will appear as a warning message or a red error sign?
- Answer (yren10-stat6250) : Both would happen, depends on what error you made.
- Question (cyuan10-stat6250): Does SAS indicate where the syntax error occurred?
- Question (lzhao4−stat6250): When your Log window displays the word “ERROR” how can you know what’s the error is? 
- Answer (lzhao4−stat6250):  When the Log window displays the word ERROR to mention you that a syntax error is detected, it will identify the possible location of the error and explains the error as well.



[Course Textbook Chapter 3, Problem 5]
- Question (mcardoso3-stat6250):  What other type of errors are there in SAS aside from syntax errors?
* *Question (aalshehry−stat6250):* What type of errors can SAS detect?
- Question (yzhu12-stat6250): Will missing RUN statements, missing semicolons, unbalanced quotation marks, and invalid options cause error or just make SAS produce a warning message?
-Answer (mcardoso3-stat6250):  Missing any of the above would result into error messages.
- Question (kveng−stat6250): What is the best way to get better and memorizing syntax?
- *Question* (lwang30-stat6250) : What other kinds of error is log window able to show ?
- Question (meisenbach-stat6250): What are other types of errors?
- Question (nly13-stat6250): Does SAS ever glitch where it ignores a syntax error and produces incomplete results?
- Question (yyan11−stat6250): What can help me identify syntax errors?
- Answer (yyan11−stat6250): Some SAS system options, features of the Editor window, and the DATA step debugger can help you identify syntax errors. Other types of errors include data errors, semantic errors, and execution-time errors.
- Question (rluo-stat6250): To save the system resources, what actions can be taken to reduce the usage of recall buffer?
-Answer (mcardoso3-stat6250):  You can save the usage of the recall buffer by using the Program Editor window less often, since you would usually need the buffer when using that window.
- Question (dlee117−stat6250): What is the difference between a syntax error and a data error?
- Answer (dlee117-stat6250): A syntax error occurs when program statements do not conform to the rules of the SAS language while a data error occurs when some data values are not appropriate for the SAS statements that are specified in the program
- Question (akumar30−stat6250): What happens when program statements are not conformed to the rules of the SAS language?
- Answer (akumar30−stat6250):  A syntax error will occur. Details of syntax error can be found in log message.
- Question (hhu9−stat6250): what is the types of errors?
- Answer (hhu9−stat6250):  there are three types of errors. 1.data errors  2.logic errors  3.syntax error.
- Question (aoneill2-stat6250): What kinds of other errors can occur besides syntax erors?
- Question (yren10-stat6250) : What we find and deal with the Syntax errors?
- Answer (yren10-stat6250) : Its a common types of errors, the DATA step debugger can help us identify syntax errors.
- Question (cyuan10-stat6250): What about errors like infinite loop? If we write a code that codes such (like on python), how do we end the loop?
- Question (lzhao4−stat6250): Besides the syntax error, can SAS identify other types of error?



[Course Textbook Chapter 3, Problem 6]
- Question (mcardoso3-stat6250):  What other type of errors are there in SAS aside from syntax errors?
* *Question (aalshehry−stat6250):* What is an invalid option?
- Question (yzhu12-stat6250): What will cause syntax error and what will cause data error? What is the difference between the main causes?
- Question (kveng−stat6250): What does the word "option" refers to in SAS? Is this like a function?
-Answer (mcardoso3-stat6250):  OPTION is a statement that indicates at least one system option needs to be changed.  It is similar to a function, but has its own purpose in regards to changing settings.
- *Question* (lwang30-stat6250) : What are other ways by which you can detect an invalid option ?
- *Answer* (lwang30-stat6250) : Appropriate use of valid options will be shown in different colors in the enhanced editor window.
- Question (meisenbach-stat6250): How should you correct an invalid option?
- Answer (meisenbach-stat6250): After checking for typos, read the error message for suggestions for what a valid option would be in that statement.
- Question (nly13-stat6250): Can you save log data from a SAS session?
- Answer: Yes, you can export the SAS log external files.
- Question (yyan11−stat6250): What should I do when the statement contains an invalid option?
- Answer (yyan11−stat6250): When you submit a SAS statement that contains an invalid option, a log message notifies you that the option is not valid or not recognized. You should recall the program, remove or replace the invalid option, check your statement syntax as needed, and resubmit the corrected program.
- Question (rluo-stat6250): Which kind of error does missing "run" statement belongs to?
-Answer (mcardoso3-stat6250):  Missing a "run" from the statement isn't technically an error, it produces unexpected results.  The book considers it together with syntax errors.
- Question (dlee117−stat6250): How do you resolve an invalid option error?
- Question (akumar30−stat6250):  What happens when SAS statement that contains an invalid option is submitted? Why this happen?
- Answer (akumar30−stat6250): A message will appears in the Log window indicating that the option is not valid or not recognized. An invalid option error occurs when you specify an option that is not valid in a particular statement.
- Question (hhu9−stat6250): How can you realize that you have specified an invalid option?
- Answer (hhu9−stat6250): The log message will remind you.
- Question (aoneill2-stat6250): Can you know you have a data error by just looking at the log window, or by just looking at the output window, or do you need to figure it out from looking at both?
- Question (yren10-stat6250) : Can I submit a SAS statement that contains an invalid option?
- Question (cyuan10-stat6250): In this case, what exactly does option refer to? Is it the output?
- Question (lzhao4−stat6250): What should you do when a log message indicates you that an option is not valid or not recognized?



[Course Textbook Chapter 3, Problem 7]
- Question (mcardoso3-stat6250):  What happend if a syntax error isn't corrected?
-Answer (mcardoso3-stat6250):  SAS would show the error in the Log window and would be unable to display the statement output until the error(s) has been corrected.
* *Question (aalshehry−stat6250):* What are data errors?
- Question (yzhu12-stat6250): When a SAS program that contains errors is submitted, error messages appear in the Log window. How many types of SAS errors can be detected?
- Answer (yzhu12-stat6250): Three types of errors can be detected: syntax, execution-time and data. 
- Question (kveng−stat6250): Does SAS always has to start with "proc" and end with "run"?
-Answer (mcardoso3-stat6250):  No, SAS begins with importing or inserting data with the data name being created.  Data steps can also at times be created without the PROC command.  Though RUN isn't required in a SAS statement, it's required in order to submit and view output.
- *Question* (lwang30-stat6250) : In what situations do you need to use the quotation mark ?
- Question (meisenbach-stat6250): When is SAS able to correct misspelled keywords?
- Question (nly13-stat6250): Does SAS list errors by priority or in order of how they happen?
- Question (yyan11−stat6250): What happened when the data step contains a misspelled keyword?
- Answer (yyan11−stat6250): This is such a common (and easily interpretable) error that SAS produces only a warning message, not an error.
- Question (rluo-stat6250): How does the DATA step debugger work?
-Answer (mcardoso3-stat6250):  The DATA step debugger enables you to issue commands to execute DATA steps and then display the resulting variables' values.  By using this method, you can notice where the logic error is.
- Question (dlee117−stat6250): What type of errors are the following: omitting semicolons, leaving quotation marks unbalanced, specifying invalid options?
- Question (akumar30−stat6250):  Can SAS automatically fix misspelled words in SAS Statement?
- Answer (akumar30−stat6250):  No, You need to fix the program by interpreting the error in log message.
- Question (hhu9−stat6250): Is misspelled keyword valid? 
- Answer (hhu9−stat6250):  It depends on practicalities of SAS language conception.
- Question (aoneill2-stat6250): Are syntax errors always easier to find and fix than data errors?
- Question (yren10-stat6250) : How many types of data errors would occur when we are using SAS?
- Question (cyuan10-stat6250): Does the semicolon indicate that the step is done and what happens if it is not included at the end of each line? Do we always use a semicolon or are there other options?
- Answer (cyuan10-stat6250): The semicolon indicates the end of the line.
- Question (lzhao4−stat6250): Can a syntax error be caused by misspelling?



[Course Textbook Chapter 3, Problem 10]
- Question (mcardoso3-stat6250):  How quick does the active window display a data step running before it becomes too long?
* *Question (aalshehry−stat6250):* Is there a situation where “Run;” statement is not required?
- Question (yzhu12-stat6250): How to look for and replace text using the editor Window?
- Question (kveng−stat6250): Is it always the case that when we forget to end the DATA step with a RUN statement, the window always displays the message "DATA step running"?
- *Question* (lwang30-stat6250) : What are the options that you can use in a data step ?
- Question (meisenbach-stat6250): How can you catch unbalanced quotation marks?
- Answer (meisenbach-stat6250): Quoted text is purple. If the rest of the program is also purple, there is an unmatched quote somewhere in the purple block.
- Question (nly13-stat6250): If you have RUN statements multiple times at the end of a program, will it run faster?
- Answer: No, RUN only needs to be used once.
- Question (yyan11−stat6250): What are data errors?
- Answer (yyan11−stat6250): Data errors that occur when some data values are not appropriate for the SAS statements that are specified in a program.
- Question (rluo-stat6250): Logic error is more harder to detect, and is there other ways to detect it except the DATA step debugger?
- Question (dlee117−stat6250): Is it true that each step in a SAS program is compiled and executed independently from every other step.
- Question (akumar30−stat6250): Can Data Step debugger will be used in other than interactive mode?
- Answer (akumar30−stat6250): No.
- Question (hhu9−stat6250): what is the result except for 'running error' if you do not write a complete statement? 
- Question (aoneill2-stat6250): Besides syntax errors and data errors, what is the third type of error that SAS can detect?
- Answer (aoneill2-stat6250): SAS can detect syntax, data, and execution-time errors.
- Question (yren10-stat6250) : What is the difference between "PROC running" and "DATA step running"?
-Answer (mcardoso3-stat6250):  "PROC running" occurs when there is nothing to indicate the end of a PROC step, while "DATA running" happens when SAS is unable to resolve the DATA step.
- Question (cyuan10-stat6250): In what cases do you write a code that does not end with run?
-Answer (mcardoso3-stat6250):  You can write code without RUN if you plan to continue the DATA step.  You can write lines of code as long as RUN appears at the end of all the statements so that the code can end and be submitted.
- Question (lzhao4−stat6250): What will happen if you miss the RUN statement?
- Answer (lzhao4−stat6250):  The active window will display the message "DATA step running". And the DATA step won’t execute.



[Course Textbook Chapter 4, Problem 1]
- Question (mcardoso3-stat6250):  What does the "where" statement indicate in a PROC Print statement?
-Answer (mcardoso3-stat6250):  The "where" statement specifies a codition for selecting obsservtions.
* *Question (aalshehry−stat6250):* How to change the name of a variable(column)?
- Question (yzhu12-stat6250): You can refine a basic report by sort the data, generate columns totals for numeric variables or?
- Answer (yzhu12-stat6250): You can also select which variables and observations are processed.
- Question (kveng−stat6250): What other statements can be controlled in the PRINT procedure in SAS? Like ID, VAR, SUM, etc?
- *Question* (lwang30-stat6250) : What would the output be if the variable *date* is not specified in the *id* option ?
- Question (meisenbach-stat6250): Is the variable for the ID statement required to be unique?
Question (nly13-stat6250): Do labels exist permanently in a dataset?
-Answer (mcardoso3-stat6250):  LABEL statements can be temporary and they apply only to the PROC step in which it appears.
- Question (yyan11−stat6250): What is the WHERE statement?
- Answer (yyan11−stat6250): In the WHERE statement you can specify any variable in the SAS data set, not just the variables that are specified in the VAR statement. The WHERE statement works for both character and numeric variables.
- Question (rluo-stat6250): How many variables would the PROC PRINT step list in a data set?
- Question (dlee117−stat6250): When producing a list report, if you don’t want to list all of the variables in the data set, can you choose individual variables to show?
- Question (akumar30−stat6250):  What will be happen if a variable in the ID statement also appears in the VAR statement?
- Answer (akumar30−stat6250): The output will contains two columns for that variable.
- Question (hhu9−stat6250): what dose the ID statement mean?
- Answer (hhu9−stat6250): It replaces the Obs column with specified variable.
- Question (aoneill2-stat6250): How many WHERE statements can you include in a PROC step?
-Answer (mcardoso3-stat6250):  You should only have one WHERE statement in a step.  Although you can issue multiple WHERE statements, only the last one is processed.
- Question (yren10-stat6250) : How to change a name of an observation?
- Question (cyuan10-stat6250): How does one format the table output - for example, switch the columns with the rows?
- Question (lzhao4−stat6250): When to use the ID statement?



[Course Textbook Chapter 4, Problem 3]
- Question (mcardoso3-stat6250):  What happens if you enter "where style='RANCH' or 'SPLIT' or 'TWOSTORY';?
* *Question (aalshehry−stat6250):* How to use WHERE statement to select multiple values from numerical observations?
- Question (yzhu12-stat6250): In Where statement, Character values must be enclosed in quotation marks and must be in the same case as in the data set, is that true?
- Question (kveng−stat6250): Are the text data always in string format which is why we have to use quote? 
- *Question* (lwang30-stat6250) : What are the functions of parentheses and quotation mark in the *where* option ?
-Answer (mcardoso3-stat6250):  The parentheses are the first compound expressions to be evaluated in a WHERE statement, and a quotation mark specifies a variable name in the statement.
- Question (meisenbach-stat6250): Does using the IN operatior in the WHERE statement help the code to be more readable?
-Answer (mcardoso3-stat6250): Yes, using the IN operator is a convenient code to input and read for WHERE statements.
Question (nly13-stat6250): Can other types of brackets work for ‘in (content)’ statement, such as [ ]?
- Question (yyan11−stat6250): How to write the IN operator in the WHERE statement?
- Answer (yyan11−stat6250): In the WHERE statement, the IN operator enables you to select observations based on several values. You specify values in parentheses and separate them by spaces or commas. Character values must be enclosed in quotation marks and must be in the same case as in the data set.
- Question (rluo-stat6250): Can WHERE statement control which variables would be printed?
- Question (dlee117−stat6250): When specifying variables with WHERE expressions, what are the two things you must do?
- Question (akumar30−stat6250): What will happen if value of number variable (fee) will be queried as below?
```SAS
where fee in (‘124’,’178’); 
```
- Question (hhu9−stat6250): what is the std spelling of WHERE statement?
- Answer (hhu9−stat6250):  specify values in parentheses and separated by spaces or commas, character value must be enclosed in quatation marks and must be in the same case as in the data set.
- Question (aoneill2-stat6250): Can you use the statement WHERE whatsit IN ('this', 'that', 'theother') as in SQL?
- Question (yren10-stat6250) : What is DATA=option specifies in the codes?
- Answer (yren10-stat6250) : It specifies the data set that you are listing.
- Question (cyuan10-stat6250): Do we always use an apostraphe oppose to quotations?
- Question (lzhao4−stat6250): How to format multiple values in one WHERE statement?



[Course Textbook Chapter 4, Problem 4]
- Question (mcardoso3-stat6250):  Given their similarities in math, how often does SAS create accounting statements?
* *Question (aalshehry−stat6250):* What will happen if you run a PROC SORT statement without OUT= option?
- Question (yzhu12-stat6250): In a PROC SORT step, what method should you use for specifying an output data?
-Answer (mcardoso3-stat6250): After using PROC SORT, you would use PROC PRINT to output the data that you wish.
- Question (kveng−stat6250): What other statements can be controlled in the SORT procedure in SAS? Like NODUPLICATES, NODUPKEY, etc?
- *Question* (lwang30-stat6250) : Is it okay not to include **work.** in the *out=* option ?
- *Answer* (lwang30-stat6250) : Yes, the work library is the default temperary library in the current SAS session, and a one-level filename is automatically considered to be in the work library.
- Question (meisenbach-stat6250): What kind of error do you get if you leave out the BY statement?
Question (nly13-stat6250): Can the process of data to output be reverse, where you use the output to get the original data?
- Question (yyan11−stat6250): What should I do if I do not want my original data to be sorted?
- Answer (yyan11−stat6250): If you do not want your original data to be sorted permanently, you must create an output data set that contains the data in sorted order. The OUT= option in the PROC SORT statement specifies an output data set. 
- Question (rluo-stat6250): What is the function of DESCENDING option?
-Answer (mcardoso3-stat6250):  When sorting a SAS column, DESCENDING lists the variables in order from the highest value at the top to the lowest value at the bottom.
- Question (dlee117−stat6250): What is the general form of a simple PROC SORT step?
- Question (akumar30−stat6250):  Can sort statement in SAS generated the printed output?
- Answer (akumar30−stat6250): No, additional steps will be required to show the printed output.
- Question (hhu9−stat6250): Do you need to name the variables in a VAR statement?
- Answer (hhu9−stat6250): no.
- Question (aoneill2-stat6250): When would you actually want to not use an "OUT=" statement when sorting data?
- Question (yren10-stat6250) : What is the OUT=option specifies in these steps?
- Question (cyuan10-stat6250): For the sort function, is it always alphabetical and how can we reverse it?
- Question (lzhao4−stat6250): Any difference when using PROC SORT to sort multiple datasets?



[Course Textbook Chapter 4, Problem 7]
- Question (mcardoso3-stat6250):  How many variables can you sort under the "PROC SORT" command?
* *Question (aalshehry−stat6250):* Is “BY” statement required in “PROC SORT”?
- Question (yzhu12-stat6250): Why does the step PROC SORT fails if it doesn't contain BY statement?
- Question (kveng−stat6250): Why does PROC SORT step generate errors and stops processing with this code?
- *Question* (lwang30-stat6250) : In what other proc step is "BY" statement required ?
- Question (meisenbach-stat6250): Why does SAS continue execution of a program when a step fails?
Question (nly13-stat6250): Can you have multiple ‘out’ outputs in the same statement if they are sorted by different means?
- Question (yyan11−stat6250): What can I do when I want to subtotal numeric variables?
- Answer (yyan11−stat6250): To produce subtotals, add both a SUM statement and a BY statement to your PROC PRINT step.
- Question (rluo-stat6250): How long will the TITLE and FOOTNOTE statement remain in effect?
-Answer (mcardoso3-stat6250):  The TITLE and FOOTNOTE statements remain in effect until they are modified, cancelled, or the SAS session ends.
- Question (dlee117−stat6250): Does the PROC SORT step permanently sort the input data set?
- Question (akumar30−stat6250): What will happen if no option define for OUT while sorting the dataset in SAS? 
- Answer (akumar30−stat6250):  The PROC SORT step permanently sorts the input data set.
- Question (hhu9−stat6250): If one step of all is wrong, what is the effect?
- Question (aoneill2-stat6250): Does PROC PRINT fail if a BY statement is included?
-Answer (mcardoso3-stat6250):  No, a PROC PRINT step can work if a BY statement is included as long as the variable in the BY statement is specified.
- Question (yren10-stat6250) : What does the BY statement really do in steps？
- Question (cyuan10-stat6250): Why do we have two runs here, can we combine sort and print and have run at the end of both?
- Question (lzhao4−stat6250): Can PROC SORT step successfully run without the BY statement?



[Course Textbook Chapter 4, Problem 9]
- Question (mcardoso3-stat6250):  How similar are SAS tables compared toExcel tables?
* *Question (aalshehry−stat6250):* What symbols represent “not equal to” operator in SAS?
- Question (yzhu12-stat6250): How can we assign a descriptive label to a variable?
- Answer (yzhu12-stat6250): We use the LABEL statement.
- Question (kveng−stat6250): Does "eq" refer to equal sign in SAS?
- *Question* (lwang30-stat6250) : What rules does SAS follow to perform calculations in the *where* option ?
- *Answer* (lwang30-stat6250) : The rules are the same as that in mathematical calculations. For example, what's in the parentheses will be calculated first. 
Question (nly13-stat6250): Does the where statements every use ‘if then’ statements? 
- Question (yyan11−stat6250): Which operator could link sequence of expressions into compound expressions?
- Answer (yyan11−stat6250): To link a sequence of expressions into compound expressions, you use logical operators, including AND or &, OR or |.
- Question (rluo-stat6250): Is formatting data value necessary? Explain why.
- Answer (rluo-stat6250): Formatting data value is necessary because it can make the data values more understandable when they display.
- Question (dlee117−stat6250): Can you use quotation marks when specifying certain character strings, or must you use apostrophes?
- Question (akumar30−stat6250):  Can we do grouping and sorting of variable in SAS together?
-Answer (mcardoso3-stat6250):  Yes, SAS statements an be run when variables are sorted and grouped together.
- Question (hhu9−stat6250): what is the diffirence between '=' and 'eq'?
-Answer (mcardoso3-stat6250):  Both symbols mean equal to in WHERE statements, but other SAS statements such as creating a dataset require an "=" sign.
- Question (aoneill2-stat6250): When are ranges of data appropriate as conditions in a WHERE statement and when not?
- Answer (aoneill2-stat6250) : The rules are the same as that in mathematical calculations. For example, what's in the parentheses will be calculated first.
- Question (yren10-stat6250) : Should we use LABEL option to specific that variable labels appear in output instead of variable names?
- Question (cyuan10-stat6250): Can these equation symbols be used for text as well as numbers?
- Question (lzhao4−stat6250): Is parentheses required when group data?



[Course Textbook Chapter 4, Problem 10]
- Question (mcardoso3-stat6250):  What are all of the requirements for completing a PROC PRINT statement?
-Answer (mcardoso3-stat6250):  The dataset intended to be displayed needs to be specified and you need to insert the "run;" command to successfully complete a PROC PRINT statement.
* *Question (aalshehry−stat6250):* What does “NOOBS” in “PROC PRINT” do?
- Question (yzhu12-stat6250): What statements do remain in effect only for the PROC step in which they appear?
- Answer (yzhu12-stat6250): VAR, WHERE and SUM.
- Question (kveng−stat6250): Can we customize the PROC PRINT output like choosing which font we want and how big the table is?
- *Question* (lwang30-stat6250) : Which option can you use to alternate the observation column to a variable that you want to display on the far left side ? 
- Question (meisenbach-stat6250): What happens if you don’t group conditions with parentheses?
- Question (nly13-stat6250): How do you control the order of results of PROC PRINT?
-Answer (mcardoso3-stat6250):  You can select variables and control the order that they by using a VAR statement in your PROC PRINT step.
- Question (yyan11−stat6250): What does a PROC PRINT step list by default?
- Answer (yyan11−stat6250): By default, a PROC PRINT step lists all the observations in a data set. 
- Question (rluo-stat6250): In what kind of situation do we use permanent labels?
- Question (dlee117−stat6250): What does the Obs column represent and how do you remove the Obs column in your program?
-Answer (mcardoso3-stat6250):  Obs refers to the number of observations in the dataset and you can remove the column by specifying the NOOBS option in the PROC PRINT statement.
- Question (akumar30−stat6250):   Can we change the default properties of PROC PRINT?
- Question (hhu9−stat6250): how to change the default setting of displaying?
- Question (aoneill2-stat6250): It's a good idea to begin DATA steps, proc steps, and RUN statements on which side to indent statements within a step?
- Question (yren10-stat6250) : What does PROC PRINT display， just observation or just variable or both？
- Question (cyuan10-stat6250): What exactly does PROC mean in PROC PRINT?
- Question (lzhao−stat6250): Any default can refine? step?



[recipe_to_check_for_duplicates (from Week 3 Overview)]
- Question (mcardoso3-stat6250):  How is the unique ID formed when checking for duplicates?
* *Question (aalshehry−stat6250):* Does “DUPOUT” save unique observations without the duplicated rows or does it save only the duplicated observations?
- Question (yzhu12-stat6250): If the out=option is set to anything other than the null data set _null_, then a deduplicated could also be formed- so what other function will cause the same problem?
- Question (kveng−stat6250): What does w.r.t mean?
-Answer (mcardoso3-stat6250): w.r.t. is an acronym for "with respect to".
- *Question* (lwang30-stat6250) : How do we tell from the log window if the dataset we are using has duplicates or not ?
- Question (meisenbach-stat6250): What does PROC SORT using  NODUPKEY use to determine what a duplicate row is?
- Answer (meisenbach-stat6250): The criteria is the variables specified in the BY statement. So in the recipe example, if there are rows with the same County_Code, District_Code, and School_Code, they would be considered duplicates.
Question (nly13-stat6250): What would the code be if you wanted to remove all duplicates except for exactly 2 copies of each data point?
- Question (yyan11−stat6250): Does every data in a SAS dataset have a duplicate?
- Question (rluo-stat6250): Is there any situation that two rows contain the same data and both of them are useful data but not duplicated data?
- Question (dlee117−stat6250): What is the purpose of removing duplicate rows in a SAS data set?
-Answer (mcardoso3-stat6250):  Each SAS row is considered to be an observation, so having a duplicate would give us a false number of rows.
- Question (akumar30−stat6250): Can we compare two identical datasets and find the matching records and mismatched records using duplicate data scripts?
- Question (hhu9−stat6250): what has been changed between duplicated dataset and the inicial data?
- Question (aoneill2-stat6250): How can obs numbers be suppressed in a print statement without the use of the noobs option?
- Question (yren10-stat6250) : What is the default settig for the sorting option?
- Question (cyuan10-stat6250): Is this case-sensitive?
- Question (lzhao4−stat6250): What step we can do to sort a dataset while simultaneously keeping duplicates?



[recipe_for_sorting_data (from Week 3 Overview)]
- Question (mcardoso3-stat6250):  Why don't many data analysis tasks require sorting data?
* *Question (aalshehry−stat6250):* What is the default sorting option? Is it ascending or descending?
- Question (yzhu12-stat6250): How can we sort numerical variables out of all the variables and assign specific group of values to them using SAS?
- Question (kveng−stat6250): After we sort we make a copy and keep the original file. How and where does the sorted copy file is stored?
- *Question* (lwang30-stat6250) : When several variable appear in the *sort* option, what is the order by which those variables will be sorted by SAS ? Will the variable on the left be sorted first ?
-Answer (mcardoso3-stat6250):  The variables can be sorted based on ascending or descending order depending on what is specified per the BY statement.
- Question (meisenbach-stat6250): Is it generally a bad idea to overwrite the original dataset with the sorted one?
- Answer (meisenbach-stat6250): Yes, there may be information in the original order of the data.
Question (nly13-stat6250): Instead of sorting by categories, can you sort by length?
- Question (yyan11−stat6250): What would happen if I do not write anything before “out=”?
- Question (rluo-stat6250): Can we sort data in ascending and descending order simultaneously?
- Question (dlee117−stat6250): When sorting data, why should you add the “out=” command?
-Answer (mcardoso3-stat6250):  Sorting data without the "out=" command would override the original data, which is not recommended because the original data may be needed for further interpretation.
- Question (akumar30−stat6250): Can indexing inside dataset will help for faster sorting results?
- Answer (akumar30−stat6250): An index doesn’t guarantee that query performance will be improve.
- Question (hhu9−stat6250): can we sort data by default way, I mean, can we sort data by typing one key? and can we save the same process for next use?
- Question (aoneill2-stat6250): Can multiple sorts be done on more than one variable in a single sorting operation?
- Question (yren10-stat6250) : Will numerical variables and categrical variable sorted together sometimes? what if we needed it seperated for our convenience?
- Question (cyuan10-stat6250): How are numbers sorted? Is it from 0-9 or high to low?
- Question (lzhao4−stat6250): When sorting in descending order will missing values appear last?



[recipe_for_printing_values (from Week 3 Overview)]
- Question (mcardoso3-stat6250):  How much easier is it to use the "ViewTable" option than to to scan content from PROC PRINT? 
* *Question (aalshehry−stat6250):* How to PROC PRINT to print a specific range of data (i.e. rows from 20 to 30)?
- Question (yzhu12-stat6250): In the example, SAS print out var and id as rows and columns. How does "Explorer" look like when it print out and when should we use "Explorer"?
- Question (kveng−stat6250): Can we perform some calculation in a PRINT procedure like performing average on the variable then print only the data that are above average?
- *Question* (lwang30-stat6250) : What other modifications of the data is the *proc print* step able to do ?
- Question (meisenbach-stat6250): What is the purpose of the ID statement within PROC PRINT? Does the index have to be unique?
- Answer (meisenbach-stat6250): “Identifies observations by using the formatted values of the variables that you list instead of by using observation numbers.” - SAS documentation. It does not appear to have to be unique. In the example, County_Name District_Name is not unique.
Question (nly13-stat6250): In the proc print statement, if obs= controls how many observations, can be it set to show specific rows of observations, such as evens or odds?
- Question (yyan11−stat6250): How to copy SAS data to the system clipboard?
-Answer (mcardoso3-stat6250):  Right clicking the selected data and copying to the clipboard would save the data.
- Question (rluo-stat6250): Can the "Explorer" convert the dataset to different file type such as excel?
- Question (dlee117−stat6250): How do you specify which rows will be used when using a PROC PRINT command?
- Question (akumar30−stat6250): Can we directly update the value of a column inside dataset in explorer mode?
- Question (hhu9−stat6250): I see sometimes too many variables lead to dislocation in output, How to deal with it.
- Question (aoneill2-stat6250): Does one always have to sort data BEFORE printing it in the PROC PRINT step?
-Answer (mcardoso3-stat6250):  Data can be read using PROC PRINT without sorting data, but if you wanted to view the sorted data, you would need to PROC SORT before you PROC PRINT.
- Question (yren10-stat6250) : How can we take out a specific part of data seprartely if we needed?
- Question (cyuan10-stat6250): How do we specify certain formating of numbers (rounding) or letters (all case vs. lower case)
- Question (lzhao4−stat6250): What’s the specific step to use “Explorer”?



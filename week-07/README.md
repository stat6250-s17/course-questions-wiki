## Week 7 Quiz Questions and Answers

In order to prepare your Week 7 Quiz submission, please edit ***this*** document to provide substantive questions for each Quiz Problem and SAS Recipe listed below, as well as answers to at least three questions raised.

All edits should conform to GitHub Markdown specifications (https://guides.github.com/features/mastering-markdown/) and should be committed to a branch named "week-7" in your fork of this repo. Then, after all edits have been made/committed, your Week 7 Quiz should be submitted by initiating a pull request using

- the master branch of the stat6250/course_questions_wiki repo as the base fork and

- the week-7 branch of your version of the repo as the head fork.

The instructor will then review the pull request and make comments should further revision be needed. Then, after the contents of the pull request have been finalized without any merge conflicts, the instructor will merge the pull request.

********************************************************************************



[Course Textbook Chapter 10, Problem 2]
- Question (mcardoso3-stat6250):  Does the 'Amount' label cover only numeric variables?
- Question (akumar30−stat6250): Does any variable formatted in the PROC PRINT output statement override the same variable formatted in DATA step?
- Answer (akumar30−stat6250):  Yes, any format option that are done in a PROC PRINT step supersede the data step format assignments for same variable.
* *Question (aalshehry−stat6250):* How to assign the formats permanently?  
* *Answer (aalshehry−stat6250):*  Formats can be assigned temporarily in PROC steps and permanently in DATA steps.
- Question (kveng−stat6250): What is COMMA10 format?
- *Question* (lwang30-stat6250) : Can we take the label and format statement in the data step away as they will be overwritten by "proc print" anyway ?
- Answer (mcardoso3-stat6250):  Though a PROC step can override temporary labels and formats; most SAS procedures automatically use labels and formats without additional statements or options.  Plus, it is good practice to learn multiple ways to create different types of SAS code.
- Question (lzhao4-stat6250): Can temporary labels which assigned in a PROC step override the permanent labels which assigned in a Data step?
- Question (dlee117−stat6250): What is the difference between COMMA6 and COMMA10?
- Question (meisenbach-stat6250): Do temporary labels and formats override permanent labels and formats?
- Answer (meisenbach-stat6250): Yes, they do.
- Question (rluo-stat6250): What is the operation priority of the operators?
- Answer (mcardoso3-stat6250):  The operators are meant to provide a shortened form of code while symbolizing the logical operation it interprets.
- Question (aoneill2-stat6250): Is the formatting in an input statement in a DATA step overridden by a format statement in the DATA step?
- Answer (aoneill2-stat6250): Yes, a Format statement in a DATA step is a permanent formatting assignment.
- Question (yren10-stat6250): What to use for formatiing the variable, how it formatted in the PROC PRINT output?
- Answer (yren10-stat6250):  Formats this variable using the COMMA10. format. 
- Question (nly13-stat6250): What is COMMA10 format?
- Question (hhu9-sta6250):In PROC PRINT, why there is a "." after "comma10"?
- Question (yzhu12-stat6250): Which statement can you use to specify a length before the variable's first value that referred in the DATA step?
- Answer (yzhu12-stat6250): You can use Length statement.



[Course Textbook Chapter 10, Problem 6]
- Question (mcardoso3-stat6250):  How many different ways are there of writing an IF-THEN statement in SAS?
- Question (akumar30−stat6250): What is the order of execution in case of multiple IF-THEN statement?
- Answer (akumar30−stat6250):  Each IF statement is evaluated in order it define, even if the first condition is true. 
* *Question (aalshehry−stat6250):* When we use IF-THEN statement, how to differenciate between variable type?
- Question (kveng−stat6250): How does Count+1 work?
- Answer (kveng−stat6250): The count+1 statement creates the variable count and adds one to each oservation as SAS processes the data step.
- *Question* (lwang30-stat6250) : What types of variable are present in this problem ?
- Answer (mcardoso3-stat6250):  In problem 6, the variable 'Count' is a numeric type, while the variables 'Action' and 'Control' are character types.
- Question (lzhao4−stat6250): What need attention when identify character values in an IF-THEN statement? 
- Answer (lzhao4-stat6250): In IF-THEN statement, you need to enclose character values in quotation mark, and specify them in same case how they exactly appear in the data set. 
- Question (dlee117−stat6250): For Chapter 10 Quiz, problem 6, if both if statements were false, what would be the values of the variables Count and Control?
- Answer (dlee117-stat6250): The value of Count would be 12 and the value of Control would be Go.
- Question (meisenbach-stat6250): When evaluating if a string matches, does case matter?
- Answer (meisenbach-stat6250): Yes, it does.
- Question (rluo-stat6250): What is the differences between using IF statement and using SELECT statement?
- Answer (mcardoso3-stat6250):  An IF statement is based on whether or not a statement is true and the THEN or DELETE statement follows.  A SELECT statement compares the valueof the select-expression with the value of each when-expression.
- Question (aoneill2-stat6250): Are two if statements the same as an if-else statement?
- Answer (aoneill2-stat6250): The effect is the same in terms of the results, but the processing is different. In a series of if statements, every if statement is evaluated by the compiler. In an if-else construction, once there is a condition satisfied as true, the rest of the conditional statements are not evaluated.
- Question (yren10-stat6250): Does lower-case and upper-case matters in IF-THEN statement?
- Answer (yren10-stat6250): Yes, like the case in this question, value 'Ok' is not identical to 'OK'.
- Question (nly13-stat6250): Is it possible to use fuzzy logic?
- Question (hhu9-sta6250):IN IF-THEN statement, is it case-sensitive?  
- Answer (hhu9-sta6250): yes, it is, so we need to be careful about case-sensitive.
- Question (yzhu12-stat6250): Which statement would you use if you need to read and process variables that you don't want to keep in the dataset?
- Answer (yzhu12-stat6250): You need to use DROP= and KEEP= data set options.



[Course Textbook Chapter 10, Problem 7]
- Question (mcardoso3-stat6250):  How long can a new variable be by using the LENGTH statement?
- Question (akumar30−stat6250): What happen if LENGTH statement appears after any other reference to the variable in the DATA step?
- Answer (akumar30−stat6250):  If the variable has been created by another statement, then a later use of the LENGTH statement will not change its length.
* *Question (aalshehry−stat6250):* Why we might want to specify a length for a character variable, rather than let the first assigned value determine the length?
- Question (kveng−stat6250): What is LENGTH statement?
- Answer (kveng−stat6250): You can use a LENGTH statement to specify a length (the number of bytes) for a variable before the first value is referenced elsewhere in the DATA step. For example: LENGTH Type $ 8;
- *Question* (lwang30-stat6250) : What is the consequence of the subsequent observations having longer values than the first observation without the length of the variable being specified in the statement ?
- *Answer* (lwang30-stat6250) : All subsequent values are truncated to the same length as the first observation's value.
- Question (lzhao4−stat6250): How to specify length for variables?
- Answer (mcardoso3-stat6250):  After typing the LENGTH statement, you input the variable(s) names that you want to specify, followed by a $ sign, and then the length value.
- Question (dlee117−stat6250): What does it mean when a value is truncated?
- Answer (dlee117-stat6250): It means if the value is longer than the assigned length, the value is shortened to the assigned length. 
- Question (meisenbach-stat6250): How is variable length determined?
- Question (rluo-stat6250): How many forms does DO statement have? What are they?
- Answer (rluo-stat6250): There are three forms of the DO statement, and they are iterative DO statement, the DO UNTIL statement, and the DO WHILE statement.
- Question (aoneill2-stat6250): What is the difference in programming protocol between declaring the length of a variable implicitly in its first reference in a data set or in an assignment statement and using a LENGTH statement, or are they used interchangeably?
- Answer (mcardoso3-stat6250):  If the length of the variable is referenced first in a DATA step or assignment statement, the values may be truncated, whereas the LENGTH statement would rid the variables from being truncated.
- Question (yren10-stat6250): What determines the length of a variable in the DATA step?
- Answer (yren10-stat6250): It determined by its first reference
- Question (nly13-stat6250): What is LENGTH statement?
- Answer (nly13-stat6250): You can use a LENGTH statement to specify a length for a variable before the first value is referenced elsewhere in the DATA step.
- Question (hhu9-sta6250):What is the difference between LENGTH() and LENGTHC()?
- Answer (hhu9-sta6250): LENGTH() do not count blank in tail.
- Question (yzhu12-stat6250): What is the alternative statement of IF-THEN/ELSE statements when you perform conditional processing?
- Answer (yzhu12-stat6250): You can use SELECT groups.



[Course Textbook Chapter 10, Problem 8]
- Question (mcardoso3-stat6250):  What is the benefit of using ELSE in an IF-THEN statement?
- Answer (mcardoso3-stat6250):  In a IF-THEN statement with ELSE, SAS executes IF-THEN statements until it encounters the first true statment.
- Question (akumar30−stat6250): Which one has better performance in SAS, multiple if then statement or nested if else statement?
- Answer (mcardoso3-stat6250):  Nested IF ELSE statements give a better performance in SAS because you can nest DO groups to any level, though your system has a limit to how many DO statements you can use based on its memory capabilities.
* *Question (aalshehry−stat6250):* What is the benifit of using ELSE in IF-THEN statement?
* *Answer (aalshehry−stat6250):* SAS wont evaluate the code that included within ELSE statement unless all previous IF's are not meet the condition which can save some resources.
- Question (kveng−stat6250): Can we write multiple ELSE statements to specify a series of mutally exclusive conditions?
- Answer (kveng−stat6250): Yes, the ELSE statement must immediately follow the IF-THEN statement in your program.
- *Question* (lwang30-stat6250) : What is the advantage of using the IF-THEN/ELSE statement ?
- *Answer* (lwang30-stat6250) : When the dataset is large, IF-THEN/ELSE statement can process much faster than multiple IF-THEN statement in which all the observations are evaluated one by one.
- Question (lzhao4−stat6250): How to use ELSE statements with the IF-THEN statement?
- Answer (lzhao4-stat6250): You should write ELSE statement immediately follow the IF-THEN statement. Additionally, you can use multiple ELSE statements when needed.  
- Question (dlee117−stat6250): Why is it more efficient to construct IF-THEN/ELSE statements with conditions of decreasing probability?
- Question (meisenbach-stat6250): How does SAS evaluate a stand alone character variable in a condition?
- Question (rluo-stat6250): Can DO statement be used in the PROC?
- Question (aoneill2-stat6250): Can if statements be viewed as program control structures?
- Answer (aoneill2-stat6250): Yes, especially in conjunction with if-else structures. If statements are all evaluated, and this makes a difference in the number of statements that can be evaluated or result in variables being assigned values. 
- Question (yren10-stat6250): How many  ELSE statements we can write in one statement(IF-THEN)?
- Answer (mcardoso3-stat6250):  You can execute a group of ELSE statements as a unit in one IF-THEN statement with no specific limit.
- Question (nly13-stat6250): What is the benefit of using ELSE in IF-THEN statement?
- Answer (nly13-stat6250): Using IF-THEN statements without the ELSE statement causes SAS to evaluate all IF-THEN statements. Using IF-THEN statements with the ELSE statement causes SAS to execute IF-THEN statements until it encounters the first true statement. 
- Question (hhu9-sta6250):Why in SAS, we should type first "else" parallel with "if" in first column?
- Question (yzhu12-stat6250):  How can you assign an initial value to a variable whose value is assigned by a sum statement?
- Answer (yzhu12-stat6250): You can use RETAIN statement.



[Course Textbook Chapter 10, Problem 9]
- Question (mcardoso3-stat6250):  Is there a limit to including how many LENGTH statements you type in SAS?
- Question (akumar30−stat6250): What is the ideal position to define the length statement so that the program can run successfully?
- Answer (akumar30−stat6250):  The LENGTH statement should appears before any other reference to the variable in the DATA step.
* *Question (aalshehry−stat6250):* In case of using LENGTH statement to assign a length to a character variable, where it supposed to be located?
* *Answer (aalshehry−stat6250):* It must be the first reference to the character variables in the DATA step. Therefore, the best position in the DATA step for a LENGTH statement is immediately after the DATA statement.
- Question (kveng-stat6250): In which order should the LENGTH statement appears in the DATA step?
- *Question* (lwang30-stat6250) : Where should we place the LENGTH statement in order to let variable "Type" have a length of 10 ?
- Question (lzhao4−stat6250): Does LENGTH statement can change the length of an existing variable?
- Question (dlee117−stat6250): Can you specify a new LENGTH of a variable after the first value for the variable is referenced?
- Question (meisenbach-stat6250): Where should the LENGTH statement be?
- Answer (meisenbach-stat6250): Before any references to the variable in the DATA step.
- Question (rluo-stat6250): Can DO statement nest IF or SELECT statement?
- Answer (mcardoso3-stat6250):  Yes, you can nest DO groups to any level or any statement.
- Question (aoneill2-stat6250):  Are statements concerning length of variable data in a data step permanent or non-permanent assignments?
- Answer (mcardoso3-stat6250):  Statements concerning length of variable data are permanent because any later statements regarding length will not change the length of the variable.
- Question (yren10-stat6250): What determines the length of a new variable?
- Question (nly13-stat6250): How does the length statement work with newly created variables?
- Question (hhu9-sta6250):Where should we place LENGTH statement in?
- Answer (hhu9-sta6250): LENGTH statement should be placed before any other reference to the variable in the DATA step.
- Question (yzhu12-stat6250): How can you perform many statements as part of the conditional action?
- Answer (yzhu12-stat6250): You can use DO groups.



[Course Textbook Chapter 10, Problem 10]
- Question (mcardoso3-stat6250):  What are the possible errors that you can commit while writing a LENGTH, INFILE, or IF-THEN statement?
- Question (akumar30−stat6250): Can we create a new calculated variable in data step which doesn’t exists in keep statement?
* *Question (aalshehry−stat6250):* What are the  differences between the DROP & KEEP statements and the DROP= & KEEP= data set options?
- Answer (mcardoso3-stat6250):  No, you can't use the DROP and KEEP statements in SAS procedure, or PROC steps.  They apply to all all output data sets named in the DATA statement.
- Question (kveng−stat6250): Can we drop or keep variables in the PROC steps?
- *Question* (lwang30-stat6250) : What is the difference between the "DROP or KEEP" statement and the "DROP= or KEEP=" statement ?
- Question (lzhao4−stat6250): What’s the difference between DROP statement and DROP= data set option? 
- Question (dlee117−stat6250): Do you have to provide a label and format for a variable?
- Question (meisenbach-stat6250): Can you use DROP or KEEP statements in a PROC step?
- Answer (meisenbach-stat6250): No, you cannot.
- Question (rluo-stat6250): Is there any situations that cannot use the DO, SELECT, and IF statements but alternatives?
- Answer (mcardoso3-stat6250):  Yes, you can use the ELSE statement to specify an alternative action to be performed if the other statements fail.
- Question (aoneill2-stat6250): Can a variable be dropped in a data step in which it has been used for a calculation without producing an error?
- Answer (aoneill2-stat6250): No. When you drop a variable in a DATA step but not in the DATA statement itself, it removes the variable and its data from being accessed by the DATA step.
- Question (yren10-stat6250):  Can we use DROP or KEEP statements in PROC steps?
- Question (nly13-stat6250): What are the possible errors that can occur while writing a LENGTH, INFILE, or IF-THEN statement?
- Question (hhu9-sta6250):In which time we should use KEEP= instead of keep?
- Question (yzhu12-stat6250): Why the LENGTH statement has to be before any other reference to the variable in the DATA step?



[Course Textbook Chapter 11, Problem 1]
- Question (mcardoso3-stat6250):  Is it required to have both the DROP and KEEP data set options within the same statement?
- Answer (mcardoso3-stat6250):  If certain variables are not referenced, you can use the DROP= option in the SET statement, which doesn't require yo to use the KEEP= option.
- Question (akumar30−stat6250): Does drop statement delete the variables from its original dataset?
- Answer (mcardoso3-stat6250):  Yes, the function of DROP is to exclude variables from your data set.
* *Question (aalshehry−stat6250):* If you use more than one data set option or a combination of data set options and statements, what is the order that SAS applying for drops, keeps, and renames variables?
- Question (kveng−stat6250): How does KEEP=option in the SET statement work?
- *Question* (lwang30-stat6250) : What are the statements where we can use the "DROP= or KEEP=" option ?
- Question (lzhao4−stat6250): Where to specify the KEEP= data set option?
- Answer (mcardoso3-stat6250):  We specify the KEEP= data set option in either the DATA statement or the SET statement.
- Question (dlee117−stat6250): What is the difference between using DROP= and KEEP= statements in the DATA step vs the SET step?
- Question (meisenbach-stat6250): Which dataset is specified by the DATE statement?
- Answer (meisenbach-stat6250): The new dataset. The dataset to be read from is assigned by the SET statement.
- Question (rluo-stat6250): Can mutiple datasets be created by using the SET statement?
- Question (aoneill2-stat6250): Do variables referenced in a data file in a set statement within a DATA step need to be explicitly kept or dropped?
- Question (yren10-stat6250): If age <= 40 and group not equal 2, will age and group appears in new data set? 
- Question (nly13-stat6250): If there are more than one WHEN statement that has a true ‘when’ expression, how many WHEN statements will be used?
- Answer (nly13-stat6250): Only the first WHEN statement will be read.
- Question (hhu9-sta6250):when we use drop statement, where are the variables that be droped?
- Answer (hhu9-sta6250): They are still in PDV.
- Question (yzhu12-stat6250): If there are more than one WHEN statement that has a true when-expression, how many WHEN statements will be used?
- Answer (yzhu12-stat6250): Only the first WHEN statement is used.



[Course Textbook Chapter 11, Problem 2]
- Question (mcardoso3-stat6250):  Will the new data set being created always come before the previous data set has ben specified?
- Question (akumar30−stat6250):  Can Data and set option have same dataset name to override the existing dataset?
- Answer (mcardoso3-stat6250):  Yes, the DATA and SET option can both be read from the same, single dataset.
* Question (aalshehry−stat6250): What kind of IF logical operators can we use within a DATA step?
- Question (kveng−stat6250): Can we drop ordertime from the SET statement in this case?
- Answer (mcardoso3-stat6250):  Yes, in problem 2, we can drop the variable 'ordertime' since the DROP= option is valid in a SET statement.
- *Question* (lwang30-stat6250) : What is the basic criterion to be based on in order to figure out the correct place where the "DROP= or KEEP=" option should be located ? 
- Question (lzhao4−stat6250): Where to specify the DROP= data set option? 
- Question (dlee117−stat6250): What does “july” mean when referencing the data set Orders with this statement: july.orders?
- Question (meisenbach-stat6250): What happens if you DROP a variable in the SET statement and then reference it?
- Question (rluo-stat6250): After dropping some variables, how can we add them again?
- Question (aoneill2-stat6250): When creating an output file in a DATA statement, is there an error if no variables are explicitly kept or dropped?
- Question (yren10-stat6250): Does DROP= drops all the stuff from the variable? or we may use ‘if’ make some change？
- Question (nly13-stat6250): What is the basic criteria in order to figure out the placement of the "DROP= or KEEP=" option?
- Question (hhu9-sta6250):How to understand "compile-time only statement"?
- Question (yzhu12-stat6250): When you create a new variable in SAS, what will happen if the variable has been created by another statement instead of the LENGTH statement?
- Answer (yzhu12-stat6250): Then a later use of the LENGTH statement will not change its size.



[Course Textbook Chapter 11, Problem 3]
- Question (mcardoso3-stat6250):  Why is there no 'middle' variable in each BY group?
- Question (akumar30−stat6250): Can we specify multiple variables together in BY statement for multiple group observations for processing at same time?
* *Question (aalshehry−stat6250):* Can we use multiple BY statements within a DATA step?  
* *Answer (aalshehry−stat6250):* Only one BY statement can accompany each SET statement in a DATA step.
- Question (kveng−stat6250): Where does the FRIST and LAST temporary varaibles are stored?
- Answer (mcardoso3-stat6250):  The temporary variables would be stored in the program data vector.
- *Question* (lwang30-stat6250) : What are the values of each FIRST. and LAST. when the BY-Group processing is used for multiple variables ?
- Answer (mcardoso3-stat6250):  For multiple variables, FIRST for each variable is set to 1 at the first occurrence of a new value or the primary variable, while a change in the value of a primary BY variable forces LAST to equal 1 for the secondary BY variables.
- Question (lzhao4−stat6250): When using the BY statement with the SET statement, does the data step creates two temporary variables for each BY variable?
- Answer (lzhao4-stat6250): Yes, one is the named FIRST.VARIABLE and another is named LAST.VARIABLE. They are identifying the first and the last observation in each BY group.
- Question (dlee117−stat6250): What are the values in FIRST.variable and LAST.variable?
- Answer (dlee117-stat6250): Their values are either 1 for the first and last observations respectively or 0 for any other observation.
- Question (meisenbach-stat6250): What kind of variable are FIRST. and LAST.?
- Answer (meisenbach-stat6250): FIRST. and LAST. are temporary variables.
- Question (rluo-stat6250): What is the statement that prevents continuous looping?
- Answer (rluo-stat6250): The STOP statement can prevent continuous looping.
- Question (aoneill2-stat6250): How can the sort process help create subtotals for variables by which the data set is sorted by?
- Answer (aoneill2-stat6250): The sort process creates "first." and "last." extenuated variables that can be used with the by-variable name appended to them and used in if statements to determine whether you have hit the first of a list or the last of a list to begin an operation or to end one.
- Question (yren10-stat6250): When we're using the BY statement with the SET statement, what the DATA step creates？
- Question (nly13-stat6250): Is there any other type of comparisons that goes before logical comparison in SAS?
- Question (hhu9-sta6250):what does FIRST.andLAST.mean?
- Answer (hhu9-sta6250): it identify the first and last observations in each BY statement.
- Question (yzhu12-stat6250): Is there any other type of logical comparison in SAS?



[Course Textbook Chapter 11, Problem 8]
- Question (mcardoso3-stat6250):  How would continous looping happen when submitting a program?
- Answer (mcardoso3-stat6250):  The POINT= option reads only specified observations, so SAS can't read an end-of-file indicator as it would if the file was read sequentially.
- Question (akumar30−stat6250): What is the major difference between END=options and POINT= options statement?
- Answer (mcardoso3-stat6250):  POINT= specifies a temporary numeric variable that contains the observation number of the observation to read, while END= creates a numeric variable whose value is used to detect just the last observation.
* *Question (aalshehry−stat6250):* What is the value of the END= variable when random access is used?
- Question (kveng−stat6250): What does "if last" referred to in this statement?
- *Question* (lwang30-stat6250) : In what situations do we want to use the END= option to manipulate the data ?
- Question (lzhao4−stat6250): When to use an END= option in the SET statement?
- Question (dlee117−stat6250): Is “LAST” a SAS defined statement or is it a variable?
- Answer (mcardoso3-stat6250):  LAST is a temporary variable along with FIRST.
- Question (meisenbach-stat6250): Why does the “if last” statement do?
- Question (rluo-stat6250): What statement is used for detecting the end of a data?
- Answer (rluo-stat6250): THe END statement can be used for detecting the end of a data.
- Question (aoneill2-stat6250): How can you create an end-of-file marker when reading in a list of values?
- Answer (aoneill2-stat6250): You can solve the problem by assigning a value to the end of file variable, "end".
- Question (yren10-stat6250): What does END= option do in the program?
- Question (nly13-stat6250): Is there a maximum number of set statements allowed?
- Question (hhu9-sta6250):In what situation we should add end=eof in set statement?
- Question (yzhu12-stat6250): What's the alternative statement that works the same as the ELSE statement in SAS?



[Course Textbook Chapter 11, Problem 9]
- Question (mcardoso3-stat6250):  How soon would observations be revealed when the DATA step has been executed?
- Question (akumar30−stat6250):  What is the content of program data vector after compilation phase is completed of data step?
- Answer (akumar30−stat6250):  The descriptor portion of the new SAS Data set is created after compilation phase of data step is complete. There are no observations because the DATA step has not yet executed.
* *Question (aalshehry−stat6250):* What are the added values of using program data vector (PDV) compared to the other database platforms?
- Question (kveng−stat6250): What is program data vector (PDV)?
- Answer (mcardoso3-stat6250):  The program data vector is the temporary area of computer memory where SAS builds a SAS data set one observation at a time.
- *Question* (lwang30-stat6250) : What are the values of each variable in the PDV at the beginning of the execution phase ?
- *Answer* (lwang30-stat6250) : The values of each variable are set to missing at the beginning of the execution phase.
- Question (lzhao4−stat6250): In compilation phase, how SAS reading an existing data set with the SET statement?
- Question (dlee117−stat6250): If variables are created in the DATA step, what happens to them during the compilation phase?
- Answer (mcardoso3-stat6250):  When the variables are created in the DATA step, they are added to the PDV.
- Question (meisenbach-stat6250): How are the variables for the Program Data Vector determined?
- Answer (meisenbach-stat6250): From the SET statement and from any variable created in the DATA steps
- Question (rluo-stat6250): What are the two phases of reading the data sets?
- Answer (rluo-stat6250): Compilation phase and exxcution phase.
- Question (aoneill2-stat6250): How can the program data vector and its population of values as the program steps through the code be useful in debugging a program?
- Question (yren10-stat6250): What does PDV do in the DATA step processing?
- Question (nly13-stat6250): What are the values of each variable in the PDV at the beginning of the execution phase ?
- Question (hhu9-sta6250):What signs the end of DATA precess?
- Answer (hhu9-sta6250):RUN statement
- Question (yzhu12-stat6250): Why you can't use DROP or KEEP statements in PROC steps?



[basic_recipe_for_combining_data_vertically (from Week 7 Overview)]
- Question (mcardoso3-stat6250):  Why would a length statement need to appear when creating wider character variable?
- Question (akumar30−stat6250): If there are two data set having same data structure but variable names and position are different? Can we combine this dataset vertically by using additional keep and retain statement?
* *Question (aalshehry−stat6250):* What is the main advantage of using "IN=" Statement?
- Question (kveng−stat6250): When combining the data vertically, can we sort and combine the data at the same time?
- *Question* (lwang30-stat6250) : What is an example of the expansion of the dataset by applying both two indicator variables that has been defined in the "set" statement ?
- Question (lzhao4−stat6250): From the recipe we know that IN= dataset option can be used in conjunction with if or else conditioning. Beside this, what else we can do with IN= dataset option?
- Question (dlee117−stat6250): What is the function of the SAS statement DO?
- Question (meisenbach-stat6250): How does the IN= data set option work?
- Answer (meisenbach-stat6250): Syntax: IN=variable, This names the new variable whose value indicates whether the input data set contributed data to the current observation.
- Question (rluo-stat6250): How many indicator variables should be created when combining the data sets?
- Question (aoneill2-stat6250): How can one create useful data structures to evaluate business logic in combining data files vertically?
- Answer (aoneill2-stat6250): An "in" (for "in-file") variable is created along with a datasource variable that holds a reference to the file. The in-variable then gets assigned a value of 1 if the data comes from the indicated file and 0 if not, which can further be used in a business analysis scheme regarding the file through the use of the datasource variable assignment.
- Question (yren10-stat6250): If we are combining data vertically or horizontally, what does missing observations or variables will show in result or output when combining them?
- Answer (mcardoso3-stat6250):   Missing observations will show as a missing value in the output when datasets are combined.
- Question (nly13-stat6250): In what situation that the indicator variables are not eligible?
- Question (hhu9-sta6250): whats the advantages of SAS language over SQL language?
- Question (yzhu12-stat6250): In what situation can indicator variables not be used?
- Answer (mcardoso3-stat6250):  An indicator variable can be created for symmetry since it can be useful in future expansions of the data step, but it's not necessary and therefore unused.



[optional: adv_recipe_for_combining_data_vertically (from Week 7 Overview)]
- Question (mcardoso3-stat6250):  What would be the best option to combine datasets in SAS?
- Question (akumar30−stat6250): How to rewrite concat statement using pro sql?
- Answer (akumar30−stat6250):  The two data sets can be combined vertically, or concatenated, in a DATA step by naming them both in a single SET statement. Here is the example where two dataset 'one' and 'two' are being concatenated:
```SAS
DATA concat; 
SET one two; 
RUN;
*The equivalent SQL statement of concatenated is;
CREATE TABLE concat AS
SELECT *
FROM one
OUTER UNION CORRESPONDING
SELECT *
FROM two
;
```
* *Question (aalshehry−stat6250):* How to sort the selected data using PROQ SQL?
- *Question* (lwang30-stat6250) : What are the advantages and disadvantages of using "proc sql" rather than a data step ?
- Answer (mcardoso3-stat6250):  With PROC SQL, combining data sets requires less complex code and columns can be created at the same time a data set is being queried.  However, it is limited by available RAM and can take significantly longer to create data sets in an equivalent DATA step.
- Question (meisenbach-stat6250): What does the AS keyword do in a PROC SQL SELECT statement?
- Answer (meisenbach-stat6250): Syntax: value AS variable. The AS keyword allows you to set the value of a new variable.
- Question (nly13-stat6250): Do the advantages of PROC sql out weight the disadvantage of memory?
- Question (yzhu12-stat6250): The statement "union all corr" can include all the columns with the corresponding names, does that mean the missing columns are skipped automatically and the remained ones are matched up with each other precisely?
- Answer (mcardoso3-stat6250):  Yes, since "union all corr" includes all columns with corresponding names, missing columns are skipped and duplicate columns can be created to match the two data sets.



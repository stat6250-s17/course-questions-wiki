## Week 5 Quiz Questions and Answers

In order to prepare your Week 5 Quiz submission, please edit ***this*** document to provide substantive questions for each Quiz Problem and SAS Recipe listed below, as well as answers to at least three questions raised.

All edits should conform to GitHub Markdown specifications (https://guides.github.com/features/mastering-markdown/) and should be committed to a branch named "week-5" in your fork of this repo. Then, after all edits have been made/committed, your Week 5 Quiz should be submitted by initiating a pull request using

- the master branch of the stat6250/course_questions_wiki repo as the base fork and

- the week-5 branch of your version of the repo as the head fork.

The instructor will then review the pull request and make comments should further revision be needed. Then, after the contents of the pull request have been finalized without any merge conflicts, the instructor will merge the pull request.

********************************************************************************



[Course Textbook Chapter 5, Problem 1]
- Question (akumar30−stat6250): What is the significance of aggregate storage location in SAS?
* *Question (aalshehry−stat6250):* What is the general form of using FILENAME statement?
* *Answer (aalshehry−stat6250):* FILENAME fileref 'filename';
- Question (yyan11−stat6250): Can I using a FILENAME Statement referencing a Raw Data File?
- Answer (yyan11−stat6250): Yes, when reading raw data, you can use the FILENAME statement to point to the location of the external file that contains the data. Just as you assign a libref by using a LIBNAME statement, you assign a fileref by using a FILENAME statement.
- Question (meisenbach-stat6250): What error message do you get if you do not use the quote marks?
- Question (dlee117−stat6250): To read a raw data file, what four instructions must 	the DATA step provide to SAS?
- Answer (dlee117-stat6250): The location or name of the external text file, the name for the new SAS data set, the reference that identifies the external file, and a description of the data values to be read.
- Question (kveng−stat6250): Is there a FILEREF statement in SAS?
- Answer (kveng−stat6250): I don't think there is such a statement in SAS. Fileref is a name that you associate with an external file. It's not a statement in SAS. 
- *Question* (lwang30-stat6250): In what situations should the single quotation marks be eliminated when we are referencing the location of the file ?
- Question (aoneill2−stat6250): Can you access files in your SAS user file without a LIBREF statement?



[Course Textbook Chapter 5, Problem 2]
- Question (akumar30−stat6250):  Can I reference multiple external file with a fileref that points to an aggregate storage location?
- Answer (akumar30−stat6250):  Yes, The * and ? wildcards can be used in either the external file name. Wildcards are supported for input only in the FILENAME and INFILE statements, and in member name syntax (aggregate syntax). Also allfiles command can be used to reads all files in the current working directory.
* *Question (aalshehry−stat6250):* Why does Fileref statement lose its information after ending SAS session?
- Question (yyan11−stat6250): How to view active filerefs?
- Answer (yyan11−stat6250): Like librefs, the filerefs currently defined for your SAS session are listed in the SAS Explorer window. To view details about a referenced file, double-click File Shortcuts (or select File Shortcuts and then Open from the pop-up menu). Then select View→Details. Information for each file (name, size, type, and host path name) is listed.
- Question (meisenbach-stat6250): Can you save filenames permanently?
- Question (dlee117−stat6250): What is the difference between the LIBNAME and FILENAME statements?
- Answer (dlee117-stat6250): LIBNAME references a SAS library while FILENAME references an external file.
- Question (kveng−stat6250): Can we set the Filerefs to permanently in effect?
- *Question* (lwang30-stat6250): What are the other global statements except *libname* and *filename* ?
- Question (aoneill2−stat6250): Do explicit fileref statements using full pathnames render the use of a LIBREF statement unneccessary?



[Course Textbook Chapter 5, Problem 6]
- Question (akumar30−stat6250): Can I assign a static text or conditional text (e.g.  Yes or No) to a variable in input statement?  	    
- Answer (akumar30−stat6250):  Yes, using SAS expression new variable can be created to calculate measures or display value based on certain conditions.
* *Question (aalshehry−stat6250):* In INPUT statement, what do the numbers after the variables represent? 
* *Answer (aalshehry−stat6250):* INPUT variable <$> startcol-endcol . . .; The dollar sign ($) identifies the variable type as character (if the variable is numeric, then nothing appears here), startcol represents the starting column for this variable, and endcol represents the ending column for this variable.
- Question (yyan11−stat6250): Can I use the INPUT statement to describing the data?
- Answer (yyan11−stat6250): The INPUT statement describes the fields of raw data to be read and placed into the SAS data set.
- Question (meisenbach-stat6250): What happens when you change the order of the variables in the INPUT statement?
- Question (dlee117−stat6250): When using the INPUT statement to describe the fields of raw data to be read and placed into the SAS data set, what does the dollar sign ($) do?
- Answer (dlee117-stat6250): It identifies the variable type as character.
- Question (kveng−stat6250): What is the $ sign use din the input statement?
- Answer (kveng−stat6250): the dollar sign ($) identifies the varaible taype as character with start collumn and end column for the variable.
- *Question* (lwang30-stat6250): In the *input* statement, what kind of variable do we use the dollar sign for ?
- *Answer* (lwang30-stat6250): The dollar sign is used to input a character variable.
- Question (aoneill2−stat6250): When SAS encounters invalid data in a file that is run in a data step using an infile statement, does SAS stop processing the program?
- Answer (aoneill2−stat6250): No, SAS continues to run, even though an invalid data error is generated.



[Course Textbook Chapter 5, Problem 7]
- Question (akumar30−stat6250): Can we changed the order of existing raw dataset file permanently using SAS?
* *Question (aalshehry−stat6250):* What information should be provided to use INPUT statement?
- Question (yyan11−stat6250): How to write an INPUT statement?
- Answer (yyan11−stat6250): For each field of raw data that you want to read into your SAS data set, you must specify the following information in the INPUT statement: a valid SAS variable name; a type (character or numeric); a range (starting column and ending column).
- Question (meisenbach-stat6250): What happens when you read in try to read in a numeric field as character or vice versa?
- Question (dlee117−stat6250): If you wanted to name a new variable NewBalance, when do you need to specify it in the exact case you wanted stored and when can you specify the name in uppercase, lowercase, or mixed case?
- Answer (dlee117-stat6250): It identifies the variable type as character.
- Question (kveng−stat6250): Is there a better way of creating a table from raw data instead of using column input? Can we just specify the column name and SAS will know the column numbers automatically?
- *Question* (lwang30-stat6250): By what means can we check a comprehensive discription of a dataset, such as each variable's data type?
- *Answer* (lwang30-stat6250): By using a *proc contents* statement, we are able to output the discriptors of a dataset including the data types for each variable.
- Question (aoneill2−stat6250): What kind of error is generated when data is read in using an infile statement with incorrect column numbers?



[Course Textbook Chapter 5, Problem 8]
- Question (akumar30−stat6250): How to delete a column in SAS output?
- Answer (akumar30−stat6250):  Use DROP in the data option to delete a column in the SAS output.
* *Question (aalshehry−stat6250):* When you re-define the value of a variable, can you restore the orginal values?
- Question (yyan11−stat6250): How to evaluate the expression when a variable name appears on both sides of the equal sign?
- Answer (yyan11−stat6250): When a variable name appears on both sides of the equal sign, the original value on the right side is used to evaluate the expression. The result is assigned to the variable on the left side of the equal sign.
- Question (meisenbach-stat6250): How do you use comparison and logical operators with variables?
- Answer (meisenbach-stat6250): With an IF-THEN statement (e.g. IF age > 40 AND gender ‘F’ THEN test = ‘T’)
- Question (dlee117−stat6250): When you use more than one arithmetic operator in an expression, how do you control the order of operations?
- Question (kveng−stat6250): Does this method permanent re-define the values of the varaible?
- Answer (kveng-stat6250): Yes, it will.
- *Question* (lwang30-stat6250): What is the order for arithmetic operator's processing ?
- Question (aoneill2−stat6250): Must assignment statements for operations on variables use explicit mention of the variable, or can it be implied, such as count=+1?



[Course Textbook Chapter 6, Problem 1]
- Question (akumar30−stat6250): Can we increase the default size of output buffer in SAS?
- Answer (akumar30−stat6250):  Yes using BUFSIZE option we can specifies the size of a permanent buffer page for an output SAS data set.
* *Question (aalshehry−stat6250):* After the compilation phase is completed, what SAS compiler will create next?
* *Answer (aalshehry−stat6250):* The descriptor portion of the new data set will be created.
- Question (yyan11−stat6250): What are program data vectors?
- Answer (yyan11−stat6250): The program data vector contains two automatic variables that can be used for processing but which are not written to the data set as part of an observation. _N_ counts the number of times that the DATA step begins to execute. _ERROR_ signals the occurrence of an error that is caused by the data during execution. 
- Question (meisenbach-stat6250): The descriptor portion is created at the end of the compilation phase. How does the program know how many observations there are before the data is read?
- Question (dlee117−stat6250): What are the two automatic variables that can be used for processing contained in the program data vector?
- Question (kveng−stat6250): What is compilation phase?
- Answer (aoneill2−stat6250): During the compilation phase, each statement is scanned for syntax errors.
- *Question* (lwang30-stat6250): What are the two phases of a data step process ?
- Question (aoneill2−stat6250): What heppens during the execution phase of a SAS DATA step?



[Course Textbook Chapter 6, Problem 2]
- Question (akumar30−stat6250): How to detect and fix semantic error in SAS?
- Answer (akumar30−stat6250):  All error details can be found in log windows, using error description you can analyze the error and correct the code.
* *Question (aalshehry−stat6250):* What type of syntax errors does SAS can recognize? 
- Question (yyan11−stat6250): What is syntax checking?
- Answer (yyan11−stat6250): During the compilation phase, SAS also scans each statement in the DATA step, looking for syntax errors. 
- Question (meisenbach-stat6250): What are incorrect values and format?
- Answer (meisenbach-stat6250): Incorrect values refers to the values of variables. Incorrect format probably refers to the data format not matching what you expect (character when you are expecting numeric)
- Question (dlee117−stat6250): What happens when SAS finds a syntax error during the compilation phase?
- Answer (aoneill2−stat6250): If an error is found during the compilation phase, SAS tries to interpret it if possible.
- Question (kveng−stat6250): What is data step?
- *Question* (lwang30-stat6250): What commands can we use to detect invalid data in SAS ?
- *Answer* (lwang30-stat6250): *proc print, proc freq, proc means* are the statements that we can use to detect invalid data in SAS. 
- Question (aoneill2−stat6250): What happens if SAS cannot interpret a syntax error during compliation phase?



[Course Textbook Chapter 6, Problem 3]
- Question (akumar30−stat6250): Which command can be used in data step to execute multiple time for each record in the input file?
* *Question (aalshehry−stat6250):* How to change/redirect the defult Data statem?
- Question (yyan11−stat6250): How SAS Processes Programs if the DATA step compiles successfully?
- Answer (yyan11−stat6250): If the DATA step compiles successfully, then the execution phase begins. During the execution phase, the DATA step reads and processes the input data. The DATA step executes once for each record in the input file, unless otherwise directed.
- Question (meisenbach-stat6250): What would cause the DATA step to stop before excuting once per record? 
- Question (dlee117−stat6250): A raw data file with 20 records on the file executes how many times during the DATA step?
- Question (kveng−stat6250): Can we execute more than once per each record in the input file?
- *Question* (lwang30-stat6250): Which phase of the data step process works like a loop ?
- Question (aoneill2−stat6250): Can more than one input file be read in in a single DATA step?



[Course Textbook Chapter 6, Problem 4]
- Question (akumar30−stat6250): Can we change the default value of _N_ and _ERROR_ at the beginning of the execution phase?
* *Question (aalshehry−stat6250):* What is the function of _N_ and _ERROR_?
- Question (yyan11−stat6250): What is initializing variables?
- Answer (yyan11−stat6250): The remaining variables are initialized to missing. Missing numeric values are represented by periods, and missing character values are represented by blanks.
- Question (meisenbach-stat6250): Why does SAS initalize the variables in the data vector to missing at the beginning of the execution step?
- Question (dlee117−stat6250): If I was missing the item name, what symbol would represent this missing value?
- Question (kveng−stat6250): Why do the remaining variables are initialized to missing?
- *Question* (lwang30-stat6250): What are the values of _N_ , _ERROR_ , and the remaining variables before the second observation starts to be read ? 
- Question (aoneill2−stat6250): How can you use the assignment of values to variables in a SAS file during execution to track the execution of a DATA step?



[Course Textbook Chapter 6, Problem 5]
- Question (akumar30−stat6250):  Can we find the number of errors in execution step by analyzing the value of _ERROR_ in SAS?
* *Question (aalshehry−stat6250):* What values can _ERROR_ takes?
- Question (yyan11−stat6250):What is the value of the automatic variable _ERROR_ when the observation that contains any error?
- Answer (yyan11−stat6250): _ERROR_ signals the occurrence of an error that is caused by the data during execution. The default value is 0, which means there is no error. When one or more errors occur, the value is set to 1.
- Question (meisenbach-stat6250): When there is an error, does the DATA step stop executing?
- Answer (meisenbach-stat6250): No, the value where the error occured will be missing and the program continues to read data.
- Question (dlee117−stat6250): Why does the value of the automatic variable _ERROR_ only go from 0 to 1?
- Question (kveng−stat6250): How do we know if we have multiple erros if the system only show the value of 1 despite having multiple erros?
- *Question* (lwang30-stat6250): Is **_ERROR_** in the execution phase a dummy variable ?
- Question (aoneill2−stat6250): Does the value of the automatic variable _ERROR_ equal the number of actual errors encountered?



[Course Textbook Chapter 6, Problem 6]
- Question (akumar30−stat6250): if there are independent SAS code, can we change the SAS execution processing from sequential to parallel for faster processing?
* *Question (aalshehry−stat6250):* Why SAS assigns variables in the program data vector to missing before each execution of the DATA step?
- Question (yyan11−stat6250): What is the value of the automatic variable _N_?
- Answer (yyan11−stat6250): _N_ counts the number of times that the DATA step begins to execute.
- Question (meisenbach-stat6250): Why would the _ERROR_ variable be reset to 0 at the beginning of an iteration of the DATA step?
- Question (dlee117−stat6250): Why are the values of variables in the program data vector created in programming statements reset to missing at the end of the DATA step?
- Question (kveng−stat6250): Why the values of varaible creating in programming statements are re-set to missing in the program data vector?
- *Question* (lwang30-stat6250): At which phase is the descriptor portion of the data written in a data step process ? 
- Question (aoneill2−stat6250): Are values of the variables set to missing as part of the initial execution step of a DATA step, or does that happen at the beginning of the compilation phase?



[basic_recipe_for_creating_analytic_datasets (from Week 5 Overview)]
- Question (akumar30−stat6250): Can we create new dataset from existing multiple dataset in SAS data step? (without using proc sql)
* *Question (aalshehry−stat6250):* What is the difference between "Retain" and "Keep" in DATA statement?
- Question (yyan11−stat6250): Is there a limit number of specific rows or columns data that will be the subset of an SAS data set?
- Question (meisenbach-stat6250): What does the SET statement in the DATA step do?
- Answer (meisenbach-stat6250): It tells SAS to read an observation from one or more SAS data sets. If more than one data set name appears in the SET statement, the resulting output data set is a concatenation of all the data sets that are listed. 
- Question (dlee117−stat6250): Even though it looks redundant to have the same variables in both the RETAIN and KEEP statements, why is this necessary?
- Question (kveng−stat6250): Is there any statement that would incorporate both RETAIN and KEEP into a single process?
- *Question* (lwang30-stat6250): Except the data step, is there any other statement where the program data vector (PDV) will be used in SAS ?
- Question (aoneill2−stat6250): Can a retain statement be sufficient in itself, given that it specifies the order of the existing variables?
- Answer (aoneill2−stat6250): No, a retain statement must always be accompanied by either a "keep" or "drop" statement. The retain statement only specifies order, wherease the "keep' or "drop" statement determines the existence of the variables in the program.



[optional: adv_recipe_for_creating_analytic_datasets (from Week 5 Overview)]
- Question (akumar30−stat6250):  can we create new variable using proc sql statement in SAS?
- Answer (akumar30−stat6250):  Yes, using LABEL = option we can create new variable using SAS proc sql statement.
* *Question (aalshehry−stat6250):* In SQL inquery, what is the substitue of proc means and proc freq?
- Question (meisenbach-stat6250): Does using PROC SQL create a different data structure than using the DATA statement? If I want to sort data using PROC SQL, does the data need to be read into a TABLE?
- Question (dlee117−stat6250): Even though PROC SQL requires less code (since it uses the select clause to combine the functions of the RETAIN and KEEP statements), when are the times when you want to use PROC SQL and when are the times you would want to use the regular DATA step?
- Question (kveng−stat6250): What happens if we don't sepecify the program to quit at the end?
- *Question* (lwang30-stat6250): If *prog glm* is an interactive proc, why can we still run other statement without enclosing *proc glm* by a "quit" ? 
- Question (aoneill2−stat6250): What statement can be left out of the recipe without affecting its output?
- Answer (aoneill2−stat6250): The WHERE statement can be omitted.
- Question (aoneill2−stat6250): What is the PROC step used in the advanced recipe for creating analytic datasets?
- Answer (aoneill2−stat6250): The PROC SQL step is used.
- Question (aoneill2−stat6250): What is one advantage of a PROC SQL step?
- Answer (aoneill2−stat6250): The PROC SQL statement uses les code that a DATA step.
- Question (aoneill2−stat6250): How do you end a PROC SQL step?
- Answer (aoneill2−stat6250): A PROC SQL step must end with a QUIT statement.



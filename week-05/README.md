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
- Question (yzhu12-stat6250): How do you reference the raw data file before you can read your raw data?
- Answer (yzhu12-stat6250): You must create a fileref.
- Question (nly13-stat6250): Is there a limit to the types of files we can associate to?
- Question (rluo-stat6250): What is a raw data file, and what are its features?
- Question (aoneill2−stat6250): Can you access files in your SAS user file without a LIBREF statement?
- Question (cyuan10−stat6250): Raw data files can be converted to SAS datasets. Can we also use filename statement to convert a SAS dataset into a different software file like excel?
- Question (yren10−stat6250): How can we assign a fileref?
- Answer (yren10−stat6250): You assign a fileref by using a FILENAME statement in the same way that you assign a libref by using a LIBNAME statement.
- Question (mcardoso3-stat6250):  Is there an easier way to input the data set other than to include the data file in the SAS statement?
- Question (lzhao4−stat6250): Reference the raw data file by creating a fileref is an essential step to read the row data?



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
- Question (yzhu12-stat6250): What do you must specify in the INPUT statement when you read each field of raw data into your SAS data set?
- Answer (yzhu12-stat6250): You must specify a valid SAS variable name, a type, a starting column, and if necessary, an ending column.
- Question (nly13-stat6250): Will Fileref be in effect if you save your SAS session?
- Answer (nly13-stat6250): No, it ends when the SAS session ends.
- Question (rluo-stat6250): In order to read the raw data file, what DATA steps must be provided?
- Question (aoneill2−stat6250): Do explicit fileref statements using full pathnames render the use of a LIBREF statement unneccessary?
- Question (cyuan10−stat6250): How do we make filerefs permanent? 
- Question (yren10−stat6250): LIBNAME statement remain effect utill?
- Answer (yren10−stat6250): Same as FILENAME remain in effect until you change them, cancel them, or end your SAS session.
- Question (mcardoso3-stat6250):  What is the benefit to having a fileref?
- Answer (mcardoso3-stat6250):  Filerefs temporarily point to a storage location for data and they reference external files.  It is a good function to have if you need to find a specific dataset that has been saved.
-	Question (lzhao4−stat6250):  Do Filerefs perform the same function as librefs?
-	Answer (lzhao4−stat6250): Both LIBNAME and FILENAME statements are global.  Librefs and filerefs remain in effect until you change them, cancel them, or end your SAS session.



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
- Question (yzhu12-stat6250): What’s the reason to use the keyword _NULL_ when the goal of your SAS program is to create a raw data file and not a SAS data set?
- Answer (yzhu12-stat6250): It allows the power of the DATA step without actually creating a SAS data set. A SET statement specifies the SAS data set that you want to read from.
- Question (nly13-stat6250): In the INPUT statement, what does the $ represent?
- Answer (nly13-stat6250): The $ is used to label variables as characters.
- Question (rluo-stat6250): Besides we correct the invalid data in the data file, is there other ways that can help us deal with the invalid data without modify them?
- Question (aoneill2−stat6250): When SAS encounters invalid data in a file that is run in a data step using an infile statement, does SAS stop processing the program?
- Answer (aoneill2−stat6250): No, SAS continues to run, even though an invalid data error is generated.
- Question (cyuan10−stat6250): How is the code format determined for the input line where we have 2 variables in the first line then 2 more variables in the second line? Can we have all four in the same line or each individually? 
- Answer (cyuan10−stat6250): This was done for stylistic reasons. The line code ends with the semi-colon.
- Question (yren10−stat6250): In the INPUT statement, does variable name we assign will show exactly in data set?
- Answer (yren10−stat6250): Yes, when we write an INPUT statement, we need to specify the variable names exactly as we want them to appear in the SAS data set.
- Question (mcardoso3-stat6250):  How much differently, if at all, would variables be inputed in an INFILE statement as opposed to a DATALINES  statement?
-	Question (lzhao4−stat6250): Do INPUT statement reads raw data from instream data lines into a SAS data set?



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
- Question (yzhu12-stat6250): How can we fix the data that’s not have standard character and numeric values to fit in the column input?
- Question (nly13-stat6250): When assigning the range for characters, what happens if there is overlap? Example 1-3 and 3-6.
- Question (rluo-stat6250): Does assignment statement begin with the keyword?
- Answer (rluo-stat6250): Assignment statement does not begin with the keyword.
- Question (aoneill2−stat6250): What kind of error is generated when data is read in using an infile statement with incorrect column numbers?
- Question (cyuan10−stat6250): In the example, are ending "0" such as 33.990 the same as 33.99 read as the same in SAS?
- Answer (cyuan10−stat6250): Yes. These two values are equal.
- Question (yren10−stat6250): What is the rule when we are using $ in INPUT statement, should we use it between variable name and numbers?
- Question (mcardoso3-stat6250):  What happens if the input variables are entered out of order?
- Answer (mcardoso3-stat6250):  If the variables are entered out of order, the columns will have inaccurate names and therefore the dataset would appear confusing to interpret.
-	Question (lzhao4−stat6250):  Can you use column input to read fields in any order?



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
- Question (yzhu12-stat6250): How to modify existing values or to create new variables?
- Answer (yzhu12-stat6250): You can use an assignment statement in any DATA step.
- Question (nly13-stat6250): Will income=income+income; generate the same result?
- Question (rluo-stat6250): Does the subsetting IF statement have iteration function?
- Question (aoneill2−stat6250): Must assignment statements for operations on variables use explicit mention of the variable, or can it be implied, such as count=+1?
- Question (cyuan10−stat6250): Is there a difference in output if we use 2 vs. 2.00? Would our results end with decimals?
- Question (yren10−stat6250): Does expression has to be on the left of the equal sign?
- Question (mcardoso3-stat6250):  What other variables can define values as percentages besides Income?
-	Question (lzhao4-stat6250): Do you have to including the variable name on the right side of the equal sign when re-define a value?



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
- *Question* (lwang30-stat6250): What are the two phases of a data step process ?
- Question (yzhu12-stat6250): What’s the usage of the DATA statement step?
- Answer (yzhu12-stat6250): They are used to check for syntax errors, such as invalid options or misspellings.
- Question (nly13-stat6250): What types of variables can be used in a data vector?
- Question (rluo-stat6250): What are the two phases of SAS DATA step process?
- Answer (rluo-stat6250): Compilation phase and the execution phase.
- Question (aoneill2−stat6250): What heppens during the execution phase of a SAS DATA step?
- Question (cyuan10−stat6250): What can prevent or block the descriptors during the compilation phrase?
- Answer (cyuan10−stat6250): Syntax errors may prevent the compilation phrase from moving forward successfully.
- Question (yren10−stat6250): So where is the data set descriptor created?
- Question (mcardoso3-stat6250):  What is the purpose of the compilation phase in SAS?
-	Question (lzhao4-stat6250): Do observation written at the compilation phase?
-	Answer (lzhao4-stat6250): Observations are not written until the execution phase.



[Course Textbook Chapter 6, Problem 2]
- Question (akumar30−stat6250): How to detect and fix semantic error in SAS?
- Answer (akumar30−stat6250):  All error details can be found in log windows, using error description you can analyze the error and correct the code.
* *Question (aalshehry−stat6250):* What type of syntax errors does SAS can recognize? 
- Question (yyan11−stat6250): What is syntax checking?
- Answer (yyan11−stat6250): During the compilation phase, SAS also scans each statement in the DATA step, looking for syntax errors. 
- Question (meisenbach-stat6250): What are incorrect values and format?
- Answer (meisenbach-stat6250): Incorrect values refers to the values of variables. Incorrect format probably refers to the data format not matching what you expect (character when you are expecting numeric)
- Question (dlee117−stat6250): What happens when SAS finds a syntax error during the compilation phase?
- Question (kveng−stat6250): What is data step?
- *Question* (lwang30-stat6250): What commands can we use to detect invalid data in SAS ?
- *Answer* (lwang30-stat6250): *proc print, proc freq, proc means* are the statements that we can use to detect invalid data in SAS. 
- Question (yzhu12-stat6250): What will cause syntax error?
- Answer (yzhu12-stat6250): Missing semicolons, misspelled keywords, and invalid options will cause syntax error.
- Question (nly13-stat6250): Why do format errors not count as a syntax error?
- Question (rluo-stat6250): What are the two automatic variables the program data vector contain?
- Question (aoneill2−stat6250): What happens if SAS cannot interpret a syntax error during compliation phase?
- Answer (aoneill2−stat6250): If an error is found during the compilation phase, SAS tries to interpret it if possible.
- Question (cyuan10−stat6250): Is there a memory limitation with the input buffer?
- Question (yren10−stat6250): Does syntax checks the values of variables or the correctness of formats?
- Question (mcardoso3-stat6250):  If incorrect values and formats in each statement in the DATA step aren't considered syntax errors, what are they considered as?
-	Question (lzhao4-stat6250): Do Syntax checking able to verify the values of variables or the correctness of formats?



[Course Textbook Chapter 6, Problem 3]
- Question (akumar30−stat6250): Which command can be used in data step to execute multiple time for each record in the input file?
* *Question (aalshehry−stat6250):* How to change/redirect the defult Data statem?
- Question (yyan11−stat6250): How SAS Processes Programs if the DATA step compiles successfully?
- Answer (yyan11−stat6250): If the DATA step compiles successfully, then the execution phase begins. During the execution phase, the DATA step reads and processes the input data. The DATA step executes once for each record in the input file, unless otherwise directed.
- Question (meisenbach-stat6250): What would cause the DATA step to stop before excuting once per record? 
- Question (dlee117−stat6250): A raw data file with 20 records on the file executes how many times during the DATA step?
- Question (kveng−stat6250): Can we execute more than once per each record in the input file?
- *Question* (lwang30-stat6250): Which phase of the data step process works like a loop ?
- Question (yzhu12-stat6250): In what situation that SAS can’t interpret the error?
- Question (nly13-stat6250): Can a Data step be executed more than once for each record in the input file?
- Question (rluo-stat6250): What does the descriptor portion of the data set include?
- Question (aoneill2−stat6250): Can more than one input file be read in in a single DATA step?
- Question (cyuan10−stat6250): Can variables names be changed permanently in the data file as part of the the DATA step so that we're correctly issues with the file rather than the code?
- Question (yren10−stat6250): Will the DATA step executes more than once in any siutation? 
- Question (mcardoso3-stat6250):  Where and how often would DATA steps be executed if otherwise directed?
-	Question (lzhao4−stat6250): How the DATA step work?



[Course Textbook Chapter 6, Problem 4]
- Question (akumar30−stat6250): Can we change the default value of _N_ and _ERROR_ at the beginning of the execution phase?
* *Question (aalshehry−stat6250):* What is the function of _N_ and _ERROR_?
- Question (yyan11−stat6250): What is initializing variables?
- Answer (yyan11−stat6250): The remaining variables are initialized to missing. Missing numeric values are represented by periods, and missing character values are represented by blanks.
- Question (meisenbach-stat6250): Why does SAS initalize the variables in the data vector to missing at the beginning of the execution step?
- Question (dlee117−stat6250): If I was missing the item name, what symbol would represent this missing value?
- Question (kveng−stat6250): Why do the remaining variables are initialized to missing?
- *Question* (lwang30-stat6250): What are the values of _N_ , _ERROR_ , and the remaining variables before the second observation starts to be read ? 
- Question (yzhu12-stat6250): What does numeric and blanks represent, respectively?
- Answer (yzhu12-stat6250): Numeric represents missing numeric values and blanks represent missing character values.
- Question (nly13-stat6250): Can you extract the _N_ value?
- Question (rluo-stat6250): Can the execution phase only input a portion of the dataset?
- Question (aoneill2−stat6250): How can you use the assignment of values to variables in a SAS file during execution to track the execution of a DATA step?
- Question (cyuan10−stat6250): Is there a way to add more "descriptors" to the Descriptor Portion beyond was is currently in the output?
- Question (yren10−stat6250): What are missing values will represent in output?
- Question (mcardoso3-stat6250):  Why are the values of the remaining variables at the start of the execution phase set to "missing"?
-	Question (lzhao4-stat6250): How to represent missing variables in SAS statements?



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
- Question (yzhu12-stat6250): What’s the difference between the errors that raised during the compilation phrase and execution phrase?
- Question (nly13-stat6250): Can you extract the _ERROR_ value?
- Question (rluo-stat6250): How to clean the data?
- Answer (rluo-stat6250): Use IF-THEN statement or IF-THEN-ELSE statement to valid the data.
- Question (aoneill2−stat6250): Does the value of the automatic variable _ERROR_ equal the number of actual errors encountered?
- Question (cyuan10−stat6250): Will ERRORS help us identify exactly how many errors there are in the Data step?
- Question (yren10−stat6250): What does default _ERROR_ equal to zero actually means? 
- Question (mcardoso3-stat6250):  When would it be necessary to reset the automatic variable_ERROR_ to 0?
-	Question (lzhao4-stat6250): What the default value of ERROR is?
-	Answer (lzhao4-stat6250): The ERROR variable acts like a binary switch whose value is 0 if no errors exist in the DATA step, or 1 if one or more errors exist.



[Course Textbook Chapter 6, Problem 6]
- Question (akumar30−stat6250): if there are independent SAS code, can we change the SAS execution processing from sequential to parallel for faster processing?
* *Question (aalshehry−stat6250):* Why SAS assigns variables in the program data vector to missing before each execution of the DATA step?
- Question (yyan11−stat6250): What is the value of the automatic variable _N_?
- Answer (yyan11−stat6250): _N_ counts the number of times that the DATA step begins to execute.
- Question (meisenbach-stat6250): Why would the _ERROR_ variable be reset to 0 at the beginning of an iteration of the DATA step?
- Question (dlee117−stat6250): Why are the values of variables in the program data vector created in programming statements reset to missing at the end of the DATA step?
- Question (kveng−stat6250): Why the values of varaible creating in programming statements are re-set to missing in the program data vector?
- *Question* (lwang30-stat6250): At which phase is the descriptor portion of the data written in a data step process ? 
- Question (yzhu12-stat6250): What kind of errors will raise when you use a wrong method to test your programs?
- Question (nly13-stat6250): Why are variables in the program data vector created in programming statements reset to missing at the end of the DATA step?
- Question (rluo-stat6250): What is the function of the PUT Statement?
- Question (aoneill2−stat6250): Are values of the variables set to missing as part of the initial execution step of a DATA step, or does that happen at the beginning of the compilation phase?
- Question (cyuan10−stat6250): Why are ERROR and the program data vector reset to zero at the end of the data step? 
- Question (yren10−stat6250): What is the default at the end of the DATA step will do?
- Question (mcardoso3-stat6250):  What does an iteration of the DATA step mean?
- Answer (mcardoso3-stat6250):  An iteration is a loop or cycle of execution, which repetitively executes statements to read data values and create observations one by one.
-	Question (lzhao4-stat6250): What different actions will occur at the beginning and the end of the DATA step?



[basic_recipe_for_creating_analytic_datasets (from Week 5 Overview)]
- Question (akumar30−stat6250): Can we create new dataset from existing multiple dataset in SAS data step? (without using proc sql)
* *Question (aalshehry−stat6250):* What is the difference between "Retain" and "Keep" in DATA statement?
- Question (yyan11−stat6250): Is there a limit number of specific rows or columns data that will be the subset of an SAS data set?
- Question (meisenbach-stat6250): What does the SET statement in the DATA step do?
- Answer (meisenbach-stat6250): It tells SAS to read an observation from one or more SAS data sets. If more than one data set name appears in the SET statement, the resulting output data set is a concatenation of all the data sets that are listed. 
- Question (dlee117−stat6250): Even though it looks redundant to have the same variables in both the RETAIN and KEEP statements, why is this necessary?
- Question (kveng−stat6250): Is there any statement that would incorporate both RETAIN and KEEP into a single process?
- *Question* (lwang30-stat6250): Except the data step, is there any other statement where the program data vector (PDV) will be used in SAS ?
- Question (yzhu12-stat6250): How can we tell an error that is from execute phrase or compile phrase?
- Question (nly13-stat6250): If retain and keep have to be the same, why isn’t there a single statement that is simplified to do both? 
- Answer (nly13-stat6250): The simplified version would be proc sql, uses less code for same result, however it is limited by memory.
- Question (rluo-stat6250): How can we actually use program data vector function?
- Question (aoneill2−stat6250): Can a retain statement be sufficient in itself, given that it specifies the order of the existing variables?
- Answer (aoneill2−stat6250): No, a retain statement must always be accompanied by either a "keep" or "drop" statement. The retain statement only specifies order, wherease the "keep' or "drop" statement determines the existence of the variables in the program.
- Question (cyuan10−stat6250): Can we create a single SAS data set from mulitple external raw data sets?
- Question (yren10−stat6250): How we ise "Retain" exactly, and what it does in DATA statement?
- Question (mcardoso3-stat6250):  How much practice would it typically take for one to fully understand the programming data vector in SAS?
-	Question (lzhao4-stat6250): What different aspects do retain and keep modify with?



[optional: adv_recipe_for_creating_analytic_datasets (from Week 5 Overview)]
- Question (akumar30−stat6250):  can we create new variable using proc sql statement in SAS?
- Answer (akumar30−stat6250):  Yes, using LABEL = option we can create new variable using SAS proc sql statement.
* *Question (aalshehry−stat6250):* In SQL inquery, what is the substitue of proc means and proc freq?
- Question (meisenbach-stat6250): Does using PROC SQL create a different data structure than using the DATA statement? If I want to sort data using PROC SQL, does the data need to be read into a TABLE?
- Question (dlee117−stat6250): Even though PROC SQL requires less code (since it uses the select clause to combine the functions of the RETAIN and KEEP statements), when are the times when you want to use PROC SQL and when are the times you would want to use the regular DATA step?
- Question (kveng−stat6250): What happens if we don't sepecify the program to quit at the end?
- *Question* (lwang30-stat6250): If *prog glm* is an interactive proc, why can we still run other statement without enclosing *proc glm* by a "quit" ? 
- Question (yzhu12-stat6250): How does SAS run sql and what’s the difference of the coding language between sql and SAS?
- Question (nly13-stat6250): What is the memory limit to proc sql?
- Question (aoneill2−stat6250): What statement can be left out of the recipe without affecting its output?
- Answer (aoneill2−stat6250): The WHERE statement can be omitted.
- Question (aoneill2−stat6250): What is the PROC step used in the advanced recipe for creating analytic datasets?
- Answer (aoneill2−stat6250): The PROC SQL step is used.
- Question (aoneill2−stat6250): What is one advantage of a PROC SQL step?
- Answer (aoneill2−stat6250): The PROC SQL statement uses les code that a DATA step.
- Question (aoneill2−stat6250): How do you end a PROC SQL step?
- Answer (aoneill2−stat6250): A PROC SQL step must end with a QUIT statement.
- Question (yren10−stat6250): How to use PROC SQL to do the subset and make concatenate datasets?
- Question (mcardoso3-stat6250):  How important is PROC SQL command in comparison to the other SAS commands?
-	Question (lzhao4-stat6250): Can select statement be used to drop a column in PROC SQL?



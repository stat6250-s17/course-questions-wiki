## Week 2 Quiz Questions and Answers

In order to prepare your Week 2 Quiz submission, please edit ***this*** document to provide substantive questions for each Quiz Problem and SAS Recipe listed below, as well as answers to at least three questions raised.

All edits should conform to GitHub Markdown specifications (https://guides.github.com/features/mastering-markdown/) and should be committed to a branch named "week-2" in your fork of this repo. Then, after all edits have been made/committed, your Week 2 Quiz should be submitted by initiating a pull request using

- the master branch of the stat6250/course_questions_wiki repo as the base fork and

- the week-2 branch of your version of the repo as the head fork.

The instructor will then review the pull request and make comments should further revision be needed. Then, after the contents of the pull request have been finalized without any merge conflicts, the instructor will merge the pull request.

********************************************************************************



[Course Textbook Chapter 1, Problem 1]
* *Question (aalshehry−stat6250):* Wht is themaximum number of observations per dataset? What about variables/columns?
- Question (lzhao4−stat6250): Do missing values affect the structure of the data set?
- Question (dlee117−stat6250): In the given data set, what is considered an observation and what is considered a variable?
- Answer (dlee117-stat6250): An observation is a single row (Picker, M, 32) and a variable is a single column (Name).
- Question (yzhu12-stat6250): In a SAS table, what does the rows and columns represent?
- Answer (yzhu12-stat6250): The number of the rows represents observations, the number of the columns represents the variables.
- *Question* (lwang30-stat6250) : If only the column of variable age is presented, do we still consider it to have four observations considering the missing value ?
- Question (kveng-stat6250): Is “.” represent missing value in a data set?
- Answer (kveng-stat6250): Yes, “.” Represents numeric missing value in a data set?
- Question (hhu9−stat6250): What is the difference between variables and observations in data set?
- Answer (hhu9−stat6250): Rows represent observations and columns represent variables.
- Question (nly13-stat6250): Is it possible to set the name as an ID?
- Question (meisenbach-stat6250): Are there any other variable types? Datetime? Boolean?
- Answer (meisenbach-stat6250): No but... "SAS converts date, time, and datetime values back and forth between calendar dates and clock times with SAS language elements called formats and informats" - SAS 9.4 Language Reference.
- Question (aoneill2−stat6250): Are observations always equivalent to the number of rows of data regardless of whether any specific row has null data fields?
- Answer (aoneill2−stat6250): Yes, each row of data is an "observation," whether all data fields have data or not.



[Course Textbook Chapter 1, Problem 2]
* *Question (aalshehry−stat6250):* Why should we use “run;” steatment many times within SAS program instead of one time at the end?
* *Answer (aalshehry−stat6250):* The "run;" statement is often not strictly required, as SAS will assume you want to start a new step when it sees data or proc. However your code will be clearer and easier to understand if you make the end of each step explicit.
- Question (lzhao4−stat6250): Add run statement after each program step is an essential?character variable is valid when contains letters and underscores.
- Question (dlee117−stat6250): When running the given program, is it ok that some of the lines in the code are indented?
- Answer (dlee117-stat6250): Yes, SAS statements are free-format. This means that they can begin and end anywhere on a line.
- Question (yzhu12-stat6250): What kind of statement in SAS represent executing previous steps in the program?
- Answer (yzhu12-stat6250): data, proc or run statement.
- *Question* (lwang30-stat6250) : How many variables does the final output totally have ?
- Question (kveng-stat6250): What does “proc” refer to?
- Answer (kveng-stat6250): “proc” refers to procedure in SAS.
- Question (hhu9−stat6250): Can we calulate problem steps just by RUN statement?
- Answer (hhu9−stat6250): Yes, since all RUN statement follow DATA steps and PROC steps. 
- Question (nly13-stat6250): What’s the difference between  infile and set?
- Answer (nly13-stat6250): From what I’ve researched, infile allows you to pull data records from external files.
- Question (meisenbach-stat6250): Is indenting within steps necessary?
- Answer (meisenbach-stat6250): No, but it helps with code readability.
- Question (aoneill2−stat6250): What are program steps? Do they consist of a set of statements ending in a semicolon that end with a run statement? Or are they just statements that end in semicolons?
- Answer (aoneill2−stat6250): Program steps are defined as beginning with "data" or "proc". Program steps are then usually each terminated by a "run" statement.



[Course Textbook Chapter 1, Problem 3]
* *Question (aalshehry−stat6250):* How many type of variables does SAS support?
- Question (lzhao4−stat6250): Can numeric variable contains letter and underscore?
- Answer (lzhao4−stat6250): A numeric variable can only contain numeric values. A 
- Question (dlee117−stat6250): Is it valid for the variable AcctNum to contain both numbers and letters?
- Question (yzhu12-stat6250): What's the difference between character variable and numeric variable?
- Answer (yzhu12-stat6250): character variables can contain any values while numeric variables can contain only numeric values. 
- *Question* (lwang30-stat6250) : What are the other names for numeric and character variables ?
- Question (kveng-stat6250): Can a single variable (a column) contain multiple data types?
- Answer (kveng-stat6250): A single variable (a column) can’t  contain multiple data types.
- Question (hhu9−stat6250): How to distinguish the type of variables?
- Answer (hhu9−stat6250): we can see the value including which kind of characaters.
- Question (nly13-stat6250):How are some of the values read as character under AcctNum if there are numbers?
- Answer (nly13-stat6250): By adding a $ at the end of AcctNum, it makes all of its values a character.
- Question (meisenbach-stat6250): What happens when you try to assign a character value to a numeric variable and vice versa?
- Question (aoneill2−stat6250): If a variable type is not specified, what is the default?



[Course Textbook Chapter 1, Problem 4]
* *Question (aalshehry−stat6250):* How to represent missing data in SAS dataset?
- Question (lzhao4−stat6250): Can missing value indicates a different type of variable?
- Question (dlee117−stat6250): Is it valid to change the variable name Brand to 10Brand? 
- Answer (dlee117-stat6250): No, each variable name has to begin with a letter or an underscore, not a number.
- Question (yzhu12-stat6250): If a data value is unknown for a particular observation, where should we find the missing value?
- Answer (yzhu12-stat6250): The missing value is recorded in the SAS data set automatically.
- *Question* (lwang30-stat6250) : How is the missing value displayed for both numeric and character variables ?
- *Answer* (lwang30-stat6250) : The missing value appears as a period for numeric variables, and blank for character variables.
- Question (kveng-stat6250): Does SAS exclude missing value when doing the calculation? 
- Question (hhu9−stat6250): Who to represent missing value?
- Answer (hhu9−stat6250): Blank or a period.
- Question (nly13-stat6250): Can SAS read determine value types automatically when reading in a mixed data set?
- Question (meisenbach-stat6250): SAS uses floating point representation for a numeric values? Does this cause inaccuracies when working with integer values?
- Question (aoneill2−stat6250): Does a numeric variable have to be specified as such to be treated as a number for calculations?



[Course Textbook Chapter 1, Problem 5]
* *Question (aalshehry−stat6250):* Can a character variable begins with a number?
- Question (lzhao4−stat6250): What is the basic rule to set a valid variable name in SAS?
- Question (dlee117−stat6250): Can variable names contain a space?
- Question (yzhu12-stat6250): Is the variable name @Bunny01 a valid name? 
- Answer (yzhu12-stat6250): No, it's not a valid name because it must begin with a letter (A–Z, either uppercase or lowercase) or an underscore, and can continue with any combination of numbers, letters, or underscores. 
- *Question* (lwang30-stat6250) : What are the rules for variable names ?
- *Answer* (lwang30-stat6250) : Variable names must begin with a letter or an underscore, and continue with any combination of numerals, letters, or underscores.
- Question (kveng-stat6250): Can a variable name contain special characters?
- Question (hhu9−stat6250): What is the rules of SAS data set names and variable names?
- Answer (hhu9−stat6250): Variable names follow the same rules as SAS data set names. They can be 1 to 32 characters long, must begin with a letter (A-Z, either uppercase or lowercase) or an underscore, and can continue with any combination of numerals, letters, or underscores.
- Question (nly13-stat6250): In the text it says a variable can only begin with a letter or an underscore, but if does converting it to a character with $ make a difference?
- Question (meisenbach-stat6250): Is SAS case sensitive? 
- Answer (meisenbach-stat6250): No
- Question (aoneill2−stat6250): If a variable is not named correctly, does it generate an error in naming, or is the error type hard to pin dow?



[Course Textbook Chapter 1, Problem 8]
* *Question (aalshehry−stat6250):* Considering all numeric variables have a default length of 8 bytes, what is the maximum value that can SAS accept for a numeric variable?
* *Answer (aalshehry−stat6250):* 
![8 byte](https://github.com/aalshehry-stat6250/course-questions-wiki/blob/Week-2/week-02/8byte.JPG?raw=true)
- Question (lzhao4−stat6250): No matter a numeric variable contains how many digits it has a default length of 8?
- Answer (lzhao4−stat6250): Numeric variable balance always has a default length of 8 unless you set a specific length.
- Question (dlee117−stat6250): Why does the variable Name have a longer length than Policy or Total?
- Question (yzhu12-stat6250): What's the default length of the numeric variable Oyster?
- Answer (yzhu12-stat6250): 6
- *Question* (lwang30-stat6250) : What would SAS output if we input a numeric value that exceeds 8 bytes ? Would it be rounded up to the first 8 digits including decimal points ?
- Question (kveng-stat6250): Can set a default length different than 8 bytes?
- Question (hhu9−stat6250): What is the default length for the numeric variable Balance?
- Answer (hhu9−stat6250): No matter how many digits they contain, the default length is 8.
- Question (nly13-stat6250): Is there a maximum length for character variables?
- Answer (nly13-stat6250): character variables can be 1-32 characters long.
- Question (meisenbach-stat6250): What happens when you try to assign a value larger than the defined length of the variable?
- Question (aoneill2−stat6250): How can you tell what the default length for a numeric variable is beyond the digits and decimal point that are shown for the entries? Is there a typical default length for decimal numbers?



[Course Textbook Chapter 2, Problem 3]
* *Question (aalshehry−stat6250):* Where and how to use YEARCUTOFF option?
- Question (lzhao4−stat6250):  YEARCUTOFF= option has no effect in some cases?
- Answer (lzhao4−stat6250): The YEARCUTOFF= option has no effect when processing dates with four-digits years, processing dates already stored as SAS date values, and displaying dates with SAS date formats.
- Question (dlee117−stat6250): What date would 4/4/17 be interpreted as if YEARCUTOFF = 2017?
- Question (yzhu12-stat6250): How to define library?
- Answer (yzhu12-stat6250): You assign a library name (a libref) to it and specify a path, such as a directory path and use the libref as the first part of the file's two-level name (libref.filename) to reference the file within the library. You can use programming statements to assign library names. 
- *Question* (lwang30-stat6250) : Is there a way to let SAS read and process more than 100 years ?
- Question (kveng-stat6250): Is “YEARCUTOFF” a function in SAS? 
- Question (hhu9−stat6250): Does the YEARCUTOFF=option has affect on 4 digit value?
- Answer (hhu9−stat6250): No, you set an informat with correct field width.
- Question (nly13-stat6250): In the text it says yearcutoff option really only applies for 2-digit years due to the fact that the century leading two digits may be ambigious. So how would it distinguish between 05 (1905) and 05 (2005)?
- Question (meisenbach-stat6250): If possible, should you always store dates using four digits?
- Question (aoneill2−stat6250): Can the value of the YEARCUTOFF= option be equal to exactly 100 yeas before the date in question?



[Course Textbook Chapter 2, Problem 7]
* *Question (aalshehry−stat6250):* How to save your dataset in the permanent library?
- Question (lzhao4−stat6250): How to correctly assign a SAS libref?
- Question (dlee117−stat6250): What are the steps to reference a permanent SAS file?
- Question (yzhu12-stat6250): How can you modify system options?
- Answer (yzhu12-stat6250): I submit an OPTIONS statement and place an OPTIONS statement anywhere in a SAS program to change the current settings. Because the OPTIONS statement is global, the settings remain in effect until you modify them or until you end your SAS session. 
- *Question* (lwang30-stat6250) : What are the functions of *proc freq* statement ?
- Question (kveng-stat6250): What does this part mean: “if totalsales>50000; run;”?
- Question (hhu9−stat6250): Whats the rules for librefs?
- Answer (hhu9−stat6250): Librefs must be 1 to 8 characters, and only contains letters,numerals,underscores.
- Question (nly13-stat6250): How do you remove permanently saved data in SAS?
- Question (meisenbach-stat6250): Why are librefs limited to 8 characters?
- Question (aoneill2−stat6250): Is "set" the key word to referencing a SAS data file?
- Answer (aoneill2−stat6250): Yes, "set" is used to reference a SAS file. The file name specified after the proc or data keyword is the name of the file created after program is run on the "set" statement-specified file.



[Course Textbook Chapter 2, Problem 8]
* *Question (aalshehry−stat6250):* Without using the YEARCUTOFF= option, how would SAS interpret 11/11/20? Is it 1920 or 2020?
* *Answer (aalshehry−stat6250):* The default value of YEARCUTOFF= is 1920.
- Question (lzhao4−stat6250): How does YEARCUTOFF= option work on the interpretation of two-digits years?
- Question (dlee117−stat6250): Is the value for YEARCUTOFF the first year of the 100-year span or the last year?
- Question (yzhu12-stat6250): What step should we take before we access to SAS files that stored in a permanent SAS data library?
- Answer (yzhu12-stat6250): We must assign a libref.
- *Question* (lwang30-stat6250) : What is the oldest date that SAS can trace back to ? 
- *Answer* (lwang30-stat6250) : All versions of SAS represent dates correctly from 1582 A.D. to 20,000 A.D..
- Question (kveng-stat6250): Does the YEARCUTOFF always has 100-year span? Can we modify YEARCUTOFF?
- Question (hhu9−stat6250): Can we reset the default value of YEARCUTOFF=option? 
- Answer (hhu9−stat6250): Yes , we can reset its first year.
- Question (nly13-stat6250): Can YEARCUTOFF be used for a millennium or is there a different code for that? 
- Question (meisenbach-stat6250): What is the default value for YEARCUTOFF=? Does this default update with newer versions of SAS?
- Answer (meisenbach-stat6250): 1926 for SAS 9.4 and beyond. It might. Previously the default was 1920.
- Question (aoneill2−stat6250): Can the value of the YEARCUTOFF= option be equal to exactly 100 yeas before the date in question? How do you determine the YEARCUTOFF= option if you are not syure about whether the years entered would be within a 100-yr interval?



[Course Textbook Chapter 2, Problem 9]
* *Question (aalshehry−stat6250):* If a SAS session is ended or a libref is deleted, does the library still exist?
* **Answer (aalshehry−stat6250): In these cases, SAS no longer has access to the files in the library.
- Question (lzhao4−stat6250): Libref exists only during the session in which it is created?
- Question (dlee117−stat6250): What is the default libref for temporary SAS files?
- Question (yzhu12-stat6250): What option do we add to suppress detailed information about the files?
- Answer (yzhu12-stat6250): NODS.
- *Question* (lwang30-stat6250) : Without a *libname* statement, what is the default place where SAS read and write data ? 
- Question (kveng-stat6250): What is Librefs?
- Answer (kveng-stat6250): A libref is a temporary name that you associate with the physical name of the SAS data library during each SAS job or session.
- Question (hhu9−stat6250): whats the meaning of special SAS window in this question? and what can we do more with it?
- Answer (hhu9−stat6250): Still try to solve this problem.
- Question (nly13-stat6250): How do you manually clear libref while still in a SAS session?
- Question (meisenbach-stat6250): <libref.>_ALL_ requests a listing of all files in the library. What happens with you name a dataset _all_ (which is a legal name)?
- Question (aoneill2−stat6250): Can the value of the YEARCUTOFF= option be equal to exactly 100 yeas before the date in question? When would libref statements not be included in a SAS program to reference the permanent SAS library automatically when the program is submitted?



[basic_recipe_for_loading_data_from_remote_Excel_file (from Week 2 Overview)]
* *Question (aalshehry−stat6250):* Is it mandatory to use “filename tempfile clear;” step? Why?
- Question (lzhao−stat6250): Do we possible to transfer data from SAS dataset to an excel file? How? 
- Question (dlee117−stat6250): What does it mean to assign TEMP to the file name tempfile?
- Question (yzhu12-stat6250): Besides the method using "get" function to download URL, what other methods can be the substitute?
- *Question* (lwang30-stat6250) : Why can some statement lines not end with a semicolon ?
- Question (kveng-stat6250): Where does the “tempfile” is stored after we run the code. Is it stored in a local computer or SAS server? Can we have it stored in our personal computer? 
- Question (hhu9−stat6250):  there is a technology that transfer PDF to word, is it can be used to transfer image data to excel, and then to SAS data set? 
- Question (nly13-stat6250): Is formatting ever an issue when getting data from a URL to Excel to SAS?
- Question (meisenbach-stat6250): What happens if I misspell something (e.g dbms → dms)?
- Answer (meisenbach-stat6250): You get a warning that the interpretor assumed symbol DBMS was misspelled as "dms" and the statement executes correctly.
- Question (aoneill2−stat6250): What data step follows the proc http data step in importing an online file into a temporary working file?



[optional: bonus_advanced_recipe_for_loading_data_from_remote_Excel_file (from Week 2 Overview)]
- Question (yzhu12-stat6250): What's the meaning of two command % and & in SAS?
- *Question* (lwang30-stat6250) : In the macro, what are the functions of **%** and **&** respectively ? What is the advantage of using a macro ? 



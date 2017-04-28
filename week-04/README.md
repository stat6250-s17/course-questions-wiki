## Week 4 Quiz Questions and Answers

In order to prepare your Week 4 Quiz submission, please edit ***this*** document to provide substantive questions for each Quiz Problem and SAS Recipe listed below, as well as answers to at least three questions raised.

All edits should conform to GitHub Markdown specifications (https://guides.github.com/features/mastering-markdown/) and should be committed to a branch named "week-4" in your fork of this repo. Then, after all edits have been made/committed, your Week 4 Quiz should be submitted by initiating a pull request using

- the master branch of the stat6250/course_questions_wiki repo as the base fork and

- the week-4 branch of your version of the repo as the head fork.

The instructor will then review the pull request and make comments should further revision be needed. Then, after the contents of the pull request have been finalized without any merge conflicts, the instructor will merge the pull request.

********************************************************************************



[Course Textbook Chapter 7, Problem 3]
- Question (akumar30−stat6250):  What is the maximum length of format-name defined as VALUE format-name?
- Answer (akumar30−stat6250):  It varies on SAS Version and type of format-name. In SAS 8.2 maximum length will be up to eight characters only. But in SAS 9 onwards, a numeric format name can be up to 32 characters in length and character format name can be up to 31 characters in length. 
- Question (mcardoso3-stat6250):  What is considered to be a VALUE statement when creating a format in Escape?
- Answer (mcardoso3-stat6250): A VALUE in SAS can be any set of numbers or letter characters that are enclosed in quotation marks, not a combination of letters and numbers nor any special characters (@,#,$).
- Question (dlee117−stat6250): What is the general form of the VALUE statement?
- Question (rluo-stat6250): What format catalog would be stored if we do not specify the LIBRARY = option?
- Answer (rluo-stat6250): The format catalog named Work.Formats would be stored.
- Question (hhu9−stat6250):Why the new format's name can not be the name of data set variable?
- Question (yyan11−stat6250): How to create a new format's name of the VALUE statement?
- Answer (yyan11−stat6250): Where format-name must begin with a dollar sign ($) if the format applies to character data, must be a valid SAS name, cannot be the name of an existing SAS format, cannot end in a number, does not end in a period when specified in a VALUE statement.
- Question (aoneill2-stat6250): Is there a way to permanently assign a libref statement for a user-defined library?
- *Question* (yren10−stat6250): What is the format when creating with a VALUE statemen?
- *Answer* (yren10−stat6250): Must begin with a dollar sign($) if it applies to a character variable.
- Question (meisenbach-stat6250): Why would the name ending with number be a problem?
- Question (nly13-stat6250): Is it possible to take a range of items, and format them into a number?
- Question (kveng−stat6250): When creating a format with the VALUE statement, do we only use the sign ($) if used with a character varaible?
- Answer (kveng−stat6250): Yes, if it's number then we don't need to begin with the dollar sign.
- *Question* (lwang30-stat6250) : In what situations does the new format's name have to end with a period ?
- Question (cyuan10-stat6250): Can you use a mix of values that includes both character values as well as numeric values?
- Answer (cyuan10-stat6250): There are particular keywords you can use together with numeric values such as "LOW" and "OTHER" but cannot be a combination of character and numeric values.
- Question (yzhu12-stat6250): Which sign do we must begin with when the name of a format that is created with a VALUE statement?
- Answer (yzhu12-stat6250): A dollar sign must be used.


[Course Textbook Chapter 7, Problem 4]
- Question (akumar30−stat6250): Can we define several formats in single proc format statement?
- Answer (akumar30−stat6250):  Yes, we can use multiple VALUE statements in a single PROC FORMAT step to define multiple formats.
- Question (mcardoso3-stat6250):  Are there any instatnces where a SAS line doesn't need to end in a semicolon?
- Question (dlee117−stat6250): What are your two options when using the PROC FORMAT statement?
- Answer (dlee117-stat6250): You can enter LIBRARY, which specifies the libref for a SAS library to contain a permanent catalog of user-defined formats, or FMTLIB, which displays a list of all of the formats in your catalog with descriptions.
- Question (rluo-stat6250): What is the function of VALUE statement?
- Question (hhu9−stat6250): What's the function of a semicolon after PROC FORMAT statement?
- Answer (hhu9-stat6250)  : semicolon means a complete process.
- Question (yyan11−stat6250): How to write the FORMAT procedures?
- Answer (yyan11−stat6250): The statement begins with the keyword VALUE and ends with a semicolon after all the labels have been defined. 
- Question (aoneill2-stat6250): What kind of error is generated if the proc format statement is lacking a semicolon or has one too many? 
- *Question* (yren10−stat6250): How exactly sign (;) does in SAS format?
- Question (meisenbach-stat6250): Are you able to specify strings in the value range (e.g. ‘’CA” = “California”)?
- Answer (meisenbach-stat6250): Yes (according to SAS documentation)
- Question (nly13-stat6250): In most cases, if there is a missing value, will other=’unknown’ just replace the ‘.’ For missing vlaules with ‘unknown’?
- Question (kveng−stat6250): What is FORMAT procedures for?
- Answer (kveng−stat6250): Using the FORMAT procedure, you can define your own formats for variables. You can store your formats temporarily or permanently, and you can display a list of all your formats and descriptions of their values.
- *Question* (lwang30-stat6250) : What should be done prior to the *proc format* step to indicate where the new format will be stored ?
- Question (cyuan10-stat6250): Can we reformat "text" or character values with numeric values instead? How would we approach this?
- Question (yzhu12-stat6250): What does VALUE statement begin with and end with?
- Answer (yzhu12-stat6250): A VALUE statement begins with VALUE and ends with a semicolon after all the labels are defined. 



[Course Textbook Chapter 7, Problem 5]
- Question (akumar30−stat6250):  Can we use combination of character and numeric values together to defining the VALUE range for format-name?
- Answer (akumar30−stat6250):  No, because formats themselves are either character or numeric.
- Question (mcardoso3-stat6250):  Do the values need to be in alphabetical/numerical in the VALUE statement?
- Question (dlee117−stat6250): When specifying a VALUE range, can you have a list of values that are a combination of character and numeric values?
- Answer (dlee117-stat6250): No, these values must be character values OR numeric values, not a combination. This is because formats themselves are either character or numeric.
- Question (rluo-stat6250): What is the range that VALUE can specify?
- Question (hhu9−stat6250): Can numeric variables and character variables setted in one list to together?
- Answer (hhu9-stat6250)  : No, the list must contain either all nnumberic values or all character values.
- Question (yyan11−stat6250): How many values could be displayed when use the VALUE statement to define a format?
- Answer (yyan11−stat6250): You can use the VALUE statement to define a format for displaying one or more values.
- Question (aoneill2-stat6250): Is it possible to mix numbers and characters in a range of values in a user-defined proc format statement?
- Answer (aoneill2-stat6250): No, it is not possible to mix them. A character format name must start with a $ sign.
- *Question* (yren10−stat6250): Can we list values separated by commas?
- *Answer* (yren10−stat6250): You can list values separated by commas, but need to be either all numeric values or all character values.
- Question (meisenbach-stat6250): Why can’t you mix character and numeric values?
- Answer (meisenbach-stat6250): Because the formats are defined as either character or numeric
- Question (nly13-stat6250):  If there are a mix of numeric and characters in a range, is the best course of action to use 2 separate VALUE statements?
- Question (kveng−stat6250): Can we specify a ranges in the VALUE statement with both numberic and character type of data?
- Answer (kveng−stat6250): No, we can't have multiple types of data when specifying a ranges in the VALUE statement.
- *Question* (lwang30-stat6250) : When are the single and double quotation mark used respectively in the *value* statement ?
- Question (cyuan10-stat6250): What is the largest numeric value we can use? What about character values - does it go beyond Z such as restarting with AA?
- Question (yzhu12-stat6250): If a value is combined with both numeric and characters, what will happen?
- Answer (yzhu12-stat6250): A value must contain either all numeric or character, or an error will be occurred.



[Course Textbook Chapter 7, Problem 6]
- Question (akumar30−stat6250): How to use apostrophe to appear in the label?
- Answer (akumar30−stat6250):  We can use two single quotation marks if we want an apostrophe to appear in the label.
- Question (mcardoso3-stat6250):  What would happen if there needs to be more characters than a label can provide?
- Question (dlee117−stat6250): Can you use numeric values in a label?
- Question (rluo-stat6250): Where can we plcae the FORMAT statement?
- Answer (rluo-stat6250): In either a DATA step or a PROC step.
- Question (hhu9−stat6250): What is max amount of characters in the label?
- Answer (hhu9-stat6250)  : 256
- Question (yyan11−stat6250): How can I do if I want an apostrophe to appear on the label?
- Answer (yyan11−stat6250): Use two single quotation marks if you want an apostrophe to appear in the label.
- Question (aoneill2-stat6250): Why must a label specifically be limited to 256 characters? Is that the byte size?
- *Question* (yren10−stat6250): Does a label need to enclose in a quitation marks?
- Question (meisenbach-stat6250): Does other work for missing character values? 
- Question (nly13-stat6250): Does the limit of characters on Label have to with how many bytes it can store?
- Question (kveng−stat6250): Is 256 characters is the maximum number of chacracters that we can use in a label?
- *Question* (lwang30-stat6250) : How many characters can be used in a variable's name ?
- Question (cyuan10-stat6250): Why is the characters used in the label limited to 256? 
- Question (yzhu12-stat6250): What do you use when you want an apostrophe to appear in a label?
- Answer (yzhu12-stat6250): We need to use two double quotation marks.




[Course Textbook Chapter 7, Problem 7]
- Question (akumar30−stat6250): What is the advantage of keyword OTHER to specify the variables range of a format?
- Answer (akumar30−stat6250):  The keyword OTHER is used to label missing values as well as any values that are not specifically addressed in a range.
- Question (mcardoso3-stat6250):  Given that there are keywords for the upper and lower limits of a variable's value range, is there any keyword that can specify the median of the range?
- Question (dlee117−stat6250): What is the point of using the LOW and HIGH keywords instead of using a low or high number?
- Question (rluo-stat6250): What steps must be done when we associate a format with a variable?
- Answer (rluo-stat6250): We mustuse the same format name in the FORMAT statement that you specified in the VALUE statement and place a period at the end of the format name when it is used in the FORMAT statement.
- Question (hhu9−stat6250): Should we remenber all key words in SAS statement?
- Question (yyan11−stat6250): Which keyword can I use to specify the lower and upper limits of a variable's value range?
- Answer (yyan11−stat6250): You can also use the keywords LOW and HIGH to specify the lower and upper limits of a variable's value range. The keyword LOW does not include missing numeric values. The keyword OTHER can be used to label missing values as well as any values that are not specifically addressed in a range.
- Question (aoneill2-stat6250): Are missing values included in "low" values?
- Answer (aoneill2-stat6250): Yes, missing values can be included in "low" values, as it includes anything lower than the specified value as well as any 'other' missing values.
- *Question* (yren10−stat6250): What is keyword LOW does in SAS?
- Question (meisenbach-stat6250): Does OTHER work for missing character values? 
- Question (nly13-stat6250): if you use the value statement ‘Low-High’ will that cover the entire range?
- Question (kveng−stat6250): is "OTHER" a built-in keyword in VALUE statement in SAS?
- *Question* (lwang30-stat6250) : What other keywords can also be used to label ?
- Question (cyuan10-stat6250): Are there other keywords available, what are they and does this mean we cannot use these key words as a value?
- Question (yzhu12-stat6250): Why MISS and MISSING are invalid keywords in SAS?


[Course Textbook Chapter 7, Problem 8]
- Question (akumar30−stat6250): Can we reuse the format created in data step inside proc step?
- Question (mcardoso3-stat6250):  What is the purpose of using a PROC FORMAT statement in SAS?
- Answer (mcardoso3-stat6250):  PROC FORMAT statements are used to create a catalog of all formats in SAS, or to be stored in an existing format catalog under the SAS library.
- Question (dlee117−stat6250): When would you want to permanently associate a format with a variable?
- Question (rluo-stat6250): How to displays a list of all the formats in the catalog?
- Answer (rluo-stat6250): We can add the keyword FMTLIB to the PROC FORMAT statement.
- Question (hhu9−stat6250): Can we get same result when we place the FORMAT statement in different step?
- Answer (hhu9-stat6250)  : No, There are two different steps(DATA step and PROC step) for placing FORMAT statement.
- Question (yyan11−stat6250): Can I place the FORMAT statement in a DATA step?
- Answer (yyan11−stat6250): Yes, you can place the FORMAT statement in either a DATA step or a PROC step. By placing the FORMAT statement in a DATA step, you can permanently associate a format with a variable. Note that you do not have to specify a width value when using a user-defined format.
- Question (aoneill2-stat6250): Are FORMAT statements permanently available to a SAS program when they are included in the DATA step or in the PROC step or both?
- Question (aoneill2-stat6250): FORMAT statements are only made permantently available to a SAS program when they are cinluded in the DATA step.
- *Question* (yren10−stat6250): What happens when you place the FORMAT statement in a PROC step?
- Question (meisenbach-stat6250): Are permanently associated formats also available for use elsewhere?
- Question (nly13-stat6250): Can your format an output statement?
- Question (kveng−stat6250): What happens when you place the FORMAT statement in PROC step?
- *Question* (lwang30-stat6250) : What happens when you place the *format* statement in a PROC step ?
- Question (cyuan10-stat6250): What is the advantages or reason why one would use PROC FORMAT vs. DATA FORMAT?
- Question (yzhu12-stat6250): How to  associate user-defined formats with variables in the FORMAT statement?
- Answer (yzhu12-stat6250): We use the same format names in both the FORMAT and VALUE statements, but place a period at the end of the format name when it is used in the FORMAT statement.


[Course Textbook Chapter 8, Problem 1]
- Question (akumar30−stat6250): Can we get median and range as default statistics output of PROC MEANS statement?
- Answer (akumar30−stat6250):  No, you need to define MEDIAN and RANGE keywords in PROC MEANS statement to get the median and range of dataset.
- Question (mcardoso3-stat6250):  Why would knowing the standard deviation of a SAS dataset be more important to know by PROC MEANS than the median?
- Question (dlee117−stat6250): What is the difference between the MEANS procedure and the SUMMARY procedure?
- Question (rluo-stat6250): How to sepcify a statistic in the PROC MEANS statement?
- Question (hhu9−stat6250): Can we reset default MEANS procedure to obtain other values?
- Question (yyan11−stat6250): What are the MEANS procedure when the default statistics produced?
- Answer (yyan11−stat6250): In its simplest form, PROC MEANS prints the n-count (number of nonmissing values), the mean, the standard deviation, and the minimum and maximum values of every numeric variable in a data set.
- Question (aoneill2-stat6250): What statistical measures do you get from the PROC MEANS statement if no specific measures are included in the statement?
- *Question* (yren10−stat6250): Are we able to change the default statistics produced by the MEANS procedure and how?
- Question (meisenbach-stat6250): How do you select which statistics to include?
- Question (nly13-stat6250): Why are median and range not set as a default of PROC MEANS?
- Question (kveng−stat6250): What's the procedure to perform median and range?
- *Question* (lwang30-stat6250) : Which keyword represents standard deviation in the MEANS procedure ?
- Question (cyuan10-stat6250): Will PROC Summary produce the same set of default output (Mean, Median, Max, Min)?
- Question (yzhu12-stat6250): What happens if PROC REPORT can't create groups?
- Answer (yzhu12-stat6250): It displays group variables as order variables.


[Course Textbook Chapter 8, Problem 2]
- Question (akumar30−stat6250): How to limit decimal places in PROC MEANS statement?
- Answer (akumar30−stat6250):  using option MAXDEC=n; where n specifies the maximum number of decimal places.
- Question (mcardoso3-stat6250):  What is the difference between the "var" command and the "by" and "class" commands?
- Answer (mcardoso3-stat6250):  "var" is meant to analyze variables, while "class" and "by" are used for categorizing observations.
- Question (dlee117−stat6250): If you have a large amount of similar variables (designated by different numbers), what can you do to make the task of listing out all of these variables less tedious?
- Answer (dlee117-stat6250): Instead of listing variables separately, you can use a numbered range of variables (i.e. item1-item5 instead of item1, item2, item3, item4, and item5).
- Question (rluo-stat6250): How to limit decimal places?
- Question (hhu9−stat6250): What should we do if we want to specify some variables that PROC MEANS analysis?
- Answer (hhu9-stat6250)  : Write a var statement.
- Question (yyan11−stat6250): What can I do when I want to focus on a few variables?
- Question (aoneill2-stat6250): What is the primary difference between specifying variables with the var statement and the class statement?
- *Question* (yren10−stat6250): Is there another statement can limits a PROC MEANS analysis to the variables Boarded, Transfer, and Dep?
- Question (meisenbach-stat6250): In a PROC MEANS statement, is the order of the variables significant?
- Question (nly13-stat6250): Does the order of the specified variables in PROC MEANS determine the order of the output?
- Answer (nly13-stat6250): Generally yes, since SAS usually processes statements in the order given.
- Question (kveng−stat6250): What does "var" referred to when used in PROC MEANS?
- *Question* (lwang30-stat6250) : What would the output be if the variables specified in *proc means* have both numeric and character types ?
- Question (cyuan10-stat6250): If we use a combination of var and by, can we produce a cross tabulation of MEANS statistics by selected variables?
- Question (yzhu12-stat6250): What's the difference between the output when you use PROC REPORT in a windowing and a nonwindowing mode?


[Course Textbook Chapter 8, Problem 4]
- Question (akumar30−stat6250): Why we need to sort the data first before using BY variable(s) statement?
- Question (mcardoso3-stat6250):  What happens if data wasn't previously sorted before using PROC MEANS with a BY group and would everything need to be redone?
- Question (dlee117−stat6250): When would you use the BY statement and when would you use the CLASS statement?
- Question (rluo-stat6250): How to specify the variables that PROC MEANS analyzes?
- Question (hhu9−stat6250): What's the difference between BY group processing and CLASS processing?
- Question (yyan11−stat6250): The BY statement like the CLASS statement specifies variables to use for categorizing observations, are they same require?
- Answer (yyan11−stat6250): No, BY processing requires that your data already be sorted or indexed in the order of the BY variables. Unless data set observations are already sorted, you will need to run the SORT procedure before using PROC MEANS with any BY group.
- Question (aoneill2-stat6250): Can BY statements be used in other commands besides PROC MEANS?
- *Question* (yren10−stat6250): Can BY-group processing be mixed with indexed and sorted?
- Question (meisenbach-stat6250): When is it preferable to use BY instead of CLASS?
- Question (nly13-stat6250): What are the differences between CLASS and BY?
- Answer (nly13-stat6250): BY processing requires that the data is already sorted or indexed.
- Question (kveng−stat6250): What is CLASS processing versus BY group processing?
- *Question* (lwang30-stat6250) : Which procedure should be performed prior to the BY group processing in *proc means* ?
- *Answer* (lwang30-stat6250) : The data should be sorted by *proc sort* statement first before BY group processing is performed in *proc means*.
- Question (cyuan10-stat6250): What happens if the BY variables are not indexed or sorted? Would we get an error?
- Question (yzhu12-stat6250): What happens if PROC REPORT can't create groups?
- Answer (yzhu12-stat6250): It displays group variables as order variables.


[Course Textbook Chapter 8, Problem 7]
- Question (akumar30−stat6250):  Is prior sorting required for PROC FREQ statement?
- Question (mcardoso3-stat6250):  What other columns would be useful for analysis if added to the PROC FREQ tables besides frequency and percentages?
- Question (dlee117−stat6250): What is recommended that you use when you use a PROC FREQ statement?
- Question (rluo-stat6250): What kind of summary statistics are produced when you use the OUTPUT statement?
- Question (hhu9−stat6250): Does PROC FREQ creates a table for all bariables?
- Answer (hhu9-stat6250)  : Yes.
- Question (yyan11−stat6250): which data set variables could be created by the FREQ procedure?
- Answer (yyan11−stat6250): By default, the FREQ procedure creates frequency tables for every variable in your data set. To specify the variables to analyze, include them in a TABLES statement.
- Question (aoneill2-stat6250): Why are categorical variables the best choice for table values in a PROC FREQ statement?
- *Question* (yren10−stat6250): How to creat both both character and numeric variables?
- Question (meisenbach-stat6250): How can you specify which variable to include in PROC FREQ?
- Answer (meisenbach-stat6250): Use a TABLES variables statement.
- Question (nly13-stat6250): How does PROC FREQ order the tables?
- Answer (nly13-stat6250): the order of variables for the ‘tables’ statement determines the order.
- Question (kveng−stat6250): Can PROC FREQ create a table of frequencies for all variables in the data set?
- *Question* (lwang30-stat6250) : What other statistics does *proc freq* create in the output ?
- *Answer* (lwang30-stat6250) : By default, *proc freq* also prints cumulative frequency and cumulative percent in the output.
- Question (cyuan10-stat6250): How should we handle numeric variable in PROC FREQ? 
- Answer (cyuan10-stat6250): We can re-format the numeric variables and create a shorter list of ranges.
- Question (yzhu12-stat6250): When will PROC REPORT try to consolidate into one row all observations from the data set
that have a unique combination of values for all group variables?
- Answer (yzhu12-stat6250): If a report contains one or more group variables.


[Course Textbook Chapter 8, Problem 8]
- Question (akumar30−stat6250):  Which variables are most suitable for PROC FREQ Statements?
- Answer (akumar30−stat6250):  Frequency distributions work best with variables whose values can be described as categorical, and whose values are best summarized by counts rather than by averages.
- Question (mcardoso3-stat6250):  Why are categorical variables the best choice of variables for using PROC FREQ?
- Answer (mcardoso3-stat6250):  Categorical variables are the best option for using frequency distributions since numeric variables can be continous and therefore result in lengthy tables.  Unique values would also be unsuitable for PROC FREQ.
- Question (dlee117−stat6250): How do you determine the order that your variables are listed in the PROC FREQ report?
- Question (rluo-stat6250): What statement should we use with PROC FREQ in order to eliminate excessive or inappropriate output?
- Question (hhu9−stat6250): Why continuous values can result in meaningless tables?
- Question (yyan11−stat6250): Which variable is the best with frequency distributions work?
- Answer (yyan11−stat6250): The FREQ procedure creates frequency tables for every variable in your data set. But this isn't always what you want. A variable that has continuous numeric values—such as DateTime—can result in a lengthy and meaningless table. Likewise, a variable that has a unique value for each observation—such as FullName—is unsuitable for PROC FREQ processing. Frequency distributions work best with variables whose values can be described as categorical, and whose values are best summarized by counts rather than by averages.
- Question (aoneill2-stat6250): What is the greatest barrier to using continuous variables for frequency distributions?
- *Question* (yren10−stat6250): Does Frequency distributions can work good with all these four types of values?
- *Answer* (yren10−stat6250): No. Both continuous values and many unique values can result in lengthy and meaningless tables. Frequency distributions work best with categorical values.
- Question (meisenbach-stat6250): What happens if you run PROC FREQ on non-categorical values?
- Question (nly13-stat6250): If you only have numeric values, is it best to turn them into a categorical variable of a range, ex. ‘1- 10’ and then using PROC FREQ?
- Question (kveng−stat6250): What is frequency distributions?
- *Question* (lwang30-stat6250) : How do we limit the frequency distribution output to categorical values only ?
- Question (cyuan10-stat6250): What other outputs would be useful to understand FREQ data?
- Answer (cyuan10-stat6250): It would be nice if a histogram plot or box-whisker plot is given.
- Question (yzhu12-stat6250): Under what kind of option settings, your PROC REPORT output will appear as HTML and/or as SAS listing
output?


[Course Textbook Chapter 8, Problem 10]
- Question (akumar30−stat6250):  Can we restrict PROC FREQ output to not display Percent and Cumulative Percent Column?
- Question (mcardoso3-stat6250):  How many variables can be inputed for a two a PROC FREQ table?
- Question (dlee117−stat6250):When cross tabulations are specified, what are the four parameters produced by the PROC FREQ statement?
- Question (rluo-stat6250): What kind of variables work best with frequency distributions?
- Question (hhu9−stat6250): What kind of table can be made via more than 2 kinds of variables?
- Question (yyan11−stat6250): How to control the depth of crosstabulation results?
- Answer (yyan11−stat6250): NOFREQ suppresses cell frequencies, NOPERCENT suppresses cell percentages, NOROW suppresses row percentages, NOCOL suppresses column percentages.
- Question (aoneill2-stat6250): When would it be advantageous to specify no rows or no columns in a PROC FREQ statement when generating a table?
- *Question* (yren10−stat6250): What does the star sign acrtually do in this command?
- Question (meisenbach-stat6250): What is the output of an n-way table?
- Answer (meisenbach-stat6250): A series of two-way tables is produced with a table for each level of the other variable.
- Question (nly13-stat6250): Are ‘nofreq’, ‘nocol’, ‘norow’, and ‘nopercent’ only used for PROC FREQ?
- Question (kveng−stat6250): Is there any better way to create a more better looking frequency table than PROC FREQ?
- *Question* (lwang30-stat6250) : In what situations shall we prefer to use */list* to generate a listing output for crosstabulation tables ?
- Question (cyuan10-stat6250): How do we switch the rows and columns in this example? Can we specify in SAS that we want to columns variables as the rows and the row variables as the columns?
- Question (yzhu12-stat6520): Under what situation we need to use DEFINE statement?


[recipe_for_summarizing_quantitative_values (from Week 4 Overview)]
- Question (akumar30−stat6250): Does SAS By default include observations with a missing value specified in CLASS or BY statement?      
- Answer (akumar30−stat6250): No, We need to specify MISSING statement to summarize the missing values.
- Question (mcardoso3-stat6250):  Why are no statistics explicitly listed in the options given in the PROC MEANS statement.
- Question (dlee117−stat6250): What is the default precision for the output and can you change the precision?
- Question (rluo-stat6250): What are the most basic statistical procs in the SAS?
- Question (hhu9−stat6250): How to use T-test?
- Question (yyan11−stat6250): To limit decimal places, use the MAXDEC= option in the PROC MEANS statement. Is that have a maximum number?
- Question (aoneill2-stat6250): Are PROC FREQ statements most effective for summarizing quantitative values?
- *Question* (yren10−stat6250): what statistics explicitly would be listed in the PROC MEANS statement?
- Question (meisenbach-stat6250): What does the MISSING option do?
- Answer (meisenbach-stat6250): It includes rows with missing values for the variable being summerized.
- Question (nly13-stat6250): From the PROC MEANS var statement, it generates a column for variable and label, is there a reason why it
does both since they are the same?
- Question (kveng−stat6250): In the PROC MEANS statement, what if we don't want all the default statistics in the result, we only want like mean and std dev?
- *Question* (lwang30-stat6250) : How to suppress the output statistics to mean and standard deviation only ?
- Question (cyuan10-stat6250): Can we have multiple classes and how can we decide it is appended vs. nested?
- Question (yzhu12-stat6250): Besides the statement we used in the video to summarize the quantitative variables, is there any other methods we can apply?


[recipe_for_summarizing_qualitative_values (from Week 4 Overview)]
- Question (akumar30−stat6250): What is the significance of using NLEVEL in PROC FREQ statement? 
- Question (mcardoso3-stat6250):  How were SAS codes run from the 1970s and were they inputed on a device before computers?
- Question (dlee117−stat6250): When and why would you want to use the NOPRINT statement?
- Question (rluo-stat6250): What is the function of the nlevel option?
- Question (hhu9−stat6250): According to the guidelines, 17 results can be obtained, so can we use other   intuitive ways to express result instead of table?
- Question (yyan11−stat6250): How many variables I can compute?
- Question (aoneill2-stat6250): What types of PROC FORMAT statements are most effective for summarizing qualitative data?
- *Question* (yren10−stat6250): How people keep datas and use SAS 50 years ago？ since they don't have any hi-tech computer like now we do，do they use sas to solve problems like what we do now?
- Question (meisenbach-stat6250): What does the slash (/) do in the PROC FREQ statement?
- Answer (meisenbach-stat6250): It indicates that what comes after are options and not variables.
- Question (nly13-stat6250): Is it better to use the list option for comparing multiple variables for PROC Freq, rather than letting the standard cross?
- Question (kveng−stat6250): Instead of making a table, can PROC FREQ statement make a graph instead?
- *Question* (lwang30-stat6250) : How would SAS deal with the output if more than 2 variables are crosstabulated ?
- Question (cyuan10-stat6250): Can we still use PROC MEANS on qualititative variables?
- Question (yzhu12-stat6250): How does SAS sort among nocol, norow, nopercent?


[recipe_for_temporarily_binning_values (from Week 4 Overview)]
- Question (akumar30−stat6250): what is the scope of format in SAS ? (Limited to SAS session or Stored permanently in SAS)
- Question (mcardoso3-stat6250):  What context depends on the syntax for using a format?
- Question (dlee117−stat6250): When binning values, where should semi colon(s) be placed?
- Question (rluo-stat6250): Why is formats powerful in the SAS, and what can it achieve?
- Question (hhu9−stat6250): How many ways can make bins in SAS?
- Question (yyan11−stat6250): What different if the values are numbers?
- Answer (yyan11−stat6250): When the specified values are numeric values, they are not enclosed in quotation marks, and the format's name should not begin with a dollar sign ($). 
- Question (aoneill2-stat6250): What happens if bin values overlap? Does the program stop running?
- *Question* (yren10−stat6250): What situations we cannot be using formats?
- Question (meisenbach-stat6250): Isn’t it a bad idea to hard code the quantiles?
- Question (nly13-stat6250): If there is a ‘low’ and high’ value setting, is there something that indicates the mean or median for the range?
- Question (kveng−stat6250): How to make theese binning values permanent and store in somewhere?
- *Question* (lwang30-stat6250) : What is the change in the variable type after those 2 quantitative variables are formatted ?
- *Answer* (lwang30-stat6250) : Both the discrete and continuous quantitative variables are reformatted into categorical variables by *proc format* statement.
- Question (cyuan10-stat6250): Is a temporary variable created when you group variables? How do you make it permanent on the dataset?
- Question (yzhu12-stat6250): How do we handle with the missing data when we apply the low and high option?


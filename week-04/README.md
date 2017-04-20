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



[Course Textbook Chapter 7, Problem 4]
- Question (akumar30−stat6250): Can we define several formats in single proc format statement?
- Answer (akumar30−stat6250):  Yes, we can use multiple VALUE statements in a single PROC FORMAT step to define multiple formats.
- Question (mcardoso3-stat6250):  Are there any instatnces where a SAS line doesn't need to end in a semicolon?
- Question (dlee117−stat6250): What are your two options when using the PROC FORMAT statement?
- Answer (dlee117-stat6250): You can enter LIBRARY, which specifies the libref for a SAS library to contain a permanent catalog of user-defined formats, or FMTLIB, which displays a list of all of the formats in your catalog with descriptions.



[Course Textbook Chapter 7, Problem 5]
- Question (akumar30−stat6250):  Can we use combination of character and numeric values together to defining the VALUE range for format-name?
- Answer (akumar30−stat6250):  No, because formats themselves are either character or numeric.
- Question (mcardoso3-stat6250):  Do the values need to be in alphabetical/numerical in the VALUE statement?
- Question (dlee117−stat6250): When specifying a VALUE range, can you have a list of values that are a combination of character and numeric values?
- Answer (dlee117-stat6250): No, these values must be character values OR numeric values, not a combination. This is because formats themselves are either character or numeric.



[Course Textbook Chapter 7, Problem 6]
- Question (akumar30−stat6250): How to use apostrophe to appear in the label?
- Answer (akumar30−stat6250):  We can use two single quotation marks if we want an apostrophe to appear in the label.
- Question (mcardoso3-stat6250):  What would happen if there needs to be more characters than a label can provide?
- Question (dlee117−stat6250): Can you use numeric values in a label?



[Course Textbook Chapter 7, Problem 7]
- Question (akumar30−stat6250): What is the advantage of keyword OTHER to specify the variables range of a format?
- Answer (akumar30−stat6250):  The keyword OTHER is used to label missing values as well as any values that are not specifically addressed in a range.
- Question (mcardoso3-stat6250):  Given that there are keywords for the upper and lower limits of a variable's value range, is there any keyword that can specify the median of the range?
- Question (dlee117−stat6250): What is the point of using the LOW and HIGH keywords instead of using a low or high number?



[Course Textbook Chapter 7, Problem 8]
- Question (akumar30−stat6250): Can we reuse the format created in data step inside proc step?
- Question (mcardoso3-stat6250):  What is the purpose of using a PROC FORMAT statement in SAS?
- Answer (mcardoso3-stat6250):  PROC FORMAT statements are used to create a catalog of all formats in SAS, or to be stored in an existing format catalog under the SAS library.
- Question (dlee117−stat6250): When would you want to permanently associate a format with a variable?



[Course Textbook Chapter 8, Problem 1]
- Question (akumar30−stat6250): Can we get median and range as default statistics output of PROC MEANS statement?
- Answer (akumar30−stat6250):  No, you need to define MEDIAN and RANGE keywords in PROC MEANS statement to get the median and range of dataset.
- Question (mcardoso3-stat6250):  Why would knowing the standard deviation of a SAS dataset be more important to know by PROC MEANS than the median?
- Question (dlee117−stat6250): What is the difference between the MEANS procedure and the SUMMARY procedure?



[Course Textbook Chapter 8, Problem 2]
- Question (akumar30−stat6250): How to limit decimal places in PROC MEANS statement?
- Answer (akumar30−stat6250):  using option MAXDEC=n; where n specifies the maximum number of decimal places.
- Question (mcardoso3-stat6250):  What is the difference between the "var" command and the "by" and "class" commands?
- Answer (mcardoso3-stat6250):  "var" is meant to analyze variables, while "class" and "by" are used for categorizing observations.
- Question (dlee117−stat6250): If you have a large amount of similar variables (designated by different numbers), what can you do to make the task of listing out all of these variables less tedious?
- Answer (dlee117-stat6250): Instead of listing variables separately, you can use a numbered range of variables (i.e. item1-item5 instead of item1, item2, item3, item4, and item5).



[Course Textbook Chapter 8, Problem 4]
- Question (akumar30−stat6250): Why we need to sort the data first before using BY variable(s) statement?
- Question (mcardoso3-stat6250):  What happens if data wasn't previously sorted before using PROC MEANS with a BY group and would everything need to be redone?
- Question (dlee117−stat6250): When would you use the BY statement and when would you use the CLASS statement?



[Course Textbook Chapter 8, Problem 7]
- Question (akumar30−stat6250):  Is prior sorting required for PROC FREQ statement?
- Question (mcardoso3-stat6250):  What other columns would be useful for analysis if added to the PROC FREQ tables besides frequency and percentages?
- Question (dlee117−stat6250): What is recommended that you use when you use a PROC FREQ statement?



[Course Textbook Chapter 8, Problem 8]
- Question (akumar30−stat6250):  Which variables are most suitable for PROC FREQ Statements?
- Answer (akumar30−stat6250):  Frequency distributions work best with variables whose values can be described as categorical, and whose values are best summarized by counts rather than by averages.
- Question (mcardoso3-stat6250):  Why are categorical variables the best choice of variables for using PROC FREQ?
- Answer (mcardoso3-stat6250):  Categorical variables are the best option for using frequency distributions since numeric variables can be continous and therefore result in lengthy tables.  Unique values would also be unsuitable for PROC FREQ.
- Question (dlee117−stat6250): How do you determine the order that your variables are listed in the PROC FREQ report?



[Course Textbook Chapter 8, Problem 10]
- Question (akumar30−stat6250):  Can we restrict PROC FREQ output to not display Percent and Cumulative Percent Column?
- Question (mcardoso3-stat6250):  How many variables can be inputed for a two a PROC FREQ table?
- Question (dlee117−stat6250):When cross tabulations are specified, what are the four parameters produced by the PROC FREQ statement?



[recipe_for_summarizing_quantitative_values (from Week 4 Overview)]
- Question (akumar30−stat6250): Does SAS By default include observations with a missing value specified in CLASS or BY statement?      
- Answer (akumar30−stat6250): No, We need to specify MISSING statement to summarize the missing values.
- Question (mcardoso3-stat6250):  Why are no statistics explicitly listed in the options given in the PROC MEANS statement.
- Question (dlee117−stat6250): What is the default precision for the output and can you change the precision?



[recipe_for_summarizing_qualitative_values (from Week 4 Overview)]
- Question (akumar30−stat6250): What is the significance of using NLEVEL in PROC FREQ statement? 
- Question (mcardoso3-stat6250):  How were SAS codes run from the 1970s and were they inputed on a device before computers?
- Question (dlee117−stat6250): When and why would you want to use the NOPRINT statement?



[recipe_for_temporarily_binning_values (from Week 4 Overview)]
- Question (akumar30−stat6250): what is the scope of format in SAS ? (Limited to SAS session or Stored permanently in SAS)
- Question (mcardoso3-stat6250):  What context depends on the syntax for using a format?
- Question (dlee117−stat6250): When binning values, where should semi colon(s) be placed?



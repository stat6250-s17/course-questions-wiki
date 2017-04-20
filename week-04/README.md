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



[Course Textbook Chapter 7, Problem 4]
- Question (akumar30−stat6250): Can we define several formats in single proc format statement?
- Answer (akumar30−stat6250):  Yes, we can use multiple VALUE statements in a single PROC FORMAT step to define multiple formats.



[Course Textbook Chapter 7, Problem 5]
- Question (akumar30−stat6250):  Can we use combination of character and numeric values together to defining the VALUE range for format-name?
- Answer (akumar30−stat6250):  No, because formats themselves are either character or numeric.



[Course Textbook Chapter 7, Problem 6]
- Question (akumar30−stat6250): How to use apostrophe to appear in the label?
- Answer (akumar30−stat6250):  We can use two single quotation marks if we want an apostrophe to appear in the label.



[Course Textbook Chapter 7, Problem 7]
- Question (akumar30−stat6250): What is the advantage of keyword OTHER to specify the variables range of a format?
- Answer (akumar30−stat6250):  The keyword OTHER is used to label missing values as well as any values that are not specifically addressed in a range.



[Course Textbook Chapter 7, Problem 8]
- Question (akumar30−stat6250): Can we reuse the format created in data step inside proc step?



[Course Textbook Chapter 8, Problem 1]
- Question (akumar30−stat6250): Can we get median and range as default statistics output of PROC MEANS statement?
- Answer (akumar30−stat6250):  No, you need to define MEDIAN and RANGE keywords in PROC MEANS statement to get the median and range of dataset.



[Course Textbook Chapter 8, Problem 2]
- Question (akumar30−stat6250): How to limit decimal places in PROC MEANS statement?
- Answer (akumar30−stat6250):  using option MAXDEC=n; where n specifies the maximum number of decimal places.



[Course Textbook Chapter 8, Problem 4]
- Question (akumar30−stat6250): Why we need to sort the data first before using BY variable(s) statement?



[Course Textbook Chapter 8, Problem 7]
- Question (akumar30−stat6250):  Is prior sorting required for PROC FREQ statement?



[Course Textbook Chapter 8, Problem 8]
- Question (akumar30−stat6250):  Which variables are most suitable for PROC FREQ Statements?
- Answer (akumar30−stat6250):  Frequency distributions work best with variables whose values can be described as categorical, and whose values are best summarized by counts rather than by averages.



[Course Textbook Chapter 8, Problem 10]
- Question (akumar30−stat6250):  Can we restrict PROC FREQ output to not display Percent and Cumulative Percent Column?



[recipe_for_summarizing_quantitative_values (from Week 4 Overview)]
- Question (akumar30−stat6250): Does SAS By default include observations with a missing value specified in CLASS or BY statement?      
- Answer (akumar30−stat6250): No, We need to specify MISSING statement to summarize the missing values.



[recipe_for_summarizing_qualitative_values (from Week 4 Overview)]
- Question (akumar30−stat6250): What is the significance of using NLEVEL in PROC FREQ statement? 



[recipe_for_temporarily_binning_values discussed (from Week 4 Overview)]
- Question (akumar30−stat6250): what is the scope of format in SAS ? (Limited to SAS session or Stored permanently in SAS)



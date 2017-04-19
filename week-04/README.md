## Week 4 Quiz Questions and Answers

In order to prepare your Week 4 Quiz submission, please edit ***this*** document to provide substantive questions for each Quiz Problem and SAS Recipe listed below, as well as answers to at least three questions raised.

All edits should conform to GitHub Markdown specifications (https://guides.github.com/features/mastering-markdown/) and should be committed to a branch named "week-4" in your fork of this repo. Then, after all edits have been made/committed, your Week 4 Quiz should be submitted by initiating a pull request using

- the master branch of the stat6250/course_questions_wiki repo as the base fork and

- the week-4 branch of your version of the repo as the head fork.

The instructor will then review the pull request and make comments should further revision be needed. Then, after the contents of the pull request have been finalized without any merge conflicts, the instructor will merge the pull request.

********************************************************************************



[Course Textbook Chapter 7, Problem 3]
- Question (yyan11−stat6250): How to create a new format's name of the VALUE statement?
- Answer (yyan11−stat6250): Where format-name must begin with a dollar sign ($) if the format applies to character data, must be a valid SAS name, cannot be the name of an existing SAS format, cannot end in a number, does not end in a period when specified in a VALUE statement.



[Course Textbook Chapter 7, Problem 4]
- Question (yyan11−stat6250): How to write the FORMAT procedures?
- Answer (yyan11−stat6250): The statement begins with the keyword VALUE and ends with a semicolon after all the labels have been defined. 



[Course Textbook Chapter 7, Problem 5]
- Question (yyan11−stat6250): How many values could be displayed when use the VALUE statement to define a format?
- Answer (yyan11−stat6250): You can use the VALUE statement to define a format for displaying one or more values.



[Course Textbook Chapter 7, Problem 6]
- Question (yyan11−stat6250): How can I do if I want an apostrophe to appear on the label?
- Answer (yyan11−stat6250): Use two single quotation marks if you want an apostrophe to appear in the label.



[Course Textbook Chapter 7, Problem 7]
- Question (yyan11−stat6250): Which keyword can I use to specify the lower and upper limits of a variable's value range?
- Answer (yyan11−stat6250): You can also use the keywords LOW and HIGH to specify the lower and upper limits of a variable's value range. The keyword LOW does not include missing numeric values. The keyword OTHER can be used to label missing values as well as any values that are not specifically addressed in a range.



[Course Textbook Chapter 7, Problem 8]
- Question (yyan11−stat6250): Can I place the FORMAT statement in a DATA step?
- Answer (yyan11−stat6250): Yes, you can place the FORMAT statement in either a DATA step or a PROC step. By placing the FORMAT statement in a DATA step, you can permanently associate a format with a variable. Note that you do not have to specify a width value when using a user-defined format.



[Course Textbook Chapter 8, Problem 1]
- Question (yyan11−stat6250): What are the MEANS procedure when the default statistics produced?
- Answer (yyan11−stat6250): In its simplest form, PROC MEANS prints the n-count (number of nonmissing values), the mean, the standard deviation, and the minimum and maximum values of every numeric variable in a data set.



[Course Textbook Chapter 8, Problem 2]
- Question (yyan11−stat6250): What can I do when I want to focus on a few variables?



[Course Textbook Chapter 8, Problem 4]
- Question (yyan11−stat6250): The BY statement like the CLASS statement specifies variables to use for categorizing observations, are they same require?
- Answer (yyan11−stat6250): No, BY processing requires that your data already be sorted or indexed in the order of the BY variables. Unless data set observations are already sorted, you will need to run the SORT procedure before using PROC MEANS with any BY group.



[Course Textbook Chapter 8, Problem 7]
- Question (yyan11−stat6250): which data set variables could be created by the FREQ procedure?
- Answer (yyan11−stat6250): By default, the FREQ procedure creates frequency tables for every variable in your data set. To specify the variables to analyze, include them in a TABLES statement.



[Course Textbook Chapter 8, Problem 8]
- Question (yyan11−stat6250): Which variable is the best with frequency distributions work?
- Answer (yyan11−stat6250): The FREQ procedure creates frequency tables for every variable in your data set. But this isn't always what you want. A variable that has continuous numeric values—such as DateTime—can result in a lengthy and meaningless table. Likewise, a variable that has a unique value for each observation—such as FullName—is unsuitable for PROC FREQ processing. Frequency distributions work best with variables whose values can be described as categorical, and whose values are best summarized by counts rather than by averages.



[Course Textbook Chapter 8, Problem 10]
- Question (yyan11−stat6250): How to control the depth of crosstabulation results?
- Answer (yyan11−stat6250): NOFREQ suppresses cell frequencies, NOPERCENT suppresses cell percentages, NOROW suppresses row percentages, NOCOL suppresses column percentages.



[recipe_for_summarizing_quantitative_values (from Week 4 Overview)]
- Question (yyan11−stat6250): To limit decimal places, use the MAXDEC= option in the PROC MEANS statement. Is that have a maximum number?



[recipe_for_summarizing_qualitative_values (from Week 4 Overview)]
- Question (yyan11−stat6250): How many variables I can compute?



[recipe_for_temporarily_binning_values discussed (from Week 4 Overview)]
- Question (yyan11−stat6250): What different if the values are numbers?
- Answer (yyan11−stat6250): When the specified values are numeric values, they are not enclosed in quotation marks, and the format's name should not begin with a dollar sign ($). 



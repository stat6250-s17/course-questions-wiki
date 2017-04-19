## Week 4 Quiz Questions and Answers

In order to prepare your Week 4 Quiz submission, please edit ***this*** document to provide substantive questions for each Quiz Problem and SAS Recipe listed below, as well as answers to at least three questions raised.

All edits should conform to GitHub Markdown specifications (https://guides.github.com/features/mastering-markdown/) and should be committed to a branch named "week-4" in your fork of this repo. Then, after all edits have been made/committed, your Week 4 Quiz should be submitted by initiating a pull request using

- the master branch of the stat6250/course_questions_wiki repo as the base fork and

- the week-4 branch of your version of the repo as the head fork.

The instructor will then review the pull request and make comments should further revision be needed. Then, after the contents of the pull request have been finalized without any merge conflicts, the instructor will merge the pull request.

********************************************************************************



[Course Textbook Chapter 7, Problem 3]
- Question (mcardoso3-stat6250):  What is considered to be a VALUE statement when creating a format in Escape?
- Answer (mcardoso3-stat6250): A VALUE in SAS can be any set of numbers or letter characters that are enclosed in quotation marks, not a combination of letters and numbers nor any special characters (@,#,$).

[Course Textbook Chapter 7, Problem 4]
- Question (mcardoso3-stat6250):  Are there any instatnces where a SAS line doesn't need to end in a semicolon?

[Course Textbook Chapter 7, Problem 5]
- Question (mcardoso3-stat6250):  Do the values need to be in alphabetical/numerical in the VALUE statement?

[Course Textbook Chapter 7, Problem 6]
- Question (mcardoso3-stat6250):  What would happen if there needs to be more characters than a label can provide?

[Course Textbook Chapter 7, Problem 7]
- Question (mcardoso3-stat6250):  Given that there are keywords for the upper and lower limits of a variable's value range, is there any keyword that can specify the median of the range?

[Course Textbook Chapter 7, Problem 8]
- Question (mcardoso3-stat6250):  What is the purpose of using a PROC FORMAT statement in SAS?
- Answer (mcardoso3-stat6250):  PROC FORMAT statements are used to create a catalog of all formats in SAS, or to be stored in an existing format catalog under the SAS library.

[Course Textbook Chapter 8, Problem 1]
- Question (mcardoso3-stat6250):  Why would knowing the standard deviation of a SAS dataset be more important to know by PROC MEANS than the median?

[Course Textbook Chapter 8, Problem 2]
- Question (mcardoso3-stat6250):  What is the difference between the "var" command and the "by" and "class" commands?
- Answer (mcardoso3-stat6250):  "var" is meant to analyze variables, while "class" and "by" are used for categorizing observations.

[Course Textbook Chapter 8, Problem 4]
- Question (mcardoso3-stat6250):  What happens if data wasn't previously sorted before using PROC MEANS with a BY group and would everything need to be redone?

[Course Textbook Chapter 8, Problem 7]
- Question (mcardoso3-stat6250):  What other columns would be useful for analysis if added to the PROC FREQ tables besides frequency and percentages?

[Course Textbook Chapter 8, Problem 8]
- Question (mcardoso3-stat6250):  Why are categorical variables the best choice of variables for using PROC FREQ?
- Answer (mcardoso3-stat6250):  Categorical variables are the best option for using frequency distributions since numeric variables can be continous and therefore result in lengthy tables.  Unique values would also be unsuitable for PROC FREQ.

[Course Textbook Chapter 8, Problem 10]
- Question (mcardoso3-stat6250):  How many variables can be inputed for a two a PROC FREQ table?

[recipe_for_summarizing_quantitative_values, (from week 4 overview)]
- Question (mcardoso3-stat6250):  Why are no statistics explicitly listed in the options given in the PROC MEANS statement.

[recipe_for_summarizing_qualitative_values, (from week 4 overview)]
- Question (mcardoso3-stat6250):  How were SAS codes run from the 1970s and were they inputed on a device before computers?

[recipe_for_temporarily_binning_values, (from week 4 overview)]
- Question (mcardoso3-stat6250):  What context depends on the syntax for using a format?

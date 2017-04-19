## Week 4 Quiz Questions and Answers

In order to prepare your Week 4 Quiz submission, please edit ***this*** document to provide substantive questions for each Quiz Problem and SAS Recipe listed below, as well as answers to at least three questions raised.

All edits should conform to GitHub Markdown specifications (https://guides.github.com/features/mastering-markdown/) and should be committed to a branch named "week-4" in your fork of this repo. Then, after all edits have been made/committed, your Week 4 Quiz should be submitted by initiating a pull request using

- the master branch of the stat6250/course_questions_wiki repo as the base fork and

- the week-4 branch of your version of the repo as the head fork.

The instructor will then review the pull request and make comments should further revision be needed. Then, after the contents of the pull request have been finalized without any merge conflicts, the instructor will merge the pull request.

********************************************************************************



[Course Textbook Chapter 7, Problem 3]
- Question (aoneill2-stat6250): Is there a way to permanently assign a libref statement for a user-defined library?


[Course Textbook Chapter 7, Problem 4]
- Question (aoneill2-stat6250): What kind of error is generated if the proc format statement is lacking a semicolon or has one too many? 


[Course Textbook Chapter 7, Problem 5]
- Question (aoneill2-stat6250): Is it possible to mix numbers and characters in a range of values in a user-defined proc format statement?
- Answer (aoneill2-stat6250): No, it is not possible to mix them. A character format name must start with a $ sign.


[Course Textbook Chapter 7, Problem 6]
- Question (aoneill2-stat6250): Why must a label specifically be limited to 256 characters? Is that the byte size?


[Course Textbook Chapter 7, Problem 7]
- Question (aoneill2-stat6250): Are missing values included in "low" values?
- Answer (aoneill2-stat6250): Yes, missing values can be included in "low" values, as it includes anything lower than the specified value as well as any 'other' missing values.


[Course Textbook Chapter 7, Problem 8]
- Question (aoneill2-stat6250): Are FORMAT statements permanently available to a SAS program when they are included in the DATA step or in the PROC step or both?
- Question (aoneill2-stat6250): FORMAT statements are only made permantently available to a SAS program when they are cinluded in the DATA step.


[Course Textbook Chapter 8, Problem 1]
- Question (aoneill2-stat6250): What statistical measures do you get from the PROC MEANS statement if no specific measures are included in the statement?



[Course Textbook Chapter 8, Problem 2]
- Question (aoneill2-stat6250): What is the primary difference between specifying variables with the var statement and the class statement?


[Course Textbook Chapter 8, Problem 4]
- Question (aoneill2-stat6250): Can BY statements be used in other commands besides PROC MEANS?



[Course Textbook Chapter 8, Problem 7]
- Question (aoneill2-stat6250): Why are categorical variables the best choice for table values in a PROC FREQ statement?


[Course Textbook Chapter 8, Problem 8]
- Question (aoneill2-stat6250): What is the greatest barrier to using continuous variables for frequency distributions?


[Course Textbook Chapter 8, Problem 10]
- Question (aoneill2-stat6250): When would it be advantageous to specify no rows or no columns in a PROC FREQ statement when generating a table?


[recipe_for_summarizing_quantitative_values (from Week 4 Overview)]
- Question (aoneill2-stat6250): Are PROC FREQ statements most effective for summarizing quantitative values?

[recipe_for_summarizing_qualitative_values (from Week 4 Overview)]
- Question (aoneill2-stat6250): What types of PROC FORMAT statements are most effective for summarizing qualitative data?


[recipe_for_temporarily_binning_values discussed (from Week 4 Overview)]
- Question (aoneill2-stat6250): What happens if bin values overlap? Does the program stop running?



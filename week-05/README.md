## Week 5 Quiz Questions and Answers

In order to prepare your Week 5 Quiz submission, please edit ***this*** document to provide substantive questions for each Quiz Problem and SAS Recipe listed below, as well as answers to at least three questions raised.

All edits should conform to GitHub Markdown specifications (https://guides.github.com/features/mastering-markdown/) and should be committed to a branch named "week-5" in your fork of this repo. Then, after all edits have been made/committed, your Week 5 Quiz should be submitted by initiating a pull request using

- the master branch of the stat6250/course_questions_wiki repo as the base fork and

- the week-5 branch of your version of the repo as the head fork.

The instructor will then review the pull request and make comments should further revision be needed. Then, after the contents of the pull request have been finalized without any merge conflicts, the instructor will merge the pull request.

********************************************************************************



[Course Textbook Chapter 5, Problem 1]
- Question (nly13-stat6250): Is there a limit to the types of files we can associate to?


[Course Textbook Chapter 5, Problem 2]
- Question (nly13-stat6250): Will Fileref be in effect if you save your SAS session?
- Answer (nly13-stat6250): No, it ends when the SAS session ends.

[Course Textbook Chapter 5, Problem 6]
- Question (nly13-stat6250): In the INPUT statement, what does the $ represent?
-	Answer (nly13-stat6250): The $ is used to label variables as characters.



[Course Textbook Chapter 5, Problem 7]
- Question (nly13-stat6250): When assigning the range for characters, what happens if there is overlap? Example 1-3 and 3-6.


[Course Textbook Chapter 5, Problem 8]
- Question (nly13-stat6250): Will income=income+income; generate the same result?


[Course Textbook Chapter 6, Problem 1]
- Question (nly13-stat6250): What types of variables can be used in a data vector?


[Course Textbook Chapter 6, Problem 2]
- Question (nly13-stat6250): Why do format errors not count as a syntax error?


[Course Textbook Chapter 6, Problem 3]
- Question (nly13-stat6250): Can a Data step be executed more than once for each record in the input file?


[Course Textbook Chapter 6, Problem 4]
- Question (nly13-stat6250): Can you extract the _N_ value?


[Course Textbook Chapter 6, Problem 5]
- Question (nly13-stat6250): Can you extract the _ERROR_ value?


[Course Textbook Chapter 6, Problem 6]
- Question (nly13-stat6250): Why are variables in the program data vector created in programming statements reset to missing at the end of the DATA step?


[basic_recipe_for_creating_analytic_datasets (from Week 5 Overview)]
- Question (nly13-stat6250): If retain and keep have to be the same, why isn’t there a single statement that is simplified to do both? 
-	Answer (nly13-stat6250): The simplified version would be proc sql, uses less code for same result, however it is limited by memory.


[optional: adv_recipe_for_creating_analytic_datasets (from Week 5 Overview)]
- Question (nly13-stat6250): What is the memory limit to proc sql?

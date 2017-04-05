## Course Structure Quiz Problems

This document should be edited to provide substantive questions for each Quiz Problem and SAS Recipe listed below, as well as answers to at least three questions raised.

All edits should conform to GitHub Markdown specifications (https://guides.github.com/features/mastering-markdown/) and should be committed to a branch named "week-02" in your fork of this repo. Then, after all edits have been made/committed, your Week 2 Quiz should be submitted by initiating a pull request using

- the master branch of the stat6250/course_questions_wiki repo as the base fork and

- the week-02 branch of your version of the repo as the head fork.

The instructor will then review the pull request and make comments should further revision be needed. Then, after the contents of the pull request have been finalized without any merge conflicts, the instructor will merge the pull request.

********************************************************************************


[Course Textbook Chapter 1, Problem 1]
- Question (cyuan10−stat6250): Is the observations always the “rows” and variable always the columns?

[Course Textbook Chapter 1, Problem 2]
- Question (cyuan10−stat6250): In this example, what is the difference between having 3 different “steps” or “runs” versus a single run at the end?

[Course Textbook Chapter 1, Problem 3]
- Question (cyuan10-stat6250): If a single cell contains characters, does that make the entire column a “character variable”?

[Course Textbook Chapter 1, Problem 4]
- Question (cyuan10−stat6250): What happens to the “.” missing numeric value when you calculate that variable? Is it simply ignored? What is the default action?

[Course Textbook Chapter 1, Problem 5]
- Question (cyuan10−stat6250): Are variable names case-sensitive and what other ‘rules’ or ‘guidelines’ are there around what makes a good variable name?
- Answer (cyuan10−stat6250): Some basic rule is to name the file so that you the user or any other users will understand what it is. Use case or “_” to help distinguish between words.

[Course Textbook Chapter 1, Problem 8]
- Question (cyuan10−stat6250): In this example, does a leading “0” count as part of the length? For example, is 097.45 a different length than 97.45? 

[Course Textbook Chapter 2, Problem 3]
- Question (cyuan10−stat6250): How do we deal with a larger year range? For example 1800-2000? 

[Course Textbook Chapter 2, Problem 7]
- Question (cyuan10−stat6250): What are the different use cases for a permanent library vs. a temporary library?
- Answer (cyuan10−stat6250): Having a permanent library vs. a temporary library would be helpful to keep things organized so that you don’t end up with 20 versions. Instead, you can work on 20 different versions during the same sessions and make the “final” version a permanent but delete all the temp. This will keep your files organized.

[Course Textbook Chapter 2, Problem 8]
- Question (cyuan10−stat6250): Does the YEARCUTOFF= option always start from the low-end and count up or can it start from the high end and count down?

[Course Textbook Chapter 2, Problem 9]
- Question (cyuan10−stat6250): Are all syntax written in all CAPs?
- Answer (cyuan10−stat6250): No, like all programming languages, there are different ways of distinguish between synatx. It looks like the text uses all caps to help show the difference.

[basic_recipe_for_loading_data_from_remote_Excel_file (from Week 2 Overview)]
- Question (cyuan10−stat6250): What is the difference between a comma-separated values format vs. a tab-separate values format and how does this affect how the dataset is “read” in SAS?

[optional: bonus_advanced_recipe_for_loading_data_from_remote_Excel_file (from Week 2 Overview)]
- Question (cyuan10−stat6250): Does this macro only compare names? Is there a way to compare the content within so that if there are two versions, the users to check to see if the content is different?


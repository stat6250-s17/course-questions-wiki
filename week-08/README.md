## Week 8 Quiz Questions and Answers

In order to prepare your Week 8 Quiz submission, please edit ***this*** document to provide substantive questions for each Quiz Problem and SAS Recipe listed below, as well as answers to at least three questions raised.

All edits should conform to GitHub Markdown specifications (https://guides.github.com/features/mastering-markdown/) and should be committed to a branch named "week-8" in your fork of this repo. Then, after all edits have been made/committed, your Week 8 Quiz should be submitted by initiating a pull request using

- the master branch of the stat6250/course_questions_wiki repo as the base fork and

- the week-8 branch of your version of the repo as the head fork.

The instructor will then review the pull request and make comments should further revision be needed. Then, after the contents of the pull request have been finalized without any merge conflicts, the instructor will merge the pull request.

********************************************************************************



[Course Textbook Chapter 13, Problem 1]
- Question (cyuan10-stat6250): Is there a way to write the code is that you can specify to calculate all the variables or do we have to list them all out individually?


[Course Textbook Chapter 13, Problem 2]
- Question (cyuan10-stat6250): What happens if we have two numeric of different lengths?
- Answer (cyuan10-stat6250): SAS will automatically return a data that has the length of the longest numeric input.



[Course Textbook Chapter 13, Problem 3]
- Question (cyuan10-stat6250): Does the width of the input include the comma?
- Answer (cyuan10-stat6250): Yes, for example 123,456 is a comma7 because the "," is read.



[Course Textbook Chapter 13, Problem 4]
- Question (cyuan10-stat6250): In these cases, if we wish for SAS to include a ending zero such as "12.30", how do we specify it?



[Course Textbook Chapter 13, Problem 5]
- Question (cyuan10-stat6250): What happens if you only use (1,3,20) for MDY?
- Answer (cyuan10-stat6250): Since the YEARCUTOFF is defaulted to 1920, then your output would display 1920 instead of 2020.



[Course Textbook Chapter 13, Problem 6]
- Question (cyuan10-stat6250): If the character data includes a number, will the scan function automatically create a new numeric variable?



[Course Textbook Chapter 13, Problem 7]
- Question (cyuan10-stat6250): How do you deal with data where similar information is stored in different parts/length of a single variable?



[Course Textbook Chapter 13, Problem 10]
- Question (cyuan10-stat6250): Since the old area code and the new area code both start with '9', then technically, can we only change the last two digits?



[recipe_for_isolating_all_duplicates (from Week 8 Overview)]
- Question (cyuan10-stat6250): Then the sort function includes 3 variables, then does it proceed to sort in order of how the variables are listed?



[recipe_for_drop_and_swap (from Week 8 Overview)]
- Question (cyuan10-stat6250): For what reasons do we create a temporary varaible name High_Grade_character for High_Grade and what does does it play in the data step?


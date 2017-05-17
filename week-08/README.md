## Week 8 Quiz Questions and Answers

In order to prepare your Week 8 Quiz submission, please edit ***this*** document to provide substantive questions for each Quiz Problem and SAS Recipe listed below, as well as answers to at least three questions raised.

All edits should conform to GitHub Markdown specifications (https://guides.github.com/features/mastering-markdown/) and should be committed to a branch named "week-8" in your fork of this repo. Then, after all edits have been made/committed, your Week 8 Quiz should be submitted by initiating a pull request using

- the master branch of the stat6250/course_questions_wiki repo as the base fork and

- the week-8 branch of your version of the repo as the head fork.

The instructor will then review the pull request and make comments should further revision be needed. Then, after the contents of the pull request have been finalized without any merge conflicts, the instructor will merge the pull request.

********************************************************************************



[Course Textbook Chapter 13, Problem 1]
- Question (meisenbach-stat6250): What happends if you specify var1-var4 and var3 does not exist?



[Course Textbook Chapter 13, Problem 2]
- Question (meisenbach-stat6250): Why should you not rely on automatic conversion?
- Answer (meisenbach-stat6250): Sometimes SAS is unable to do the conversion (e.g. the PayRate contains a dollar sign).



[Course Textbook Chapter 13, Problem 3]
- Question (meisenbach-stat6250): Does the width in an INFORMAT count the comma?
- Answer (meisenbach-stat6250): Yes, comma7 = 123,456



[Course Textbook Chapter 13, Problem 4]
- Question (meisenbach-stat6250): Does using PUT change the type of the original variable?



[Course Textbook Chapter 13, Problem 5]
- Question (meisenbach-stat6250): What does YEARCUTOFF specify?
- Answer (meisenbach-stat6250): YEARCUTOFF specifies the first year of the 100 year span.



[Course Textbook Chapter 13, Problem 6]
- Question (meisenbach-stat6250): What does the SCAN function do?
- Answer (meisenbach-stat6250): The SCAN function is used to extract words using blanks and commas. The second argument is the nth word.



[Course Textbook Chapter 13, Problem 7]
- Question (meisenbach-stat6250): What happens when you do not give the number of characters to extract?
- Answer (meisenbach-stat6250): You get the rest of the string.



[Course Textbook Chapter 13, Problem 10]
- Question (meisenbach-stat6250): Is it necessary to lowercase the variable that you are searching in?
- Answer (meisenbach-stat6250): No but it’s safer to do so.



[recipe_for_isolating_all_duplicates (from Week 8 Overview)]
- Question (meisenbach-stat6250): What is the benefit of using this method for removing duplicate row?
- Answer (meisenbach-stat6250): This method outputs all row which have duplicate key values and allows you to review them.



[recipe_for_drop_and_swap (from Week 8 Overview)]
- Question (meisenbach-stat6250): Why is it necessary to rename the High_Grade variable?
- Answer (meisenbach-stat6250): This is necesary in order to be able to create a new numeric variable with the same name.



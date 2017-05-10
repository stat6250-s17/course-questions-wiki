## Week 7 Quiz Questions and Answers

In order to prepare your Week 7 Quiz submission, please edit ***this*** document to provide substantive questions for each Quiz Problem and SAS Recipe listed below, as well as answers to at least three questions raised.

All edits should conform to GitHub Markdown specifications (https://guides.github.com/features/mastering-markdown/) and should be committed to a branch named "week-7" in your fork of this repo. Then, after all edits have been made/committed, your Week 7 Quiz should be submitted by initiating a pull request using

- the master branch of the stat6250/course_questions_wiki repo as the base fork and

- the week-7 branch of your version of the repo as the head fork.

The instructor will then review the pull request and make comments should further revision be needed. Then, after the contents of the pull request have been finalized without any merge conflicts, the instructor will merge the pull request.

********************************************************************************



[Course Textbook Chapter 10, Problem 2]
- Question (meisenbach-stat6250): Do temporary labels and formats override permanent labels and formats?
- Answer (meisenbach-stat6250): Yes, they do.


[Course Textbook Chapter 10, Problem 6]
- Question (meisenbach-stat6250): When evaluating if a string matches, does case matter?
- Answer (meisenbach-stat6250): Yes, it does.



[Course Textbook Chapter 10, Problem 7]
- Question (meisenbach-stat6250): How is variable length determined?



[Course Textbook Chapter 10, Problem 8]
- Question (meisenbach-stat6250): How does SAS evaluate a stand alone character variable in a condition?



[Course Textbook Chapter 10, Problem 9]
- Question (meisenbach-stat6250): Where should the LENGTH statement be?
- Answer (meisenbach-stat6250): Before any references to the variable in the DATA step.



[Course Textbook Chapter 10, Problem 10]
- Question (meisenbach-stat6250): Can you use DROP or KEEP statements in a PROC step?
- Answer (meisenbach-stat6250): No, you cannot.



[Course Textbook Chapter 11, Problem 1]
- Question (meisenbach-stat6250): Which dataset is specified by the DATE statement?
- Answer (meisenbach-stat6250): The new dataset. The dataset to be read from is assigned by the SET statement.



[Course Textbook Chapter 11, Problem 2]
- Question (meisenbach-stat6250): What happens if you DROP a variable in the SET statement and then reference it?



[Course Textbook Chapter 11, Problem 3]
- Question (meisenbach-stat6250): What kind of variable are FIRST. and LAST.?
- Answer (meisenbach-stat6250): FIRST. and LAST. are temporary variables.



[Course Textbook Chapter 11, Problem 8]
- Question (meisenbach-stat6250): Why does the “if last” statement do?



[Course Textbook Chapter 11, Problem 9]
- Question (meisenbach-stat6250): How are the variables for the Program Data Vector determined?
- Answer (meisenbach-stat6250): From the SET statement and from any variable created in the DATA steps



[basic_recipe_for_combining_data_vertically (from Week 7 Overview)]
- Question (meisenbach-stat6250): How does the IN= data set option work?
- Answer (meisenbach-stat6250): Syntax: IN=variable, This names the new variable whose value indicates whether the input data set contributed data to the current observation.



[optional: adv_recipe_for_combining_data_vertically (from Week 7 Overview)]
- Question (meisenbach-stat6250): What does the AS keyword do in a PROC SQL SELECT statement?
- Answer (meisenbach-stat6250): Syntax: value AS variable. The AS keyword allows you to set the value of a new variable.



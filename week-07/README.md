## Week 7 Quiz Questions and Answers

In order to prepare your Week 7 Quiz submission, please edit ***this*** document to provide substantive questions for each Quiz Problem and SAS Recipe listed below, as well as answers to at least three questions raised.

All edits should conform to GitHub Markdown specifications (https://guides.github.com/features/mastering-markdown/) and should be committed to a branch named "week-7" in your fork of this repo. Then, after all edits have been made/committed, your Week 7 Quiz should be submitted by initiating a pull request using

- the master branch of the stat6250/course_questions_wiki repo as the base fork and

- the week-7 branch of your version of the repo as the head fork.

The instructor will then review the pull request and make comments should further revision be needed. Then, after the contents of the pull request have been finalized without any merge conflicts, the instructor will merge the pull request.

********************************************************************************



[Course Textbook Chapter 10, Problem 2]
- Question (aoneill2-stat6250): Is the formatting in an input statement in a DATA step overridden by a format statement in the DATA step?
- Answer (aoneill2-stat6250): Yes, a Format statement in a DATA step is a permanent formatting assignment.


[Course Textbook Chapter 10, Problem 6]
- Question (aoneill2-stat6250): Are two if statements the same as an if-else statement?
- Answer (aoneill2-stat6250): The effect is the same in terms of the results, but the processing is different. In a series of if statements, every if statement is evaluated by the compiler. In an if-else construction, once there is a condition satisfied as true, the rest of the conditional statements are not evaluated.



[Course Textbook Chapter 10, Problem 7]
- Question (aoneill2-stat6250): What is the difference in programming protocol between declaring the length of a variable implicitly in its first reference in a data set or in an assignment statement and using a LENGTH statement, or are they used interchangeably?




[Course Textbook Chapter 10, Problem 8]
- Question (aoneill2-stat6250): Can if statements be viewed as program control structures?
- Answer (aoneill2-stat6250): Yes, especially in conjunction with if-else structures. If statements are all evaluated, and this makes a difference in the number of statements that can be evaluated or result in variables being assigned values. 



[Course Textbook Chapter 10, Problem 9]
- Question (aoneill2-stat6250):  Are statements concerning length of variable data in a data step permanent or non-permanent assignments? 





[Course Textbook Chapter 10, Problem 10]
- Question (aoneill2-stat6250): Can a variable be dropped in a data step in which it has been used for a calculation without producing an error?
- Answer (aoneill2-stat6250): No. When you drop a variable in a DATA step but not in the DATA statement itself, it removes the variable and its data from being accessed by the DATA step.



[Course Textbook Chapter 11, Problem 1]
- Question (aoneill2-stat6250): Do variables referenced in a data file in a set statement within a DATA step need to be explicitly kept or dropped?


[Course Textbook Chapter 11, Problem 2]
- Question (aoneill2-stat6250): When creating an output file in a DATA statement, is there an error if no variables are explicitly kept or dropped?


[Course Textbook Chapter 11, Problem 3]
- Question (aoneill2-stat6250): How can the sort process help create subtotals for variables by which the data set is sorted by?
- Answer (aoneill2-stat6250): The sort process creates "first." and "last." extenuated variables that can be used with the by-variable name appended to them and used in if statements to determine whether you have hit the first of a list or the last of a list to begin an operation or to end one.


[Course Textbook Chapter 11, Problem 8]
- Question (aoneill2-stat6250): How can you create an end-of-file marker when reading in a list of values?
- Answer (aoneill2-stat6250): You can solve the problem by assigning a value to the end of file variable, "end".


[Course Textbook Chapter 11, Problem 9]
- Question (aoneill2-stat6250): How can the program data vector and its population of values as the program steps through the code be useful in debugging a program?


[basic_recipe_for_combining_data_vertically (from Week 7 Overview)]
- Question (aoneill2-stat6250): How can one create useful data structures to evaluate business logic in combining data files vertically?
- Answer (aoneill2-stat6250): An "in" (for "in-file") variable is created along with a datasource variable that holds a reference to the file. The in-variable then gets assigned a value of 1 if the data comes from the indicated file and 0 if not, which can further be used in a business analysis scheme regarding the file through the use of the datasource variable assignment.


[optional: adv_recipe_for_combining_data_vertically (from Week 7 Overview)]



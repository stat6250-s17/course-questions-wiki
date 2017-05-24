## Week 9 Quiz Questions and Answers

In order to prepare your Week 9 Quiz submission, please edit ***this*** document to provide substantive questions for each Quiz Problem and SAS Recipe listed below, as well as answers to at least three questions raised.

All edits should conform to GitHub Markdown specifications (https://guides.github.com/features/mastering-markdown/) and should be committed to a branch named "week-9" in your fork of this repo. Then, after all edits have been made/committed, your Week 9 Quiz should be submitted by initiating a pull request using

- the master branch of the stat6250/course_questions_wiki repo as the base fork and

- the week-9 branch of your version of the repo as the head fork.

The instructor will then review the pull request and make comments should further revision be needed. Then, after the contents of the pull request have been finalized without any merge conflicts, the instructor will merge the pull request.

********************************************************************************



[Course Textbook Chapter 14, Problem 1]
- Question (cyuan10-stat6250): Are there any example of statement that can be used to combine DATA and PROC steps?



[Course Textbook Chapter 14, Problem 2]
- Question (cyuan10-stat6250): If the BY statement is not included in the Do loop, what happens?
Answer: Then it will default to 1 unit increments.



[Course Textbook Chapter 14, Problem 3]
- Question (cyuan10-stat6250): Can the BY statement be anything other than numeric? Does it have it be integers?




[Course Textbook Chapter 14, Problem 4]
- Question (cyuan10-stat6250): What if we used DO UNTIL instead? Would the stored YEAR be different? 



[Course Textbook Chapter 14, Problem 5]
- Question (cyuan10-stat6250): What happens when you include the OUTPUT statement?
- Answer (cyuan10-stat6250): When the OUTPUT statement is included, then it will print the output for each iteration otherwise, the default is one single output.



[Course Textbook Chapter 14, Problem 6]
- Question (cyuan10-stat6250): Are increments always necessary and what if you want to do a loop where the iteration is not based on a numeric variable?



[Course Textbook Chapter 14, Problem 7]
- Question (cyuan10-stat6250): How does SAS know where in the code is part of the Do loop and should be executed as such?
- Answer (cyuan10-stat6250): The “Do” statement will start the loop and “End;” will stop the loop. Anything within the these two statements are part of the loop



[Course Textbook Chapter 14, Problem 8]
- Question (cyuan10-stat6250): What is the difference between DO WHILE and DO UNTIL?



[Course Textbook Chapter 14, Problem 9]
- Question (cyuan10-stat6250): What happens when you accidentally excuse an infinite Do loop?



[Course Textbook Chapter 14, Problem 10]
- Question (cyuan10-stat6250): Can you have multiple nested DO UNTIL and DO WHILE loops?



[Course Textbook Chapter 15, Problem 1]
- Question (cyuan10-stat6250): What is an “executable” statement?



[Course Textbook Chapter 15, Problem 2]
- Question (cyuan10-stat6250): Are brackets, parentheses, and braces interchangeable? Is there a benefit of one over the others?



[Course Textbook Chapter 15, Problem 3]
- Question (cyuan10-stat6250): What is the benefit of creating arrays? 
- Answer (cyuan10-stat6250): You can use them in Do Loops.



[Course Textbook Chapter 15, Problem 4]
- Question (cyuan10-stat6250): Does the index refer to the order in which the variables are listed or it’s alphabetical order?



[Course Textbook Chapter 15, Problem 5]
- Question (cyuan10-stat6250): Does the * represent “all” in other statements too?



[Course Textbook Chapter 15, Problem 6]
- Question (cyuan10-stat6250): Can variables be continuous values?



[Course Textbook Chapter 15, Problem 7]
- Question (cyuan10-stat6250): In this example, is the output a single value? Do we need to include output statement to print the output of each iteration?



[Course Textbook Chapter 15, Problem 8]
- Question (cyuan10-stat6250): What is the difference between this array with numeric variables vs. using an index with increments of 300?



[Course Textbook Chapter 15, Problem 9]
- Question (cyuan10-stat6250): What if the increments in the array is not equal or linear?



[recipe_to_create_unique_record_id (from Week 9 Overview)]
- Question (cyuan10-stat6250): For concatenating string values, can “+” be used instead?



[recipe_to_disaggregate_counts_data (from Week 9 Overview)]
- Question (cyuan10-stat6250): What is the benefit of disaggregate data and when would we use it?

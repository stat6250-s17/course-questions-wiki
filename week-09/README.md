## Week 9 Quiz Questions and Answers

In order to prepare your Week 9 Quiz submission, please edit ***this*** document to provide substantive questions for each Quiz Problem and SAS Recipe listed below, as well as answers to at least three questions raised.

All edits should conform to GitHub Markdown specifications (https://guides.github.com/features/mastering-markdown/) and should be committed to a branch named "week-9" in your fork of this repo. Then, after all edits have been made/committed, your Week 9 Quiz should be submitted by initiating a pull request using

- the master branch of the stat6250/course_questions_wiki repo as the base fork and

- the week-9 branch of your version of the repo as the head fork.

The instructor will then review the pull request and make comments should further revision be needed. Then, after the contents of the pull request have been finalized without any merge conflicts, the instructor will merge the pull request.

********************************************************************************



[Course Textbook Chapter 14, Problem 1]
- Question (yzhu12-stat6250): If you do not specify a BY clause, what is the increment value for DO loops?
- Answer (yzhu12-stat6250): The increment value for DO loops is 1.



[Course Textbook Chapter 14, Problem 2]
- Question (yzhu12-stat6250): Why the index variables can be dropped from the data set?



[Course Textbook Chapter 14, Problem 3]
- Question (yzhu12-stat6250): How can you make it easier to manage nested DO loops?
- Answer (yzhu12-stat6250): You can indent the statements in each loop.



[Course Textbook Chapter 14, Problem 4]
- Question (yzhu12-stat6250): Under what situations that we use DO WHILE and DO UNTIL statements?
- Answer (yzhu12-stat6250): DO WHILE and DO UNTIL statements can be used within iterative DO loops to combine conditional and unconditional execution. 



[Course Textbook Chapter 14, Problem 5]
- Question (yzhu12-stat6250): What's the difference between DO WHILE and DO UNTIL statements?
- Answer (yzhu12-stat6250): The DO UNTIL statement executes a DO loop until a condition becomes true while the DO WHILE statement is used to execute a DO loop while a condition is true.



[Course Textbook Chapter 14, Problem 6]
- Question (yzhu12-stat6250): How can you run DO loops within DO loops?
- Answer (yzhu12-stat6250):  You assign a unique index variable to each loop and terminate each DO loop with its own END statement. 



[Course Textbook Chapter 14, Problem 7]
- Question (yzhu12-stat6250):  Once the loop's index value exceeds the stop value, the DO loop stops, and processing continues with the following DATA step statement. So how can we re-open the previous Do loop if necessary?



[Course Textbook Chapter 14, Problem 8]
- Question (yzhu12-stat6250): Why the start value must be greater than the stop value when you decrement a DO loop by specifying a negative value for the BY clause? What kind of error will occur if the request is not fulfilled?



[Course Textbook Chapter 14, Problem 9]
- Question (yzhu12-stat6250): How can you specify that how many times that a DO loop executes?
- Answer (yzhu12-stat6250): You can specify how many times a DO loop executes by listing items in a series.



[Course Textbook Chapter 14, Problem 10]
- Question (yzhu12-stat6250): How to construct an iterative DO loop?
- Answer (yzhu12-stat6250): By specifying an index variable and the conditions that will execute the loop. 



[Course Textbook Chapter 15, Problem 1]
- Question (yzhu12-stat6250): What will happen if you using the name of a SAS function as an array name?
- Answer (yzhu12-stat6250): The array will be correct, but you won't be able to use the function in the same DATA step, and a warning will be written to the SAS log.



[Course Textbook Chapter 15, Problem 2]
- Question (yzhu12-stat6250): How can you indicate the dimension of a one-dimensional array?
- Answer (yzhu12-stat6250): You can indicate the dimension of a one-dimensional array with an asterisk (*) as long as you specify the elements of the array. 



[Course Textbook Chapter 15, Problem 3]
- Question (yzhu12-stat6250): How can you create temporary array elements for DATA step processing without creating additional variables?
- Answer (yzhu12-stat6250): You can specify _TEMPORARY_ after the array name and dimension.



[Course Textbook Chapter 15, Problem 4]
- Question (yzhu12-stat6250): How to define a multidimensional array?
- Answer (yzhu12-stat6250): You can specify the number of elements in each dimension, separated by a comma. 



[Course Textbook Chapter 15, Problem 5]
- Question (yzhu12-stat6250): You can create temporary array elements for DATA step processing without creating additional variables, but what step you must take then?
- Answer (yzhu12-stat6250): You need to specify _TEMPORARY_ after the array name and dimension.



[Course Textbook Chapter 15, Problem 6]
- Question (yzhu12-stat6250): Why do we have to enclose each value in quotation marks when assigning initial values to character variables? Which error will occur if we fail to do so?



[Course Textbook Chapter 15, Problem 7]
- Question (yzhu12-stat6250): How to create an array of character variables?
- Answer (yzhu12-stat6250): You can add a dollar sign ($) after the array dimension.



[Course Textbook Chapter 15, Problem 8]
- Question (yzhu12-stat6250): Why you don't have to re-specify the stop value of a DO statement if you change the dimension of the array when you use the DIM function?



[Course Textbook Chapter 15, Problem 9]
- Question (yzhu12-stat6250): What is the purpose of a SAS array?
- Answer (yzhu12-stat6250): An array is a temporary grouping of variables under a single name. This can reduce the number of statements needed to process variables and can simplify the maintenance of DATA step programs. 



[recipe_to_create_unique_record_id (from Week 9 Overview)]
- Question (yzhu12-stat6250): How can we convert some particular numeric to character and which statement do we use to convert character to numeric?



[recipe_to_disaggregate_counts_data (from Week 9 Overview)]
- Question (yzhu12-stat6250): How can we tell if the data is a fine data so that we can coombine it with other dataset and input into something like proc mean or proc freq?



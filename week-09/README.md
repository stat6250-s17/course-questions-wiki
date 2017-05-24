## Week 9 Quiz Questions and Answers

In order to prepare your Week 9 Quiz submission, please edit ***this*** document to provide substantive questions for each Quiz Problem and SAS Recipe listed below, as well as answers to at least three questions raised.

All edits should conform to GitHub Markdown specifications (https://guides.github.com/features/mastering-markdown/) and should be committed to a branch named "week-9" in your fork of this repo. Then, after all edits have been made/committed, your Week 9 Quiz should be submitted by initiating a pull request using

- the master branch of the stat6250/course_questions_wiki repo as the base fork and

- the week-9 branch of your version of the repo as the head fork.

The instructor will then review the pull request and make comments should further revision be needed. Then, after the contents of the pull request have been finalized without any merge conflicts, the instructor will merge the pull request.

********************************************************************************



[Course Textbook Chapter 14, Problem 1]
- Question (yyan11−stat6250): What is a DO loop?
- Answer (yyan11−stat6250): You can execute SAS statements repeatedly by placing them in a DO loop. DO loops can execute any number of times in a single iteration of the DATA step. Using DO loops lets you write concise DATA steps that are easier to change and debug.



[Course Textbook Chapter 14, Problem 2]
- Question (yyan11−stat6250): How to construct DO loops?
- Answer (yyan11−stat6250): To construct a DO loop, you use the DO and END statements along with other SAS statements. The value of the index variable can be changed within the loop. When creating a DO loop with the iterative DO statement, you must specify an index variable. The index variable stores the value of the current iteration of the DO loop. You may use any valid SAS name.



[Course Textbook Chapter 14, Problem 3]
- Question (yyan11−stat6250): Can I dropp the index variable from the data set?
- Answer (yyan11−stat6250): In most cases, the index variable is needed only for processing the DO loop and can be dropped from the data set.



[Course Textbook Chapter 14, Problem 4]
- Question (yyan11−stat6250): How to count iterations of DO loops?
- Answer (yyan11−stat6250): In some cases, it is useful to create an index variable to count and store the number of iterations in the DO loop. Then you can drop the index variable from the data set. The sum statement Year+1 accumulates the number of iterations of the DO loop and stores the total in the new variable Year. The final value of Year is then stored in the data set, whereas the index variable counter is dropped. The data set has one observation.



[Course Textbook Chapter 14, Problem 5]
- Question (yyan11−stat6250): When can I place an explicit OUTPUT statement in a DATA step?
- Answer (yyan11−stat6250): To create an observation for each iteration of the DO loop, place an OUTPUT statement inside the loop. 


[Course Textbook Chapter 14, Problem 6]
- Question (yyan11−stat6250): What happen when I place an explicit OUTPUT statement in a DATA step?
- Answer (yyan11−stat6250): By default, every DATA step contains an implicit OUTPUT statement at the end of the step. But placing an explicit OUTPUT statement in a DATA step overrides automatic output, causing SAS to add an observation to the data set only when the explicit OUTPUT statement is executed.



[Course Textbook Chapter 14, Problem 7]
- Question (yyan11−stat6250): What is nesting DO loop?
- Answer (yyan11−stat6250): Iterative DO statements can be executed within a DO loop. Putting a DO loop within a DO loop is called nesting.




[Course Textbook Chapter 14, Problem 8]
- Question (yyan11−stat6250): How to use the DO UNTIL Statement?
- Answer (yyan11−stat6250): The DO UNTIL statement executes a DO loop until the expression becomes true. The expression is not evaluated until the bottom of the loop, so a DO UNTIL loop always executes at least once. When the expression is evaluated as true, the DO loop stops.



[Course Textbook Chapter 14, Problem 9]
- Question (yyan11−stat6250): How to use the DO WHILE Statement?
- Answer (yyan11−stat6250): Like the DO UNTIL statement, the DO WHILE statement executes DO loops conditionally. You can use the DO WHILE statement to execute a DO loop while the expression is true.



[Course Textbook Chapter 14, Problem 10]
- Question (yyan11−stat6250): What different between the DO UNTIL and DO WHILE statements?
- Answer (yyan11−stat6250): An important difference between the DO UNTIL and DO WHILE statements is that the DO WHILE expression is evaluated at the top of the DO loop. If the expression is false the first time it is evaluated, the DO loop never executes. For example, in the following program, because the value of Capital is initially zero, which is less than 50,000, the DO loop does not execute.



[Course Textbook Chapter 15, Problem 1]
- Question (yyan11−stat6250): What effect does ARRAY statement have?
- Answer (yyan11−stat6250): You can use arrays to simplify the code needed to perform repetitive calculations, create many variables that have the same attributes, read data, rotate SAS data sets by changing variables to observations or observations to variables, compare variables, perform a table lookup.



[Course Textbook Chapter 15, Problem 2]
- Question (yyan11−stat6250): How to use an ARRAY statement to group data set variables into an array?
- Answer (yyan11−stat6250): Where array-name specifies the name of the array, dimension describes the number and arrangement of array elements. The default dimension is one, elements lists the variables to include in the array. Array elements must be either all numeric or all character. If no elements are listed, new variables will be created with default names.



[Course Textbook Chapter 15, Problem 3]
- Question (yyan11−stat6250): How to specify Array Elements?
- Answer (yyan11−stat6250): When specifying the elements of an array, you can list each variable name that you want to include in the array. When listing elements, separate each element with a space. As with all SAS statements, you end the ARRAY statement with a semicolon (;). You can also specify array elements as a variable list.



[Course Textbook Chapter 15, Problem 4]
- Question (yyan11−stat6250): How to reference elements of an Array?
- Answer (yyan11−stat6250): You use an array reference to perform an action on an array element during execution. To reference an array element in the DATA step, specify the name of the array, followed by a subscript value enclosed in parentheses.



[Course Textbook Chapter 15, Problem 5]
- Question (yyan11−stat6250): How to use the DIM Function in an iterative DO Statement?
- Answer (yyan11−stat6250): When using DO loops to process arrays, you can also use the DIM function to specify the TO clause of the iterative DO statement. For a one-dimensional array, specify the array name as the argument for the DIM function. The function returns the number of elements in the array.



[Course Textbook Chapter 15, Problem 6]
- Question (yyan11−stat6250): How to creating variables in an ARRAY Statement?
- Answer (yyan11−stat6250): You can create variables in an ARRAY statement by omitting the array elements from the statement. If you do not reference existing variables, SAS automatically creates new variables for you and assigns default names to them. The default name is the array-name followed by consecutive numbers 1 to the dimension of the array.



[Course Textbook Chapter 15, Problem 7]
- Question (yyan11−stat6250): How to create an array of character variables?
- Answer (yyan11−stat6250): To create an array of character variables, add a dollar sign ($) after the array dimension.
By default, all character variables that are created in an ARRAY statement are assigned a length of 8.



[Course Textbook Chapter 15, Problem 8]
- Question (yyan11−stat6250): How to creating temporary array elements?
- Answer (yyan11−stat6250): To create temporary array elements for DATA step processing without creating new variables, specify _TEMPORARY_ after the array name and dimension.



[Course Textbook Chapter 15, Problem 9]
- Question (yyan11−stat6250): Can I reference an element within the array by specifying the two dimensions?
- Answer (yyan11−stat6250): Yes. If a DO loop processes a two-dimensional array, you can reference any element within the array by specifying the two dimensions. Multidimensional arrays are typically used with nested DO loops. 




[recipe_to_create_unique_record_id (from Week 9 Overview)]
- Question (yyan11−stat6250): The resulting value of "z6" is 6-digits wide, what is the largest magnitude?



[recipe_to_disaggregate_counts_data (from Week 9 Overview)]
- Question (yyan11−stat6250): Can we still have the individual level values in the resulting dataset?

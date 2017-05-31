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
- *Question* (lwang30-stat6250) : Are there any statements that can be used to combine the functions of data step and proc step ?
- Question (rluo-stat6250): What is the benefits of the DO loops statement?
- Answer (rluo-stat6250): It can greatly reduce the number of statements required for a repetitive calculation.
- Question (yyan11−stat6250): What is a DO loop?
- Answer (yyan11−stat6250): You can execute SAS statements repeatedly by placing them in a DO loop. DO loops can execute any number of times in a single iteration of the DATA step. Using DO loops lets you write concise DATA steps that are easier to change and debug.
- Question (mcardoso3-stat6250):  What is the benefit of having a DO statement as opposed to a normal SAS command?
- Question (lzhao4−stat6250): DO loops process a group of statements repeatedly or once?
- Answer (lzhao4-stat6250): DO loops process a group of statements repeatedly rather than once. 
- Question (cyuan10-stat6250): Are there any example of statement that can be used to combine DATA and PROC steps?
- Question (akumar30−stat6250):  Can start value will be larger than stop value in do statement?
- Answer (akumar30−stat6250):  Yes, when you use a negative BY clause value, the start value must always be greater than the stop value in order to decrease the index variable during each iteration.



[Course Textbook Chapter 14, Problem 2]
- Question (yzhu12-stat6250): Why the index variables can be dropped from the data set?
- *Question* (lwang30-stat6250) : What’s the value of the index “month” in the last iteration of the loop ?
- Question (rluo-stat6250): What increment values can be applied in the DO loops statement?
- Answer (rluo-stat6250): Numbers, variables, or SAS expressions.
- Question (yyan11−stat6250): How to construct DO loops?
- Answer (yyan11−stat6250): To construct a DO loop, you use the DO and END statements along with other SAS statements. The value of the index variable can be changed within the loop. When creating a DO loop with the iterative DO statement, you must specify an index variable. The index variable stores the value of the current iteration of the DO loop. You may use any valid SAS name.
- Question (mcardoso3-stat6250):  How many DO loop statements can be used in one DATA step?
- Question (lzhao4−stat6250): What decides the number of iterations in DO statement? 
- Question (cyuan10-stat6250): If the BY statement is not included in the Do loop, what happens?
- Answer (cyuan10-stat6250): Then it will default to 1 unit increments.
- Question (akumar30−stat6250):  Can we use character values as series of items for do loop execution?
- Answer (akumar30−stat6250): Yes, all character values, with each value enclosed in quotation marks can be used to execute do loop for executes once for each item in the series.



[Course Textbook Chapter 14, Problem 3]
- Question (yzhu12-stat6250): How can you make it easier to manage nested DO loops?
- Answer (yzhu12-stat6250): You can indent the statements in each loop.
- *Question* (lwang30-stat6250) : What new variables are generated in this do loop ?
- Question (rluo-stat6250): What does the index variable do in the DO loop statement?
- Answer (rluo-stat6250): The index variable stores the value of the current iteration of the DO loop.
- Question (yyan11−stat6250): Can I dropp the index variable from the data set?
- Answer (yyan11−stat6250): In most cases, the index variable is needed only for processing the DO loop and can be dropped from the data set.
- Question (mcardoso3-stat6250):  Does the "do count" statement cover both numerical and categorical variables?
- Question (lzhao4−stat6250): How the DO loop perform repetitive calculations? 
- Question (cyuan10-stat6250): Can the BY statement be anything other than numeric? Does it have it be integers?
- Question (akumar30−stat6250): Can we exit do loop before reaching its stop value mentioned in do loop statement?



[Course Textbook Chapter 14, Problem 4]
- Question (yzhu12-stat6250): Under what situations that we use DO WHILE and DO UNTIL statements?
- Answer (yzhu12-stat6250): DO WHILE and DO UNTIL statements can be used within iterative DO loops to combine conditional and unconditional execution. 
- *Question* (lwang30-stat6250) : What would be the stored value for Year if an “until” statement is used ?
- Question (rluo-stat6250): What specific steps must be achieved in order to correctly nest DO loops?
- Question (yyan11−stat6250): How to count iterations of DO loops?
- Answer (yyan11−stat6250): In some cases, it is useful to create an index variable to count and store the number of iterations in the DO loop. Then you can drop the index variable from the data set. The sum statement Year+1 accumulates the number of iterations of the DO loop and stores the total in the new variable Year. The final value of Year is then stored in the data set, whereas the index variable counter is dropped. The data set has one observation.
- Question (mcardoso3-stat6250):  What other variables can be used in a DO loop statement aside from Year?
- Question (lzhao4−stat6250): How the DO loop executes in the DATA step? 
- Question (cyuan10-stat6250): What if we used DO UNTIL instead? Would the stored YEAR be different? 
- Question (akumar30−stat6250):  Can we use do statement to create primary key in dataset?



[Course Textbook Chapter 14, Problem 5]
- Question (yzhu12-stat6250): What's the difference between DO WHILE and DO UNTIL statements?
- Answer (yzhu12-stat6250): The DO UNTIL statement executes a DO loop until a condition becomes true while the DO WHILE statement is used to execute a DO loop while a condition is true.
- *Question* (lwang30-stat6250) : How many iterations does the loop process if “by=3” is indicated in the “do” statement ?
- *Answer* (lwang30-stat6250) : There will be 5 iterations within this do loop if "by=3" is indicated.
- Question (rluo-stat6250): What statements can be used to achieve the conditional DO loops?
- Question (yyan11−stat6250): When can I place an explicit OUTPUT statement in a DATA step?
- Answer (yyan11−stat6250): To create an observation for each iteration of the DO loop, place an OUTPUT statement inside the loop.     
- Question (mcardoso3-stat6250):  Why does the number of iterations include the year after the last one noted in the DO loop statement?
- Question (lzhao4−stat6250): What happens when placing an explicit OUTPUT statement in a DATA step?
- Answer (lzhao4-stat6250): The OUTPUT statement overrides automatic output.
- Question (cyuan10-stat6250): What happens when you include the OUTPUT statement?
- Answer (cyuan10-stat6250): When the OUTPUT statement is included, then it will print the output for each iteration otherwise, the default is one single output.
- Question (akumar30−stat6250): Can we use output statement outside do block?



[Course Textbook Chapter 14, Problem 6]
- Question (yzhu12-stat6250): How can you run DO loops within DO loops?
- Answer (yzhu12-stat6250):  You assign a unique index variable to each loop and terminate each DO loop with its own END statement. 
- *Question* (lwang30-stat6250) : Does the number of new observation generated by do loop equal the number of iteration ?
- Question (rluo-stat6250): Can conditional and unconditional execution of DO loops be achieved?
- Question (yyan11−stat6250): What happen when I place an explicit OUTPUT statement in a DATA step?
- Answer (yyan11−stat6250): By default, every DATA step contains an implicit OUTPUT statement at the end of the step. But placing an explicit OUTPUT statement in a DATA step overrides automatic output, causing SAS to add an observation to the data set only when the explicit OUTPUT statement is executed.
- Question (mcardoso3-stat6250):  What is the limit to the number of observations that can be in a DO LOOP statemet?
- Question (lzhao4−stat6250): How to count and store the number of iterations in the DO loop? 
- Question (cyuan10-stat6250): Are increments always necessary and what if you want to do a loop where the iteration is not based on a numeric variable?
- Question (akumar30−stat6250): What are the differences between Do-Until and Do-While?
- Answer (akumar30−stat6250): Do Until is executed at least once, but DO while is executed only if the condition is true.



[Course Textbook Chapter 14, Problem 7]
- Question (yzhu12-stat6250):  Once the loop's index value exceeds the stop value, the DO loop stops, and processing continues with the following DATA step statement. So how can we re-open the previous Do loop if necessary?
- *Question* (lwang30-stat6250) : In what situations should we use DO While or Do Until statements ?
- Question (rluo-stat6250): What is the benefits of achieving conditional and unconditional execution of DO loops?
- Question (yyan11−stat6250): What is nesting DO loop?
- Answer (yyan11−stat6250): Iterative DO statements can be executed within a DO loop. Putting a DO loop within a DO loop is called nesting.
- Question (mcardoso3-stat6250):  Would using a DO WHILE or DO UNTIL statement always be preferred when comparing investing capital as opposed to using nested DO loops or a DO group?
- Question (lzhao4−stat6250): How to correctly execute nested DO loops? 
- Question (cyuan10-stat6250): How does SAS know where in the code is part of the Do loop and should be executed as such?
- Answer (cyuan10-stat6250): The “Do” statement will start the loop and “End;” will stop the loop. Anything within the these two statements are part of the loop
- Question (akumar30−stat6250): Which performs faster between Do-Until and Do-While statement?



[Course Textbook Chapter 14, Problem 8]
- Question (yzhu12-stat6250): Why the start value must be greater than the stop value when you decrement a DO loop by specifying a negative value for the BY clause? What kind of error will occur if the request is not fulfilled?
- *Question* (lwang30-stat6250) : When is the condition evaluated respectively in other DO loop statements ?
- Question (rluo-stat6250): How to draw sample obervations from a data set by using DO loop?
- Question (yyan11−stat6250): How to use the DO UNTIL Statement?
- Answer (yyan11−stat6250): The DO UNTIL statement executes a DO loop until the expression becomes true. The expression is not evaluated until the bottom of the loop, so a DO UNTIL loop always executes at least once. When the expression is evaluated as true, the DO loop stops.
- Question (mcardoso3-stat6250):  Why can't a DO UNTIL statement be evaluated at the top?
- Question (lzhao4−stat6250): Does DO UNTIL statement allow you to execute DO loops when the condition is false? 
- Answer (lzhao4-stat6250):  DO UNTIL statements enable you to execute DO loops based on whether a condition is true or false.
- Question (cyuan10-stat6250): What is the difference between DO WHILE and DO UNTIL?
- Question (akumar30−stat6250): can we use both DO while and Do until in same do statement? 



[Course Textbook Chapter 14, Problem 9]
- Question (yzhu12-stat6250): How can you specify that how many times that a DO loop executes?
- Answer (yzhu12-stat6250): You can specify how many times a DO loop executes by listing items in a series.
- *Question* (lwang30-stat6250) : Are DO While and DO Until statements complementary to each other ?
- Question (rluo-stat6250): Can Do loop be used in the proc statement?
- Question (yyan11−stat6250): How to use the DO WHILE Statement?
- Answer (yyan11−stat6250): Like the DO UNTIL statement, the DO WHILE statement executes DO loops conditionally. You can use the DO WHILE statement to execute a DO loop while the expression is true.
- Question (mcardoso3-stat6250):  How are DO UNTIL and DO WHILE statements similar?
- Answer (mcardoso3-stat6250):  The biggest similarity between both DO statements is that they execute DO loops conditionally.
- Question (lzhao4−stat6250): What is the difference between DO UNTIL statement and DO WHILE statement? 
- Question (cyuan10-stat6250): What happens when you accidentally excuse an infinite Do loop?
- Question (akumar30−stat6250):  Can nested do loop be used in SAS?
- Answer (akumar30−stat6250): Yes, SAS allows Do-Loop inside a Do-Loop.



[Course Textbook Chapter 14, Problem 10]
- Question (yzhu12-stat6250): How to construct an iterative DO loop?
- Answer (yzhu12-stat6250): By specifying an index variable and the conditions that will execute the loop. 
- *Question* (lwang30-stat6250) : What would the statement be if DO Until is used in this case ? 
- Question (rluo-stat6250): Is there any disadvantages of using DO loops statement?
- Question (yyan11−stat6250): What different between the DO UNTIL and DO WHILE statements?
- Answer (yyan11−stat6250): An important difference between the DO UNTIL and DO WHILE statements is that the DO WHILE expression is evaluated at the top of the DO loop. If the expression is false the first time it is evaluated, the DO loop never executes. For example, in the following program, because the value of Capital is initially zero, which is less than 50,000, the DO loop does not execute.
- Question (mcardoso3-stat6250):  What do the "when" and "over" statements indicate and can they be a DO LOOP statement as well?
- Question (lzhao4−stat6250): The WHILE expression is evaluated before or after the execution of the DO loop?
- Question (cyuan10-stat6250): Can you have multiple nested DO UNTIL and DO WHILE loops?
- Question (akumar30−stat6250): Can we break outside of do loop before completion of all do steps?



[Course Textbook Chapter 15, Problem 1]
- Question (yzhu12-stat6250): What will happen if you using the name of a SAS function as an array name?
- Answer (yzhu12-stat6250): The array will be correct, but you won't be able to use the function in the same DATA step, and a warning will be written to the SAS log.
- *Question* (lwang30-stat6250) : What statements can be described as "executable" ?
- Question (rluo-stat6250): What is the SAS array?
- Question (yyan11−stat6250): What effect does ARRAY statement have?
- Answer (yyan11−stat6250): You can use arrays to simplify the code needed to perform repetitive calculations, create many variables that have the same attributes, read data, rotate SAS data sets by changing variables to observations or observations to variables, compare variables, perform a table lookup.
- Question (mcardoso3-stat6250):  What is a valid reason for using arrays?
- Answer (mcardoso3-stat6250):  An array is useful for reducing the number of statements that are required for processing variables.
- Question (lzhao4−stat6250): How to correctly define an array? 
- Question (cyuan10-stat6250): What is an “executable” statement?
- Question (akumar30−stat6250):  What is the primary purpose to use array in SAS?
- Answer (akumar30−stat6250):  Primary purpose of an array is array is to reduce the number of statements that are required for processing variables.



[Course Textbook Chapter 15, Problem 2]
- Question (yzhu12-stat6250): How can you indicate the dimension of a one-dimensional array?
- Answer (yzhu12-stat6250): You can indicate the dimension of a one-dimensional array with an asterisk (*) as long as you specify the elements of the array. 
- *Question* (lwang30-stat6250) : What other syntax can be used to define this array ?
- *Answer* (lwang30-stat6250) : An asterisk * can be used to replace the number "4" here to define this one-dimensional array.
- Question (rluo-stat6250): Where does the SAS array exist?
- Question (yyan11−stat6250): How to use an ARRAY statement to group data set variables into an array?
- Answer (yyan11−stat6250): Where array-name specifies the name of the array, dimension describes the number and arrangement of array elements. The default dimension is one, elements lists the variables to include in the array. Array elements must be either all numeric or all character. If no elements are listed, new variables will be created with default names.
- Question (mcardoso3-stat6250):  What does the number within the braces of an ARRAY statement supposed to indicate?
- Answer (mcardoso3-stat6250):  It's the number of elements in the array, which can be specified in many ways.
- Question (lzhao4−stat6250): What does the value inside the parentheses indicate for?
- Question (cyuan10-stat6250): Are brackets, parentheses, and braces interchangeable? Is there a benefit of one over the others?
- Question (akumar30−stat6250): Does the Array index in SAS starts with 0 or 1?
- Answer (akumar30−stat6250): The index of Array in SAS starts with 1.



[Course Textbook Chapter 15, Problem 3]
- Question (yzhu12-stat6250): How can you create temporary array elements for DATA step processing without creating additional variables?
- Answer (yzhu12-stat6250): You can specify _TEMPORARY_ after the array name and dimension.
- *Question* (lwang30-stat6250) : Which statement do we usually associate with a referenced array statement ?
- Question (rluo-stat6250): How long can the SAS array last?
- Question (yyan11−stat6250): How to specify Array Elements?
- Answer (yyan11−stat6250): When specifying the elements of an array, you can list each variable name that you want to include in the array. When listing elements, separate each element with a space. As with all SAS statements, you end the ARRAY statement with a semicolon (;). You can also specify array elements as a variable list.
- Question (mcardoso3-stat6250):  Is it easier to reference the elements of an array with a DO loop statement rather than without it?
- Question (lzhao4−stat6250): How to represent the values of the array elements?
- Question (cyuan10-stat6250): What is the benefit of creating arrays? 
- Answer (cyuan10-stat6250): You can use them in Do Loops.
- Question (akumar30−stat6250): can we use array inside nested do statement?



[Course Textbook Chapter 15, Problem 4]
- Question (yzhu12-stat6250): How to define a multidimensional array?
- Answer (yzhu12-stat6250): You can specify the number of elements in each dimension, separated by a comma. 
- *Question* (lwang30-stat6250) : What is the function of the number in the "{}" of an array statement ?
- *Answer* (lwang30-stat6250) : It is used to give a subscript to each element of the defined array.
- Question (rluo-stat6250): What is the benefits by using SAS array?
- Question (yyan11−stat6250): How to reference elements of an Array?
- Answer (yyan11−stat6250): You use an array reference to perform an action on an array element during execution. To reference an array element in the DATA step, specify the name of the array, followed by a subscript value enclosed in parentheses.
- Question (mcardoso3-stat6250):  How many different values can an index variable contain in a DATA step?
- Question (lzhao4−stat6250): Where is the right place to enclose index value? 
- Question (cyuan10-stat6250): Does the index refer to the order in which the variables are listed or it’s alphabetical order?
- Question (akumar30−stat6250): What is the advantage of using an array with do loops?
- Answer (akumar30−stat6250): Arrays are used with DO loops to process multiple variables and to perform repetitive calculations.



[Course Textbook Chapter 15, Problem 5]
- Question (yzhu12-stat6250): You can create temporary array elements for DATA step processing without creating additional variables, but what step you must take then?
- Answer (yzhu12-stat6250): You need to specify _TEMPORARY_ after the array name and dimension.
- *Question* (lwang30-stat6250) : What functions does "DIM" have in referencing an array in a do loop ?
- Question (rluo-stat6250): How to define a SAS Array?
- Question (yyan11−stat6250): How to use the DIM Function in an iterative DO Statement?
- Answer (yyan11−stat6250): When using DO loops to process arrays, you can also use the DIM function to specify the TO clause of the iterative DO statement. For a one-dimensional array, specify the array name as the argument for the DIM function. The function returns the number of elements in the array.
- Question (mcardoso3-stat6250):  What types of variables/elements can a DIM function use to specify with in a statement?
- Question (lzhao4−stat6250): When to use the DIM function? 
- Question (cyuan10-stat6250): Does the * represent “all” in other statements too?
- Question (akumar30−stat6250): How to identify size of array in SAS?
- Answer (akumar30−stat6250): In SAS DIM function can be used to determine array size.



[Course Textbook Chapter 15, Problem 6]
- Question (yzhu12-stat6250): Why do we have to enclose each value in quotation marks when assigning initial values to character variables? Which error will occur if we fail to do so?
- *Question* (lwang30-stat6250) : Can character and numeric variables be combined in one array statement ? 
- Question (rluo-stat6250): Can we use array names in LABEL, FORMAT, DROP, KEEP, or LENGTH statements?
- Question (yyan11−stat6250): How to creating variables in an ARRAY Statement?
- Answer (yyan11−stat6250): You can create variables in an ARRAY statement by omitting the array elements from the statement. If you do not reference existing variables, SAS automatically creates new variables for you and assigns default names to them. The default name is the array-name followed by consecutive numbers 1 to the dimension of the array.
- Question (mcardoso3-stat6250):  What types of variables can be created when using arrays?
- Question (lzhao4−stat6250): Is there any kind of variable cannot be created by an ARRAY statement?  
- Question (cyuan10-stat6250): Can variables be continuous values?
- Question (akumar30−stat6250): How to combine multiple array in SAS?



[Course Textbook Chapter 15, Problem 7]
- Question (yzhu12-stat6250): How to create an array of character variables?
- Answer (yzhu12-stat6250): You can add a dollar sign ($) after the array dimension.
- *Question* (lwang30-stat6250) : How many iterations does this do loop process ?
- Question (rluo-stat6250): What is the dimension of the array?
- Question (yyan11−stat6250): How to create an array of character variables?
- Answer (yyan11−stat6250): To create an array of character variables, add a dollar sign ($) after the array dimension.
By default, all character variables that are created in an ARRAY statement are assigned a length of 8.
- Question (mcardoso3-stat6250):  What is the purpose of finding the difference between {i+1} and {i}?
- Question (lzhao4−stat6250): What happens when you create variables in an ARRAY statement by omitting the array elements from the statement? 
- Question (cyuan10-stat6250): In this example, is the output a single value? Do we need to include output statement to print the output of each iteration? 
- Question (akumar30−stat6250):  How to compare two arrays and find duplicate records?



[Course Textbook Chapter 15, Problem 8]
- Question (yzhu12-stat6250): Why you don't have to re-specify the stop value of a DO statement if you change the dimension of the array when you use the DIM function?
- *Question* (lwang30-stat6250) : How to define the length of the character variables in an array statement ? 
- Question (rluo-stat6250): How do we specify variable lists?
- Question (yyan11−stat6250): How to creating temporary array elements?
- Answer (yyan11−stat6250): To create temporary array elements for DATA step processing without creating new variables, specify _TEMPORARY_ after the array name and dimension.
- Question (mcardoso3-stat6250):  Why are parentheses needed when creating temporary array elements in an ARRAY statement?
- Question (lzhao4−stat6250): How to correctly assign initial values to arrays? 
- Question (cyuan10-stat6250): What is the difference between this array with numeric variables vs. using an index with increments of 300?
- Question (akumar30−stat6250):  can array have multiple datatypes as values?



[Course Textbook Chapter 15, Problem 9]
- Question (yzhu12-stat6250): What is the purpose of a SAS array?
- Answer (yzhu12-stat6250): An array is a temporary grouping of variables under a single name. This can reduce the number of statements needed to process variables and can simplify the maintenance of DATA step programs. 
- *Question* (lwang30-stat6250) : How many rows and columns are present in this array ?
- Question (rluo-stat6250): Can the variables types be different in the array?
- Question (yyan11−stat6250): Can I reference an element within the array by specifying the two dimensions?
- Answer (yyan11−stat6250): Yes. If a DO loop processes a two-dimensional array, you can reference any element within the array by specifying the two dimensions. Multidimensional arrays are typically used with nested DO loops. 
- Question (mcardoso3-stat6250):  Is there a limit to how many elements you may have in a ARRAY statement?
- Question (lzhao4−stat6250): How to group variables into two-dimensional array?
- Question (cyuan10-stat6250): What if the increments in the array is not equal or linear?
- Question (akumar30−stat6250):  Can we use character variable as index of array in SAS? 



[recipe_to_create_unique_record_id (from Week 9 Overview)]
- Question (yzhu12-stat6250): How can we convert some particular numeric to character and which statement do we use to convert character to numeric?
- *Question* (lwang30-stat6250) : How can we use the "CATX" function to concatenate two strings ? 
- Question (rluo-stat6250): In what kind of situation do we need to create or change the unique id?
- Question (yyan11−stat6250): The resulting value of "z6" is 6-digits wide, what is the largest magnitude?
- Question (mcardoso3-stat6250):  What does concatenating strings do?
- Answer (mcardoso3-stat6250):  It means to join strings together to form a single string.
- Question (lzhao4−stat6250): From the recipe we can know that format "z6" meaning it's left-padded with zeros. So what else we can use?
- Question (cyuan10-stat6250): For concatenating string values, can “+” be used instead?
- Question (akumar30−stat6250): Can we append hexadecimal value to make unique id in SAS?



[recipe_to_disaggregate_counts_data (from Week 9 Overview)]
- Question (yzhu12-stat6250): How can we tell if the data is a fine data so that we can coombine it with other dataset and input into something like proc mean or proc freq?
- *Question* (lwang30-stat6250) : How do we use do loop to aggregate data to a higher level ? 
- Question (rluo-stat6250): In what kind of situation do we need to disaggregate the data?
- Question (yyan11−stat6250): Can we still have the individual level values in the resulting dataset?
- Question (mcardoso3-stat6250):  What would be the main reason to disaggregate the data in your dataset?
- Question (lzhao4−stat6250): What is the distinction between high level of aggregations and low level of aggregations?
- Question (cyuan10-stat6250): What is the benefit of disaggregate data and when would we use it?
- Question (akumar30−stat6250): How to keep the result accurate when aggregating the data at different level?



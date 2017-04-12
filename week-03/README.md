## Week 3 Quiz Questions and Answers

In order to prepare your Week 3 Quiz submission, please edit ***this*** document to provide substantive questions for each Quiz Problem and SAS Recipe listed below, as well as answers to at least three questions raised.

All edits should conform to GitHub Markdown specifications (https://guides.github.com/features/mastering-markdown/) and should be committed to a branch named "week-3" in your fork of this repo. Then, after all edits have been made/committed, your Week 3 Quiz should be submitted by initiating a pull request using

- the master branch of the stat6250/course_questions_wiki repo as the base fork and

- the week-3 branch of your version of the repo as the head fork.

The instructor will then review the pull request and make comments should further revision be needed. Then, after the contents of the pull request have been finalized without any merge conflicts, the instructor will merge the pull request.

********************************************************************************


[Course Textbook Chapter 3, Problem 1]
* *Question (aalshehry−stat6250):* Why code formatting is important?
* *Answer (aalshehry−stat6250):* Even though, SAS statements can be written in any format, a consistent layout improve readability and helps understand the program's purpose easily.
- Question (meisenbach-stat6250): Should you place a run statement after every DATA or PROC step?


[Course Textbook Chapter 3, Problem 2]
* *Question (aalshehry−stat6250):* How can we clear the output window and the log window?
- Question (meisenbach-stat6250): What is the difference between the Program Editor and the Editor?



[Course Textbook Chapter 3, Problem 3]
* *Question (aalshehry−stat6250):* Can we specify more than one “BY variable”?
* *Answer (aalshehry−stat6250):*  You can specify as many BY variables as you wish for example:
```SAS
PROC SORT;
      BY variable-1 ... variable-n;
```
- Question (meisenbach-stat6250): What state is the program in when there is an unbalanced quote and the rest of the program is fairly short?

 
 
[Course Textbook Chapter 3, Problem 4]
* *Question (aalshehry−stat6250):* What will SAS display in the log window when a syntax error detected?
* *Answer (aalshehry−stat6250):*  it will displays the word ERROR, identifies the possible location of the error, and gives an explanation of the error.
- Question (meisenbach-stat6250): How can you prevent syntax errors?
- Answer (meisenbach-stat6250): In the Enhanced Editor, text with syntax error is colored red.



[Course Textbook Chapter 3, Problem 5]
* *Question (aalshehry−stat6250):* What type of errors can SAS detect?
- Question (meisenbach-stat6250): What are other types of errors?



[Course Textbook Chapter 3, Problem 6]
* *Question (aalshehry−stat6250):* What is an invalid option?
- Question (meisenbach-stat6250): How should you correct an invalid option?
- Answer (meisenbach-stat6250): After checking for typos, read the error message for suggestions for what a valid option would be in that statement.



[Course Textbook Chapter 3, Problem 7]
* *Question (aalshehry−stat6250):* What are data errors?
- Question (meisenbach-stat6250): When is SAS able to correct misspelled keywords?



[Course Textbook Chapter 3, Problem 10]
* *Question (aalshehry−stat6250):* Is there a situation where “Run;” statement is not required?
- Question (meisenbach-stat6250): How can you catch unbalanced quotation marks?
- Answer (meisenbach-stat6250): Quoted text is purple. If the rest of the program is also purple, there is an unmatched quote somewhere in the purple block.



[Course Textbook Chapter 4, Problem 1]
* *Question (aalshehry−stat6250):* How to change the name of a variable(column)?
- Question (meisenbach-stat6250): Is the variable for the ID statement required to be unique?



[Course Textbook Chapter 4, Problem 3]
* *Question (aalshehry−stat6250):* How to use WHERE statement to select multiple values from numerical observations?
- Question (meisenbach-stat6250): Does using the IN operatior in the WHERE statement help the code to be more readable?



[Course Textbook Chapter 4, Problem 4]
* *Question (aalshehry−stat6250):* What will happen if you run a PROC SORT statement without OUT= option?
- Question (meisenbach-stat6250): What kind of error do you get if you leave out the BY statement?



[Course Textbook Chapter 4, Problem 7]
* *Question (aalshehry−stat6250):* Is “BY” statement required in “PROC SORT”?
- Question (meisenbach-stat6250): Why does SAS continue execution of a program when a step fails?



[Course Textbook Chapter 4, Problem 9]
* *Question (aalshehry−stat6250):* What symbols represent “not equal to” operator in SAS?



[Course Textbook Chapter 4, Problem 10]
* *Question (aalshehry−stat6250):* What does “NOOBS” in “PROC PRINT” do?
- Question (meisenbach-stat6250): What happens if you don’t group conditions with parentheses?



[recipe_to_check_for_duplicates (from Week 3 Overview)]
* *Question (aalshehry−stat6250):* Does “DUPOUT” save unique observations without the duplicated rows or does it save only the duplicated observations?
- Question (meisenbach-stat6250): What does PROC SORT using  NODUPKEY use to determine what a duplicate row is?
- Answer (meisenbach-stat6250): The criteria is the variables specified in the BY statement. So in the recipe example, if there are rows with the same County_Code, District_Code, and School_Code, they would be considered duplicates.



[recipe_for_sorting_data (from Week 3 Overview)]
* *Question (aalshehry−stat6250):* What is the default sorting option? Is it ascending or descending?
- Question (meisenbach-stat6250): Is it generally a bad idea to overwrite the original dataset with the sorted one?
- Answer (meisenbach-stat6250): Yes, there may be information in the original order of the data.


[recipe_for_printing_values (from Week 3 Overview)]
* *Question (aalshehry−stat6250):* How to PROC PRINT to print a specific range of data (i.e. rows from 20 to 30)?
- Question (meisenbach-stat6250): What is the purpose of the ID statement within PROC PRINT? Does the index have to be unique?
- Answer (meisenbach-stat6250): “Identifies observations by using the formatted values of the variables that you list instead of by using observation numbers.” - SAS documentation. It does not appear to have to be unique. In the example, County_Name + District_Name is not unique.




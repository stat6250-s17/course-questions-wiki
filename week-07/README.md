## Week 7 Quiz Questions and Answers

In order to prepare your Week 7 Quiz submission, please edit ***this*** document to provide substantive questions for each Quiz Problem and SAS Recipe listed below, as well as answers to at least three questions raised.

All edits should conform to GitHub Markdown specifications (https://guides.github.com/features/mastering-markdown/) and should be committed to a branch named "week-7" in your fork of this repo. Then, after all edits have been made/committed, your Week 7 Quiz should be submitted by initiating a pull request using

- the master branch of the stat6250/course_questions_wiki repo as the base fork and

- the week-7 branch of your version of the repo as the head fork.

The instructor will then review the pull request and make comments should further revision be needed. Then, after the contents of the pull request have been finalized without any merge conflicts, the instructor will merge the pull request.

********************************************************************************



[Course Textbook Chapter 10, Problem 2]
- *Question* (lwang30-stat6250) : Can we take the label and format statement in the data step away as they will be overwritten by "proc print" anyway ?


[Course Textbook Chapter 10, Problem 6]
- *Question* (lwang30-stat6250) : What types of variable are present in this problem ?


[Course Textbook Chapter 10, Problem 7]
- *Question* (lwang30-stat6250) : What is the consequence of the subsequent observations having longer values than the first observation without the length of the variable being specified in the statement ?
- *Answer* (lwang30-stat6250) : All subsequent values are truncated to the same length as the first observation's value.


[Course Textbook Chapter 10, Problem 8]
- *Question* (lwang30-stat6250) : What is the advantage of using the IF-THEN/ELSE statement ?
- *Answer* (lwang30-stat6250) : When the dataset is large, IF-THEN/ELSE statement can process much faster than multiple IF-THEN statement in which all the observations are evaluated one by one.


[Course Textbook Chapter 10, Problem 9]
- *Question* (lwang30-stat6250) : Where should we place the LENGTH statement in order to let variable "Type" have a length of 10 ?


[Course Textbook Chapter 10, Problem 10]
- *Question* (lwang30-stat6250) : What is the difference between the "DROP or KEEP" statement and the "DROP= or KEEP=" statement ?


[Course Textbook Chapter 11, Problem 1]
- *Question* (lwang30-stat6250) : What are the statements where we can use the "DROP= or KEEP=" option ?


[Course Textbook Chapter 11, Problem 2]
- *Question* (lwang30-stat6250) : What is the basic criterion to be based on in order to figure out the correct place where the "DROP= or KEEP=" option should be located ? 


[Course Textbook Chapter 11, Problem 3]
- *Question* (lwang30-stat6250) : What are the values of each FIRST. and LAST. when the BY-Group processing is used for multiple variables ?


[Course Textbook Chapter 11, Problem 8]
- *Question* (lwang30-stat6250) : In what situations do we want to use the END= option to manipulate the data ?


[Course Textbook Chapter 11, Problem 9]
- *Question* (lwang30-stat6250) : What are the values of each variable in the PDV at the beginning of the execution phase ?
- *Answer* (lwang30-stat6250) : The values of each variable are set to missing at the beginning of the execution phase.


[basic_recipe_for_combining_data_vertically (from Week 7 Overview)]
- *Question* (lwang30-stat6250) : What is an example of the expansion of the dataset by applying both two indicator variables that has been defined in the "set" statement ?


[optional: adv_recipe_for_combining_data_vertically (from Week 7 Overview)]
- *Question* (lwang30-stat6250) : What are the advantages and disadvantages of using "proc sql" rather than a data step ?


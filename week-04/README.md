## Week 4 Quiz Questions and Answers

In order to prepare your Week 4 Quiz submission, please edit ***this*** document to provide substantive questions for each Quiz Problem and SAS Recipe listed below, as well as answers to at least three questions raised.

All edits should conform to GitHub Markdown specifications (https://guides.github.com/features/mastering-markdown/) and should be committed to a branch named "week-4" in your fork of this repo. Then, after all edits have been made/committed, your Week 4 Quiz should be submitted by initiating a pull request using

- the master branch of the stat6250/course_questions_wiki repo as the base fork and

- the week-4 branch of your version of the repo as the head fork.

The instructor will then review the pull request and make comments should further revision be needed. Then, after the contents of the pull request have been finalized without any merge conflicts, the instructor will merge the pull request.

********************************************************************************



[Course Textbook Chapter 7, Problem 3]
- *Question* (lwang30-stat6250) : In what situations does the new format's name have to end with a period ?


[Course Textbook Chapter 7, Problem 4]
- *Question* (lwang30-stat6250) : What should be done prior to the *proc format* step to indicate where the new format will be stored ?



[Course Textbook Chapter 7, Problem 5]
- *Question* (lwang30-stat6250) : When are the single and double quotation mark used respectively in the *value* statement ?


[Course Textbook Chapter 7, Problem 6]
- *Question* (lwang30-stat6250) : How many characters can be used in a variable's name ?


[Course Textbook Chapter 7, Problem 7]
- *Question* (lwang30-stat6250) : What other keywords can also be used to label ?


[Course Textbook Chapter 7, Problem 8]
- *Question* (lwang30-stat6250) : What happens when you place the *format* statement in a PROC step ?


[Course Textbook Chapter 8, Problem 1]
- *Question* (lwang30-stat6250) : Which keyword represents standard deviation in the MEANS procedure ?


[Course Textbook Chapter 8, Problem 2]
- *Question* (lwang30-stat6250) : What would the output be if the variables specified in *proc means* have both numeric and character types ?


[Course Textbook Chapter 8, Problem 4]
- *Question* (lwang30-stat6250) : Which procedure should be performed prior to the BY group processing in *proc means* ?
- *Answer* (lwang30-stat6250) : The data should be sorted by *proc sort* statement first before BY group processing is performed in *proc means*.


[Course Textbook Chapter 8, Problem 7]
- *Question* (lwang30-stat6250) : What other statistics does *proc freq* create in the output ?
- *Answer* (lwang30-stat6250) : By default, *proc freq* also prints cumulative frequency and cumulative percent in the output.

[Course Textbook Chapter 8, Problem 8]
- *Question* (lwang30-stat6250) : How do we limit the frequency distribution output to categorical values only ?


[Course Textbook Chapter 8, Problem 10]
- *Question* (lwang30-stat6250) : In what situations shall we prefer to use */list* to generate a listing output for crosstabulation tables ?


[recipe_for_summarizing_quantitative_values (from Week 4 Overview)]
- *Question* (lwang30-stat6250) : How to suppress the output statistics to mean and standard deviation only ?


[recipe_for_summarizing_qualitative_values (from Week 4 Overview)]
- *Question* (lwang30-stat6250) : How would SAS deal with the output if more than 2 variables are crosstabulated ?


[recipe_for_temporarily_binning_values discussed (from Week 4 Overview)]
- *Question* (lwang30-stat6250) : What is the change in the variable type after those 2 quantitative variables are formatted ?
- *Answer* (lwang30-stat6250) : Both the discrete and continuous quantitative variables are reformatted into categorical variables by *proc format* statement.

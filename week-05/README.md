## Week 5 Quiz Questions and Answers

In order to prepare your Week 5 Quiz submission, please edit ***this*** document to provide substantive questions for each Quiz Problem and SAS Recipe listed below, as well as answers to at least three questions raised.

All edits should conform to GitHub Markdown specifications (https://guides.github.com/features/mastering-markdown/) and should be committed to a branch named "week-5" in your fork of this repo. Then, after all edits have been made/committed, your Week 5 Quiz should be submitted by initiating a pull request using

- the master branch of the stat6250/course_questions_wiki repo as the base fork and

- the week-5 branch of your version of the repo as the head fork.

The instructor will then review the pull request and make comments should further revision be needed. Then, after the contents of the pull request have been finalized without any merge conflicts, the instructor will merge the pull request.

********************************************************************************



[Course Textbook Chapter 5, Problem 1]
- Question (mcardoso3-stat6250):  Is there an easier way to input the data set other than to include the data file in the SAS statement?

[Course Textbook Chapter 5, Problem 2]
- Question (mcardoso3-stat6250):  What is the benefit to having a fileref?
- Answer (mcardoso3-stat6250):  Filerefs temporarily point to a storage location for data and they reference external files.  It is a good function to have if you need to find a specific dataset that has been saved.

[Course Textbook Chapter 5, Problem 6]
- Question (mcardoso3-stat6250):  How much differently, if at all, would variables be inputed in an INFILE statement as opposed to a DATALINES statement?

[Course Textbook Chapter 5, Problem 7]
- Question (mcardoso3-stat6250):  What happens if the input variables are entered out of order?
- Answer (mcardoso3-stat6250):  If the variables are entered out of order, the columns will have inaccurate names and therefore the dataset would appear confusing to interpret.

[Course Textbook Chapter 5, Problem 8]
- Question (mcardoso3-stat6250):  What other variables can define values as percentages besides Income?

[Course Textbook Chapter 6, Problem 1]
- Question (mcardoso3-stat6250):  What is the purpose of the compilation phase in SAS?

[Course Textbook Chapter 6, Problem 2]
- Question (mcardoso3-stat6250):  If incorrect values and formats in each statement in the DATA step aren't considered syntax errors, what are they considered as?

[Course Textbook Chapter 6, Problem 3]
- Question (mcardoso3-stat6250):  Where and how often would DATA steps be executed if otherwise directed?

[Course Textbook Chapter 6, Problem 4]
- Question (mcardoso3-stat6250):  Why are the values of the remaining variables at the start of the execution phase set to "missing"?

[Course Textbook Chapter 6, Problem 5]
- Question (mcardoso3-stat6250):  When would it be necessary to reset the automatic variable_ERROR_ to 0?

[Course Textbook Chapter 6, Problem 6]
- Question (mcardoso3-stat6250):  What does an iteration of the DATA step mean?
- Answer (mcardoso3-stat6250):  An iteration is a loop or cycle of execution, which repetitively executes statements to read data values and create observations one by one.

[basic_recipe_for_creating_analytic_datasets (from Week 5 Overview)]
- Question (mcardoso3-stat6250):  How much practice would it typically take for one to fully understand the programming data vector in SAS?

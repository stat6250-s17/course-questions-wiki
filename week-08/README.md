## Week 8 Quiz Questions and Answers

In order to prepare your Week 8 Quiz submission, please edit ***this*** document to provide substantive questions for each Quiz Problem and SAS Recipe listed below, as well as answers to at least three questions raised.

All edits should conform to GitHub Markdown specifications (https://guides.github.com/features/mastering-markdown/) and should be committed to a branch named "week-8" in your fork of this repo. Then, after all edits have been made/committed, your Week 8 Quiz should be submitted by initiating a pull request using

- the master branch of the stat6250/course_questions_wiki repo as the base fork and

- the week-8 branch of your version of the repo as the head fork.

The instructor will then review the pull request and make comments should further revision be needed. Then, after the contents of the pull request have been finalized without any merge conflicts, the instructor will merge the pull request.

********************************************************************************



[Course Textbook Chapter 13, Problem 1]
- Question (kveng−stat6250): Do we really need to word OF inside the mean function?
- Answer (kveng−stat6250): If you omit the word OF, the function argument might not be interpreted as expected. 


[Course Textbook Chapter 13, Problem 2]
- Question (kveng−stat6250): Is it better to specify the data type of PayRate in advance to numberic?


[Course Textbook Chapter 13, Problem 3]
- Question (kveng−stat6250): What is the different between comma6 and comma7 here?
- Answer (kveng−stat6250): The numeric informat "comma6." tells SAS that you want to read in a number that contains a comma and takes up to 6 spaces (including the comma)

[Course Textbook Chapter 13, Problem 4]
- Question (kveng−stat6250): What is the different between PUT() and  INPUT()?
- Answer (kveng−stat6250): 1, PUT() always creates character variables
                           2, INPUT() can create character or numeric variables based on the informat
                           3, The source format must match the source variable type in PUT()
                           4, The source variable type for INPUT() must always be character variables

[Course Textbook Chapter 13, Problem 5]
- Question (kveng−stat6250): How does YEARCUTOFF work?


[Course Textbook Chapter 13, Problem 6]
- Question (kveng−stat6250): Is there a substr function in SAS? 


[Course Textbook Chapter 13, Problem 7]
- Question (kveng−stat6250): What is the defference between SCAN and substr?


[Course Textbook Chapter 13, Problem 10]
- Question (kveng−stat6250): What is the difference between index function and substr?


[recipe_for_isolating_all_duplicates (from Week 8 Overview)]



[recipe_for_drop_and_swap (from Week 8 Overview)]



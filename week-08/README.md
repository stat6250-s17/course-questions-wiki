## Week 8 Quiz Questions and Answers

In order to prepare your Week 8 Quiz submission, please edit ***this*** document to provide substantive questions for each Quiz Problem and SAS Recipe listed below, as well as answers to at least three questions raised.

All edits should conform to GitHub Markdown specifications (https://guides.github.com/features/mastering-markdown/) and should be committed to a branch named "week-8" in your fork of this repo. Then, after all edits have been made/committed, your Week 8 Quiz should be submitted by initiating a pull request using

- the master branch of the stat6250/course_questions_wiki repo as the base fork and

- the week-8 branch of your version of the repo as the head fork.

The instructor will then review the pull request and make comments should further revision be needed. Then, after the contents of the pull request have been finalized without any merge conflicts, the instructor will merge the pull request.

********************************************************************************



[Course Textbook Chapter 13, Problem 1]
- Question (aoneill2-stat6250): How many arguments does the mean function take?


[Course Textbook Chapter 13, Problem 2]
- Question (aoneill2-stat6250): What is the resulting value type when you mix char and numeric vars in a function operation?


[Course Textbook Chapter 13, Problem 3]
- Question (aoneill2-stat6250): How many values must be accommodated in a format for a numeric value - do characters like commas and decimals count?
- Answer (aoneill2-stat6250): Yes, in a format statement such as comma7. the comma counts as one of the 7 "digits" even though the comma itself is not really a numerical value itself.

- Question (aoneill2-stat6250): In a numeric variable format, what does it mean when it ends in a decimal?

[Course Textbook Chapter 13, Problem 4]
- Question (aoneill2-stat6250): In formatting char values to assign as numeric values to variables, what is the function used - "put" or "input"?

[Course Textbook Chapter 13, Problem 5]
- Question (aoneill2-stat6250): Does MDY format in Year of cutoff value require only a 2-digit year in the year of the cutoff itself - i.e., if the cutoff year is year 0?


[Course Textbook Chapter 13, Problem 6]
- Question (aoneill2-stat6250): In reading in a string to store a subset of it, is there a way to make SAS take the characters from the RHS without having to count the number of characters in the original string or the number of characters leading up to it?


[Course Textbook Chapter 13, Problem 7]
- Question (aoneill2-stat6250): Do you use scan or substr function to locate single-char input in a string and do you have to specify with a separate arg the length of the substring if only one char?


[Course Textbook Chapter 13, Problem 10]
- Question (aoneill2-stat6250): How does the index function work to find values of a given bar in a given dataset?


[Recipe for Isolating All Dups]
- Question (aoneill2-stat6250): How does SAS know to loop through the entire program with just one line of code?
- Answer (aoneill2-stat6250): The run statement in a data step is the end of an implied loop.

[Recipe for Drop-and-Swap]
- Question (aoneill2-stat6250): Why is best12. the format used for the value assigned to High_Grade?
- Answer (aoneill2-stat6250): best12. is the default format for assigning a numeric value without any decimal part.

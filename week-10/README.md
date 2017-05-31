## Week 10 Quiz Questions and Answers

In order to prepare your Week 10 Quiz submission, please edit ***this*** document to provide substantive questions for each Quiz Problem and SAS Recipe listed below, as well as answers to at least three questions raised.

All edits should conform to GitHub Markdown specifications (https://guides.github.com/features/mastering-markdown/) and should be committed to a branch named "week-10" in your fork of this repo. Then, after all edits have been made/committed, your Week 10 Quiz should be submitted by initiating a pull request using

- the master branch of the stat6250/course_questions_wiki repo as the base fork and

- the week-10 branch of your version of the repo as the head fork.

The instructor will then review the pull request and make comments should further revision be needed. Then, after the contents of the pull request have been finalized without any merge conflicts, the instructor will merge the pull request.

********************************************************************************



[Course Textbook Chapter 16, Problem 1]
- Question (aoneill2−stat6250): Is it necessary to leave unused columns in columnar-formatted data?
- Answer (aoneill2−stat6250): No, it is not necessary to use spaces or other delimiters.


[Course Textbook Chapter 16, Problem 5]
- Question (aoneill2−stat6250): What does the period mean at the end of an informat?
- Answer (aoneill2−stat6250): The period ends the informat.
- Question (aoneill2−stat6250): Why does an informat need to be "ended?"


[Course Textbook Chapter 16, Problem 7]
- Question (aoneill2−stat6250): If the default for the input argument is column 1, then isn't it the same to read a piece of data that starts in column 7 either with input @7 or input +6?
- Answer (aoneill2−stat6250): Yes, that's true. In the possible answers, there is a missing period at the end of the informat for Item in answer (d).


[Course Textbook Chapter 16, Problem 8]
- Question (aoneill2−stat6250): Do you have to count everything including $ signs, commas, and decimals in determining the informant for reading in dollar and cents values?
- Answer (aoneill2−stat6250): Yes, everything counts towards the number preceding the period marking the separation between the overall character count and the number of decimal places.
- Question (aoneill2−stat6250): Does a decimal number informant include a second period at the end to end the informant itself?
- Answer (aoneill2−stat6250): No, not for a decimal number. It does not apply for this informant.

[Course Textbook Chapter 16, Problem 9]
- Question (aoneill2−stat6250): If you read in blank spaces preceding a number, is it still stored in the same manner?
- Answer (aoneill2−stat6250): Yes, because the number's formatting is determined by its informant, and not by blank spaces.
- Question (aoneill2−stat6250): Should you use the comma informant to read in dollar values with commas in them?
- Answer (aoneill2−stat6250): No, because the comma and the $ sign are included as characters in the first part of the informant before the period that separates it from the number of decimal places, and the comma-informant actually strips the field value that is read of the dollar sign, along with any other embedded symbols, which is a good solution if you want the value to be stored only as a number.

[Course Textbook Chapter 17, Problem 1]
- Question (aoneill2−stat6250): What happens if you read in free-form data that is also variable in length for some field?
- Answer (aoneill2−stat6250): It can generate an error and leave the value blank if the system attempts to read more characters than are available before an end-of-record marker is reached.

[Course Textbook Chapter 17, Problem 2]
- Question (aoneill2−stat6250): When listing variables in an input statement, why is it merely sufficient to use a $ sign to read in a character field without specifying a minimum-width or maximum-width field?


[Course Textbook Chapter 17, Problem 4]
- Question (aoneill2−stat6250): Are variable field values read into the data vector incorrectly if column values are specified but it is in free form?
- Answer (aoneill2−stat6250): Yes, it is parsed strictly according the specified columns.

[Course Textbook Chapter 17, Problem 5]
- Question (aoneill2−stat6250): Can the delimiter be declared merely in single quotes as an option?
- Question (aoneill2−stat6250): No, it needs to be enclosed in single quotes after dlm= or delimiter=.


[Course Textbook Chapter 17, Problem 7]
- Question (aoneill2−stat6250): Can input data that is in free form be read out of order?


[Course Textbook Chapter 17, Problem 8]
- Question (aoneill2−stat6250): 


[Course Textbook Chapter 17, Problem 10]
- Question (aoneill2−stat6250): 


[basic_recipe_to_load_remote_delimited_file (from Week 10 Overview)]
- Question (aoneill2−stat6250): 


[adv_recipe_to_load_remote_delimited_file (from Week 10 Overview)]
- Question (aoneill2−stat6250): 


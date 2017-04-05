## Course Structure Quiz Problems

In order to prepare your Week 2 Quiz submission, please edit ***this*** document to provide substantive questions for each Quiz Problem and SAS Recipe listed below, as well as answers to at least three questions raised.

All edits should conform to GitHub Markdown specifications (https://guides.github.com/features/mastering-markdown/) and should be committed to a branch named "week-2" or "week-02" in your fork of this repo. Then, after all edits have been made/committed, your Week 2 Quiz should be submitted by initiating a pull request using

- the master branch of the stat6250/course_questions_wiki repo as the base fork and

- the week-02 branch of your version of the repo as the head fork.

The instructor will then review the pull request and make comments should further revision be needed. Then, after the contents of the pull request have been finalized without any merge conflicts, the instructor will merge the pull request.

********************************************************************************


[Course Textbook Chapter 1, Problem 1]
- Question (meisenbach-stat6250): Are there any other variable types? Datetime? Boolean?
- Answer (meisenbach-stat6250): No but... "SAS converts date, time, and datetime values back and forth between calendar dates and clock times with SAS language elements called formats and informats" - SAS 9.4 Language Reference.

[Course Textbook Chapter 1, Problem 2]
- Question (meisenbach-stat6250): Is indenting within steps necessary?
- Answer (meisenbach-stat6250): No, but it helps with code readability.

[Course Textbook Chapter 1, Problem 3]
- Question (meisenbach-stat6250): What happens when you try to assign a character value to a numeric variable and vice versa?

[Course Textbook Chapter 1, Problem 4]
- Question (meisenbach-stat6250): SAS uses floating point representation for a numeric values? Does this cause inaccuracies when working with integer values?

[Course Textbook Chapter 1, Problem 5]
- Question (meisenbach-stat6250): Is SAS case sensitive? 
- Answer (meisenbach-stat6250): No

[Course Textbook Chapter 1, Problem 8]
- Question (meisenbach-stat6250): What happens when you try to assign a value larger than the defined length of the variable?

[Course Textbook Chapter 2, Problem 3]
- Question (meisenbach-stat6250): If possible, should you always store dates using four digits?

[Course Textbook Chapter 2, Problem 7]
- Question (meisenbach-stat6250): Why are librefs limited to 8 characters?

[Course Textbook Chapter 2, Problem 8]
- Question (meisenbach-stat6250): What is the default value for YEARCUTOFF=? Does this default update with newer versions of SAS?
- Answer (meisenbach-stat6250): 1926 for SAS 9.4 and beyond. It might. Previously the default was 1920.

[Course Textbook Chapter 2, Problem 9]
- Question (meisenbach-stat6250): <libref.>_ALL_ requests a listing of all files in the library. What happens with you name a dataset _all_ (which is a legal name)?

[loading_data_from_remote_Excel_file SAS Recipe (from Week 2 Overview)]
- Question (meisenbach-stat6250): What happens if I misspell something (e.g dbms → dms)?
- Answer (meisenbach-stat6250): You get a warning that the interpretor assumed symbol DBMS was misspelled as "dms" and the statement executes correctly.

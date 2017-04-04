## Course Structure Quiz Problems

In order to prepare your Week 2 Quiz submission, please edit ***this*** document to provide substantive questions for each Quiz Problem and SAS Recipe listed below, as well as answers to at least three questions raised.

All edits should conform to GitHub Markdown specifications (https://guides.github.com/features/mastering-markdown/) and should be committed to a branch named "week-2" or "week-02" in your fork of this repo. Then, after all edits have been made/committed, your Week 2 Quiz should be submitted by initiating a pull request using

- the master branch of the stat6250/course_questions_wiki repo as the base fork and

- the week-02 branch of your version of the repo as the head fork.

The instructor will then review the pull request and make comments should further revision be needed. Then, after the contents of the pull request have been finalized without any merge conflicts, the instructor will merge the pull request.

********************************************************************************


[Course Textbook Chapter 1, Problem 1]

* Question (aalshehry−stat6250): Will the following procedure print observations > 6 or variables > 7?

```php
proc print data=sashelp.cars;
    var Make Model;
    where Cylinders>6;
run;
```

[Course Textbook Chapter 1, Problem 2]

* Question (aalshehry−stat6250): Why should we use “run;” steatment many times within SAS program instead of one time at the end?

* Answer (aalshehry−stat6250): The "run;" statement is often not strictly required, as SAS will assume you want to start a new step when it sees data or proc. However your code will be clearer and easier to understand if you make the end of each step explicit.

[Course Textbook Chapter 1, Problem 3]

* Question (aalshehry−stat6250): How many type of variables does SAS support?

[Course Textbook Chapter 1, Problem 4]

* Question (aalshehry−stat6250): How to represent missing data in SAS dataset?

[Course Textbook Chapter 1, Problem 5]

* Question (aalshehry−stat6250): Can a character variable begins with a number?

[Course Textbook Chapter 1, Problem 8]

* Question (aalshehry−stat6250): Considering all numeric variables have a default length of 8 bytes, what is the maximum value that can SAS accept for a numeric variable?

* vAnswer (aalshehry−stat6250): ***************************

[Course Textbook Chapter 2, Problem 3]

* Question (aalshehry−stat6250): Where and how to use YEARCUTOFF option?

[Course Textbook Chapter 2, Problem 7]

* Question (aalshehry−stat6250): How to save your dataset in the permanent library?

[Course Textbook Chapter 2, Problem 8]

* Question (aalshehry−stat6250): Without using the YEARCUTOFF= option, how would SAS interpret 11/11/20? Is it 1920 or 2020?

* Answer (aalshehry−stat6250): The default value of YEARCUTOFF= is 1920.

[Course Textbook Chapter 2, Problem 9]

* Question (aalshehry−stat6250): If a SAS session is ended or a libref is deleted, does the library still exist?

* Answer (aalshehry−stat6250): In these cases, SAS no longer has access to the files in the library.

[basic_recipe_for_loading_data_from_remote_Excel_file (from Week 2 Overview)]

* Question (aalshehry−stat6250): Is it mandatory to use “filename tempfile clear;” step? Why?

[optional: bonus_advanced_recipe_for_loading_data_from_remote_Excel_file (from Week 2 Overview)]

* Question (aalshehry−stat6250):

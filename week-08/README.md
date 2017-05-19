## Week 8 Quiz Questions and Answers

In order to prepare your Week 8 Quiz submission, please edit ***this*** document to provide substantive questions for each Quiz Problem and SAS Recipe listed below, as well as answers to at least three questions raised.

All edits should conform to GitHub Markdown specifications (https://guides.github.com/features/mastering-markdown/) and should be committed to a branch named "week-8" in your fork of this repo. Then, after all edits have been made/committed, your Week 8 Quiz should be submitted by initiating a pull request using

- the master branch of the stat6250/course_questions_wiki repo as the base fork and

- the week-8 branch of your version of the repo as the head fork.

The instructor will then review the pull request and make comments should further revision be needed. Then, after the contents of the pull request have been finalized without any merge conflicts, the instructor will merge the pull request.

********************************************************************************



[Course Textbook Chapter 13, Problem 1]
- Question (yzhu12-stat6250): What will happen if the SUBSTR function is on the left side of an assignment? How about on the right side of an assignment?
- Answer (yzhu12-stat6250): When the SUBSTR function is on the left side of an assignment statement, it replaces variable values. When SUBSTR is on the right side of an assignment statement, it extracts variable values. 
- Question (akumar30−stat6250): What will be the output of mean function if all arguments has missing values?
- Answer (akumar30−stat6250): It will return a missing value.
- *Question* (lwang30-stat6250) : What value would SAS produce if "of" is not added in function D ?
- *Answer* (lwang30-stat6250) : SAS will give the mean of the difference between "var1" and "var4".
- Question (hhu9−stat6250): can we use mean(var1,var4) without "of" or we must use "of"?
- Question (meisenbach-stat6250): What happends if you specify var1-var4 and var3 does not exist?
- Question (rluo-stat6250): Where can we use SAS functions?
- Answer (rluo-stat6250): SAS functions can be used in DATA step programming statements.
– Question (nly13-stat6250): Can you use this same mechanics with alphabetical variable names?



[Course Textbook Chapter 13, Problem 2]
- Question (yzhu12-stat6250): What statement do we use if we want to ensure that all forms of a character string are found?
- Answer (yzhu12-stat6250): We can use the UPCASE or LOWCASE function with the INDEX function.
- Question (akumar30−stat6250): Can I use character variable to a function that requires numeric arguments?
- Answer (akumar30−stat6250): Yes, Automatic character-to-numeric conversion occurs when a character value is specified in a function that requires numeric arguments.
- *Question* (lwang30-stat6250) : Can SAS automatically convert numeric variable to character variable as well ?
- Question (hhu9−stat6250): In this case , I think PayRate is also should be numeric values right? LOG will show the information of data converted? 
- Answer (hhu9−stat6250): I think PayRate is also represented by numeric values, Log will show a massage that a  conversion has occurred.
- Question (meisenbach-stat6250): Why should you not rely on automatic conversion?
- Answer (meisenbach-stat6250): Sometimes SAS is unable to do the conversion (e.g. the PayRate contains a dollar sign).
- Question (rluo-stat6250): What is the target variables?
- Answer (rluo-stat6250): A target variable is the variable to whic the result of a function is assigned.
- Question (nly13-stat6250): When a numeric operation is involved, why does SAS automatically convert character variables to numeric?



[Course Textbook Chapter 13, Problem 3]
- Question (yzhu12-stat6250): What will happen if you specify an invalid data in the MDY function?
- Answer (yzhu12-stat6250):  A missing value will be assigned to the target variable.
- Question (akumar30−stat6250): What will happen if length specifies in input or put statement less than length of new variable?
- *Question* (lwang30-stat6250) : What does the PUT function do and how is it used ?
- *Answer* (lwang30-stat6250) : PUT function is able to convert numeric variable to character variable. In the parentheses, the variable and a format should be specified.
- Question (hhu9−stat6250): Which fuction should we use to convert character value to numeric value?
- Answer (hhu9−stat6250): we should use INPUT function.
- Question (meisenbach-stat6250): Does the width in an INFORMAT count the comma?
- Answer (meisenbach-stat6250): Yes, comma7 = 123,456
- Question (rluo-stat6250): What is the function of INPUT?
- Answer (rluo-stat6250): INPUT function converts character data values to numeric values.
- Question (nly13-stat6250): Does the width in an INFORMAT read the comma?



[Course Textbook Chapter 13, Problem 4]
- Question (yzhu12-stat6250): What kind of error will occur if you don't place the LENGTH statement before the assignment statements that contain the SCAN function?
- Question (akumar30−stat6250): Can I use ANSCI character chr(10) to concatenate multiple values separated by new line ?
- *Question* (lwang30-stat6250) : What other types of manipulation of variables is performed in this problem ?
- Question (hhu9−stat6250): Which fuction we should use to convert numeric values to character values?
- Answer (hhu9−stat6250): we should use PUT function.
- Question (meisenbach-stat6250): Does using PUT change the type of the original variable?
- Question (rluo-stat6250): How many SAS date functions are there? And what are they?
- Question (nly13-stat6250): Can you nest an INPUT statement in a PUT statement, and vice versa?


[Course Textbook Chapter 13, Problem 5]
- Question (yzhu12-stat6250): Even if a function doesn't require arguments, the function name must still be followed by what?
- Answer (yzhu12-stat6250): It still need to be followed by parentheses.
- Question (akumar30−stat6250): How to extract SAS date from numeric Date?
- *Question* (lwang30-stat6250) : What is the default YEARCUTOFF in SAS ?
- Question (hhu9−stat6250): how to write date in correct order in MDY function?
- Answer (hhu9−stat6250):  (moutn/day/year)
- Question (meisenbach-stat6250): What does YEARCUTOFF specify?
- Answer (meisenbach-stat6250): YEARCUTOFF specifies the first year of the 100 year span.
- Question (rluo-stat6250): What are the character functions?
- Question (nly13-stat6250): What is the correct order for the MDY function?
- Answer (nly13-stat6250): (mouth/day/year)



[Course Textbook Chapter 13, Problem 6]
- Question (yzhu12-stat6250): What do we need to do when specifying a variable list or an array as a function argument?
- Answer (yzhu12-stat6250): We need to precede the list or the array with the word OF.
- Question (akumar30−stat6250): Can I get fiscal calendar date, time and year in SAS?
- *Question* (lwang30-stat6250) : What other delimiters can be recognized by SAS when SCAN or other similar function is performed ?
- Question (hhu9−stat6250): In which situation we should specify delimiters in SCAN function?
- Question (meisenbach-stat6250): What does the SCAN function do?
- Answer (meisenbach-stat6250): The SCAN function is used to extract words using blanks and commas. The second argument is the nth word.
- Question (rluo-stat6250): How to use INT and ROUND functions?
- Question (nly13-stat6250): How do you use INT and ROUND functions?



[Course Textbook Chapter 13, Problem 7]
- Question (yzhu12-stat6250): What function can you use if you want to replace or remove patterns of characters in the values of character variables?
- Answer (yzhu12-stat6250): You can use TRANWRD function.
- Question (akumar30−stat6250): What will be happen if third argument will be missing from SUBSTR function?
- Answer (akumar30−stat6250):  If third argument (n) is omitted, all remaining characters are replaced.
- *Question* (lwang30-stat6250) : What other function is "substr" able to do in SAS ?
- *Answer* (lwang30-stat6250) : "substr" function can also be used to replace variable values when it is used on the left side of an assignment statement.
- Question (hhu9−stat6250):If we dont know the exact position of the substring, which function should we use?
- Question (meisenbach-stat6250): What happens when you do not give the number of characters to extract?
- Answer (meisenbach-stat6250): You get the rest of the string.
- Question (rluo-stat6250): What functions can we nest, and how many functions can we nest?
- Question (nly13-stat6250): What is the difference between SCAN and SUBSTR?
- Answer (nly13-stat6250): Scan relies on delimiters, while SUBSTR reads values from specified locations.



[Course Textbook Chapter 13, Problem 10]
- Question (yzhu12-stat6250): How can you test character values for the presence of a string?
- Answer (yzhu12-stat6250): You need to  use the INDEX function and specify, in parentheses, the name of the variable and the string enclosed in quotation marks.
- Question (akumar30−stat6250): Can I use trim function to store the variable with no trailing spaces?
- Answer (akumar30−stat6250): TRIM function does not affect how a variable is stored. The trimmed values are padded with trailing blanks again if the values are shorter than the length of the new variable.
- *Question* (lwang30-stat6250) : What functions can be used to make sure the search for the string is not case-sensitive ?
- Question (hhu9−stat6250):What is the differece between INDEX function and INDEXC function?
- Question (meisenbach-stat6250): Is it necessary to lowercase the variable that you are searching in?
- Answer (meisenbach-stat6250): No but it’s safer to do so.
- Question (rluo-stat6250): What is the purpose to modify the data value?
- Question (nly13-stat6250): What does the INDEX function do?
- Answer (nly13-stat6250): This function enables you to search a character value for a specified string.


[recipe_for_isolating_all_duplicates (from Week 8 Overview)]
- Question (yzhu12-stat6250): In the example, the code first*School_Code*last*School_Code=0 is used to ensure that if and only if a value of School_Code only appears exactly once in a dataset. So why doesn't it has the same code to analysis the County_Code and District_Code?
- Question (akumar30−stat6250): If we are removing duplicates in SAS, does also remove duplicate missing value?
- *Question* (lwang30-stat6250) : How do we identify which is the most deeply nested column in a composite key ?
- Question (hhu9−stat6250):during this process,How to reduce the space occupied by duplicates when we meet a big dataset?
- Question (meisenbach-stat6250): What is the benefit of using this method for removing duplicate row?
- Answer (meisenbach-stat6250): This method outputs all row which have duplicate key values and allows you to review them.
- Question (rluo-stat6250): What is the difference between using proc sort, the duput= option and this method?
- Question (nly13-stat6250): What is the difference between using proc sort with dupout= option and this method?


[recipe_for_drop_and_swap (from Week 8 Overview)]
- Question (yzhu12-stat6250): What statement can you use if you only want to drop several rows from a particular variable?
- Question (akumar30−stat6250): How to remove special character from SAS Dataset and convert them in to decimal variable?
- Answer (akumar30−stat6250):  using compress (id,'0123456789.','k') option result will show only decimal variable. Here id contains the special character. 
- *Question* (lwang30-stat6250) : What is the consequence if the compress function with "kd" option is not used in the business logic ?
- Question (hhu9−stat6250): How can we drop variables in PROC DATASETS.
- Question (meisenbach-stat6250): Why is it necessary to rename the High_Grade variable?
- Answer (meisenbach-stat6250): This is necesary in order to be able to create a new numeric variable with the same name.
- Question (rluo-stat6250): What three statements will be used to change the value type and drop the original value?
- Question (nly13-stat6250): Why is it necessary to rename High_Grade?



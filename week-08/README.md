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
- Answer (mcardoso3-stat6250):  The variable lists and arrays would be processed and outputted with var3 omitted.
- Question (rluo-stat6250): Where can we use SAS functions?
- Answer (rluo-stat6250): SAS functions can be used in DATA step programming statements.
– Question (nly13-stat6250): Can you use this same mechanics with alphabetical variable names?
- Question (yyan11−stat6250): How to use a SAS function?
- Answer (yyan11−stat6250): To use a SAS function, specify the function name followed by the function arguments, which are enclosed in parentheses. General form, SAS function:function-name(argument-1<,argument-n>)
- Question (kveng−stat6250): Do we really need to word OF inside the mean function?
- Answer (kveng−stat6250): If you omit the word OF, the function argument might not be interpreted as expected. 
- Question (aoneill2-stat6250): How many arguments does the mean function take?
- Answer (aoneill2-stat6250): The mean function can have as many arguments as there are values to take the average of, but can also appear as an expression of a range of values of variables in an array, such as mean(of x1-x3) which is equivalent to mean(x1,x2,x3).
- Question (yren10-stat6250): What would happen if we forgot to use "of"?
- Answer (yren10-stat6250): The function argument might not be interpreted as expected.
- Question (cyuan10-stat6250): Is there a way to write the code is that you can specify to calculate all the variables or do we have to list them all out individually?
* *Question (aalshehry−stat6250):* How does MEAN function deal with missing values?
- Answer (mcardoso3-stat6250):  The MEAN function would calculate the average of the selected variables with the missing values counted as blanks or zeroes.
- Question (lzhao4-stat6250): What happens if you forget to use “of” when specify a range of variables as the function argument?
- Answer (lzhao4-stat6250): The function argument won’t execute. 



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
- Question (yyan11−stat6250): Does SAS convert character values to numeric values?
- Answer (yyan11−stat6250): By default, if you reference a character variable in a numeric context such as an arithmetic operation, SAS tries to convert the variable values to numeric.
- Question (kveng−stat6250): Is it better to specify the data type of PayRate in advance to numberic?
- Answer (mcardoso3-stat6250):  Specifying the data type of PayRate in advance is better so that there is no mistake of te type as you work further into your dataset.
- Question (aoneill2-stat6250): What is the resulting value type when you mix char and numeric vars in a function operation?
- Answer (aoneill2-stat6250): SAS will automatically convert the character variable to a numeric variable, but there is a chance it may not work.
- Question (yren10-stat6250): What would output shows after SAS automatically converts the character values to numeric values?
- Question (cyuan10-stat6250): What happens if we have two numeric of different lengths?
- Answer (cyuan10-stat6250): SAS will automatically return a data that has the length of the longest numeric input.
* *Question (aalshehry−stat6250):* How SAS will deal with variable values in arithmetic operation?
* *Answer (aalshehry−stat6250):* SAS automatically converts the variable values to numeric by creating a temporary numeric value for each 
character value which will be used in the calculation. Besides, SAS issues a message in the log showing that the conversion has been occurred.
- Question (lzhao4−stat6250): In which situation would the automatic conversion occur?
- Answer (mcardoso3-stat6250):  When variables from a certain type are assigned to a previously defined opposite type, an automatic conversion occurs.



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
- Question (yyan11−stat6250): What happens if skip the INPUT function or the PUT function when converting data?
- Answer (yyan11−stat6250): SAS will detect the mismatched variables and will try an automatic character-to-numeric or numeric-to-character conversion. However, this process doesn't always work. Therefore, it is always best to include INPUT and PUT functions in your programs to avoid data type mismatches and circumvent automatic conversion.
- Question (kveng−stat6250): What is the different between comma6 and comma7 here?
- Answer (kveng−stat6250): The numeric informat "comma6." tells SAS that you want to read in a number that contains a comma and takes up to 6 spaces (including the comma)
- Question (aoneill2-stat6250): How many values must be accommodated in a format for a numeric value - do characters like commas and decimals count?
- Answer (aoneill2-stat6250): Yes, in a format statement such as comma7. the comma counts as one of the 7 "digits" even though the comma itself is not really a numerical value itself.
- Question (aoneill2-stat6250): In a numeric variable format, what does it mean when it ends in a decimal?
- Question (yren10-stat6250): What the difference between the 1nput and put, what difference they will make in output?
- Answer (mcardoso3-stat6250):  INPUT requires an informat, whereas PUT requires a format.  In ouput, the format can be a number value as a character type, while the informat would read it as a numeric type.
- Question (cyuan10-stat6250): Does the width of the input include the comma?
- Answer (cyuan10-stat6250): Yes, for example 123,456 is a comma7 because the "," is read.
* *Question (aalshehry−stat6250):* How to convert variable values with a dollar sign to numeric?
- Answer (mcardoso3-stat6250):  It is best in this case to include INPUT and PUT functions in your programs to avoid data type mismatches.
- Question (lzhao4−stat6250): What is the correct format for INPUT function?



[Course Textbook Chapter 13, Problem 4]
- Question (yzhu12-stat6250): What kind of error will occur if you don't place the LENGTH statement before the assignment statements that contain the SCAN function?
- Question (akumar30−stat6250): Can I use ANSCI character chr(10) to concatenate multiple values separated by new line ?
- *Question* (lwang30-stat6250) : What other types of manipulation of variables is performed in this problem ?
- Question (hhu9−stat6250): Which fuction we should use to convert numeric values to character values?
- Answer (hhu9−stat6250): we should use PUT function.
- Question (meisenbach-stat6250): Does using PUT change the type of the original variable?
- Answer (mcardoso3-stat6250):  Yes, PUT performs numeric-to-character conversions, so the function changes one type of variable.
- Question (rluo-stat6250): How many SAS date functions are there? And what are they?
- Answer (mcardoso3-stat6250):  There are several date functions with the book listing 12.  The typical use of date functions are MDY, TODAYDATE, and TIME while  few selected functions include DAY, QTR, WEEKDAY, MONTH, and YEAR.
- Question (nly13-stat6250): Can you nest an INPUT statement in a PUT statement, and vice versa?
- Question (yyan11−stat6250): What is the difference between the INPUT function and the PUT function?
- Answer (yyan11−stat6250): To use the INPUT function to convert character data values to numeric values. And you can use the PUT function to explicitly convert numeric data values to character data values.
- Question (kveng−stat6250): What is the different between PUT() and  INPUT()?
- Answer (kveng−stat6250): (1) PUT() always creates character variables; (2) INPUT() can create character or numeric variables based on the informat; (3) The source format must match the source variable type in PUT(); and (4) The source variable type for INPUT() must always be character variables.
- Question (aoneill2-stat6250): In formatting char values to assign as numeric values to variables, what is the function used - "put" or "input"?
- Answer (aoneill2-stat6250): The input function converts char vars to numeric vars, and the put function does vice versa.
- Question (yren10-stat6250): By using 4.1 on d selection, Is it just because we are having 3 numbers and dot, so we are using n+1 and its 4?
- Question (cyuan10-stat6250): In these cases, if we wish for SAS to include a ending zero such as "12.30", how do we specify it?
* *Question (aalshehry−stat6250):* What is the difference between INPUT and PUT?
* *Answer (aalshehry−stat6250):* INPUT function is used to to convert character data values to numeric values while PUT function converts numeric data values to character
data values.
- Question (lzhao4−stat6250): What is the correct format for PUT function? 



[Course Textbook Chapter 13, Problem 5]
- Question (yzhu12-stat6250): Even if a function doesn't require arguments, the function name must still be followed by what?
- Answer (yzhu12-stat6250): It still need to be followed by parentheses.
- Question (akumar30−stat6250): How to extract SAS date from numeric Date?
- *Question* (lwang30-stat6250) : What is the default YEARCUTOFF in SAS ?
- Answer (mcardoso3-stat6250):  The default YEARCUTOFF= in SAS is 1920.
- Question (hhu9−stat6250): how to write date in correct order in MDY function?
- Answer (hhu9−stat6250):  (moutn/day/year)
- Question (meisenbach-stat6250): What does YEARCUTOFF specify?
- Answer (meisenbach-stat6250): YEARCUTOFF specifies the first year of the 100 year span.
- Question (rluo-stat6250): What are the character functions?
- Question (nly13-stat6250): What is the correct order for the MDY function?
- Answer (nly13-stat6250): (mouth/day/year)
- Question (yyan11−stat6250): What is the MDY function?
- Answer (yyan11−stat6250): The MDY function creates a SAS date value from numeric values that represent the month, day, and year.
- Question (kveng−stat6250): How does YEARCUTOFF work?
- Question (aoneill2-stat6250): Does MDY format in Year of cutoff value require only a 2-digit year in the year of the cutoff itself - i.e., if the cutoff year is year 0?
- Answer (mcardoso3-stat6250):  MDY accepts two-digit values, but the YEARCUTOFF= option interprets the value as a 100 year span, so four-digit values in the MDY function is recommended.
- Question (yren10-stat6250): Does MDY means month goes first then day and year?
- Answer (yren10-stat6250): Yes, month number then date then full year number, and don't start with 0.
- Question (cyuan10-stat6250): What happens if you only use (1,3,20) for MDY?
- Answer (cyuan10-stat6250): Since the YEARCUTOFF is defaulted to 1920, then your output would display 1920 instead of 2020.
* *Question (aalshehry−stat6250):* Whenever possible, use four-digit year values in the MDY function, why?
- Question (lzhao4−stat6250): What is the general format for MDY function?
- Answer (lzhao4-stat6250): MDY(month,day,year) 



[Course Textbook Chapter 13, Problem 6]
- Question (yzhu12-stat6250): What do we need to do when specifying a variable list or an array as a function argument?
- Answer (yzhu12-stat6250): We need to precede the list or the array with the word OF.
- Question (akumar30−stat6250): Can I get fiscal calendar date, time and year in SAS?
- *Question* (lwang30-stat6250) : What other delimiters can be recognized by SAS when SCAN or other similar function is performed ?
- Question (hhu9−stat6250): In which situation we should specify delimiters in SCAN function?
- Question (meisenbach-stat6250): What does the SCAN function do?
- Answer (meisenbach-stat6250): The SCAN function is used to extract words using blanks and commas. The second argument is the nth word.
- Question (rluo-stat6250): How to use INT and ROUND functions?
- Answer (mcardoso3-stat6250):  INT is an argument expressed in SAS to return the integer portion of a numeric value and ROUND is an argument expressed in SAS to round to the nearest specified unit.
- Question (nly13-stat6250): How do you use INT and ROUND functions?
- Question (yyan11−stat6250): When can I use the SCAN function?
- Answer (yyan11−stat6250): The SCAN function is best used when you know the order of the words in the character value the starting position of the words varies the words are marked by some delimiter.
- Question (kveng−stat6250): Is there a substr function in SAS?
- Answer (mcardoso3-stat6250):  Yes, SUBSTR extracts a portion of a value by starting at a specified location.
- Question (aoneill2-stat6250): In reading in a string to store a subset of it, is there a way to make SAS take the characters from the RHS without having to count the number of characters in the original string or the number of characters leading up to it?
- Question (yren10-stat6250): How we deal with the space and the comma when doing the assign?
- Answer (yren10-stat6250): You don't need to specify delimiters, because the blank and the comma are default delimiters.
- Question (cyuan10-stat6250): If the character data includes a number, will the scan function automatically create a new numeric variable?
* *Question (aalshehry−stat6250):* How to use SCAN function when the delimiter is TAB key?
- Question (lzhao4−stat6250): What are the default delimiters in SCAN function?
- Answer (lzhao4-stat6250): The comma and blank are default delimiters.  



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
- Answer (mcardoso3-stat6250):  We can nest any functions as long as the as the function that is used as the argument meets the requirements for the argument.
- Question (nly13-stat6250): What is the difference between SCAN and SUBSTR?
- Answer (nly13-stat6250): Scan relies on delimiters, while SUBSTR reads values from specified locations.
- Question (yyan11−stat6250): When can I use the SUBSTR function?
- Answer (yyan11−stat6250): The SUBSTR function is best used when you know the exact position of the string that you want to extract from the character value. The string does not need to be marked by delimiters. 
- Question (kveng−stat6250): What is the defference between SCAN and substr?
- Question (aoneill2-stat6250): Do you use scan or substr function to locate single-char input in a string and do you have to specify with a separate arg the length of the substring if only one char?
- Answer (mcardoso3-stat6250):  Using SUBSTR would be preferable in this case because there are no delimiters.  If there is only one char, all characters are included in the substring.
- Question (yren10-stat6250): When we usually use the SUBSTR function?
- Question (cyuan10-stat6250): How do you deal with data where similar information is stored in different parts/length of a single variable?
* *Question (aalshehry−stat6250):* Can SUBSTR function be used with matrix?
- Question (lzhao4−stat6250): When should we use SUBSTR function rather than the SCAN function?



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
- Question (yyan11−stat6250): What is the INDEX function?
- Answer (yyan11−stat6250): The INDEX function enables you to search a character value for a specified string. The INDEX function searches values from left to right, looking for the first occurrence of the string. It returns the position of the string's first character; if the string is not found, it returns a value of 0.
- Question (kveng−stat6250): What is the difference between index function and substr?
- Answer (mcardoso3-stat6250):  Both functions deal with a specified string, but INDEX allows you to search a character value, while SUBSTR lets you extract any number of characters.
- Question (aoneill2-stat6250): How does the index function work to find values of a given bar in a given dataset?
- Answer (mcardoso3-stat6250):  You would want create a dataset that contains values that correspond to the given bar, and the INDEX function can complete this search.
- Question (yren10-stat6250): Why we need set returning value greater than 0, what would happen if we don't set it greater than 0?
- Question (cyuan10-stat6250): Since the old area code and the new area code both start with '9', then technically, can we only change the last two digits?
* *Question (aalshehry−stat6250):* Can INDEX function be used to search for the last occurance for a certain value?
- Question (lzhao4−stat6250): What is the default order when use INDEX function to search values?



[recipe_for_isolating_all_duplicates (from Week 8 Overview)]
- Question (yzhu12-stat6250): In the example, the code first*School_Code*last*School_Code=0 is used to ensure that if and only if a value of School_Code only appears exactly once in a dataset. So why doesn't it has the same code to analysis the County_Code and District_Code?
- Question (akumar30−stat6250): If we are removing duplicates in SAS, does also remove duplicate missing value?
- Answer (mcardoso3-stat6250):  Yes, all duplicates are isolated with respect to the composite specified key in the BY step, so they are all removed from the original dataset.
- *Question* (lwang30-stat6250) : How do we identify which is the most deeply nested column in a composite key ?
- Question (hhu9−stat6250):during this process,How to reduce the space occupied by duplicates when we meet a big dataset?
- Question (meisenbach-stat6250): What is the benefit of using this method for removing duplicate row?
- Answer (meisenbach-stat6250): This method outputs all row which have duplicate key values and allows you to review them.
- Question (rluo-stat6250): What is the difference between using proc sort, the duput= option and this method?
- Question (nly13-stat6250): What is the difference between using proc sort with dupout= option and this method?
- Question (yyan11−stat6250): In the composite key, which variables are used to identify duplicates?
- Question (kveng−stat6250): Instead of using the first.School_Code * last.School_Code = 0, is there a convenient function  to call that would check for duplicate? 
- Question (aoneill2-stat6250): How does SAS know to loop through the entire program with just one line of code?
- Answer (aoneill2-stat6250): The run statement in a data step is the end of an implied loop.
- Question (yren10-stat6250): What does the first_column mutiply last_column do in the command?
- Question (cyuan10-stat6250): Then the sort function includes 3 variables, then does it proceed to sort in order of how the variables are listed?
* *Question (aalshehry−stat6250):* Can we do the doublecate comparision without isolating the rows in a temperory dataset?
- Question (lzhao4−stat6250): Can we use same method to isolate only part of the duplicates when needed?
- Answer (mcardoso3-stat6250):  Yes, by using an IF-THEN statement, you can specify what duplicates you would like to isolate or keep in the dataset.



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
- Question (yyan11−stat6250): In this example, it is converted to a numeric value using the input function and the format best12., which is the default format for numerical variable having no value after the decimal point. But, if I want to keep two decimal place, how can I do it?
- Question (kveng−stat6250): Do we have to specify the drop = dataset option at the top of the data step?
- Answer (mcardoso3-stat6250):  It depends where you specify the DROP= option on how you want to reference the variables in the DATA step.
- Question (aoneill2-stat6250): Why is best12. the format used for the value assigned to High_Grade?
- Answer (aoneill2-stat6250): best12. is the default format for assigning a numeric value without any decimal part.
- Question (yren10-stat6250): Why the dataset needed temporarilly rename when procs the function?
- Question (cyuan10-stat6250): For what reasons do we create a temporary varaible name High_Grade_character for High_Grade and what does does it play in the data step?
- Answer (mcardoso3-stat6250):  High_Grade_Character is used to determine what values to place in the newly created column High_Grade before to being converted to a numeric value.
* *Question (aalshehry−stat6250):* What are the modifiers that COMPRESS function accept?
* *Answer (aalshehry−stat6250):* 
   - a:	adds uppercase and lowercase letters
   - d:	adds numerals (digits)
   - i:	ignores case
   - k:	keeps listed characters instead of removing them
   - s:	adds space (blank, tabs, lf, cr) to the list
   - p:	adds punctuation 
- Question (lzhao4−stat6250): Can we take same process and simply use PUT function to replace the INPUT function when we want to return a numeric value as a character string?



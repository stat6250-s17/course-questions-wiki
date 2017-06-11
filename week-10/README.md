## Week 10 Quiz Questions and Answers

In order to prepare your Week 10 Quiz submission, please edit ***this*** document to provide substantive questions for each Quiz Problem and SAS Recipe listed below, as well as answers to at least three questions raised.

All edits should conform to GitHub Markdown specifications (https://guides.github.com/features/mastering-markdown/) and should be committed to a branch named "week-10" in your fork of this repo. Then, after all edits have been made/committed, your Week 10 Quiz should be submitted by initiating a pull request using

- the master branch of the stat6250/course_questions_wiki repo as the base fork and

- the week-10 branch of your version of the repo as the head fork.

The instructor will then review the pull request and make comments should further revision be needed. Then, after the contents of the pull request have been finalized without any merge conflicts, the instructor will merge the pull request.

********************************************************************************



[Course Textbook Chapter 16, Problem 1]
* *Question (aalshehry−stat6250):* In INPUT statement, can you re-read the fields? 
* *Answer (aalshehry−stat6250):* Yes, Fields or parts of fields can be re-read.
- Question (dlee117−stat6250): When using column input, can it read character variable values that contain embedded blanks?
- Answer (dlee117-stat6250): Yes, column input can be used to read values that contain embedded blanks. You just need to specify the correct column locations and it will be able to read it.
- Question (akumar30−stat6250): Can we change the order of variables specifies in input statement?
- Answer (mcardoso3-stat6250): Though a feature of column input lets you read fields in any order, the variables are always listed in the order in which they were created by default in the data set.
- Question (rluo-stat6250): What is the function of the column input?
- Answer (rluo-stat6250): Column input can be used to read raw data that is stored in an external file. 
- Question (yyan11−stat6250): How many input styles does SAS provide?
- Answer (yyan11−stat6250): SAS provides three primary input styles: column input, formatted input, and list input. 
- Question (aoneill2−stat6250): Is it necessary to leave unused columns in columnar-formatted data?
- Answer (aoneill2−stat6250): No, it is not necessary to use spaces or other delimiters.
- Question (mcardoso3-stat6250):  How would you use column input to read variables?
- Answer (mcardoso3-stat6250):  You can read data values by first typing "input" followed by the first variable name, then the values for the respected variable ($ for numeric), and then inserting a semicolon. 
- Question (yzhu12-stat6250): What are the two input styles for reading data in fixed fields and what's the function of them?
- Answer (yzhu12-stat6250): They are column input and format input. Column input reads standard data only and format input read both standard and nonstandard data.
- Question (aoneill2−stat6250): Can you read in data if you don't know what type of variable/s are to be scanned?
- Answer (aoneill2−stat6250): Yes, you could generalize the data input function as character input, so that both character and numeric data are treated the same.
- Question (aoneill2−stat6250):Are there any limitations on reading in colunn input?
- Answer (aoneill2−stat6250): Yes, column input can only be used on character or numeric data.
- Question (aoneill2−stat6250): What is the benefit of using informats on inputing data?
- Answer (aoneill2−stat6250): When you use infomats, you don't have to specify the number of characters or digits.
- Question (mcardoso3-stat6250):  What is the purpose of an informat?
- Answer (mcardoso3-stat6250):  An informat is an instruction that tells SAS how to read raw data.



[Course Textbook Chapter 16, Problem 5] 
* *Question (aalshehry−stat6250):* What kind of delimiter does INFORMAT contains?
* *Answer (aalshehry−stat6250):*  INFORMAT contains a period which is a required delimiter.
- Question (dlee117−stat6250): What does the informat $w. do? 
- Answer (dlee117-stat6250): It enables you to read character data. The w represents the field width.
- Question (akumar30−stat6250): Can we read nonstandard numeric data without using informat instructions?  
- Answer (akumar30−stat6250): No, we have to use informat instructions in specified format for each type of nonstandard numeric data.
- Question (rluo-stat6250): What are the features of the column input?
- Answer (mcardoso3-stat6250):  There are 4 column input features:  reading character variable values that contain embedded blanks, no placeholder is required for missing data, fields or parts of fields can be re-read, and fields do not need to be separated by blanks or other delimiters.
- Question (yyan11−stat6250): What does the $w. represent?
- Answer (yyan11−stat6250): The $w. informat enables you to read character data. The w represents the field width of the data value (the total number of columns that contain the raw data field).
- Question (aoneill2−stat6250): What does the period mean at the end of an informat?
- Answer (aoneill2−stat6250): The period ends the informat.
- Question (aoneill2−stat6250): Why does an informat need to be "ended?"
- Answer (aoneill2−stat6250): The period functions as a delimiter to tell SAS when to stop reading the informat.
- Question (mcardoso3-stat6250):  What are the different types of informats that can be used to read character data?
- Answer (aoneill2−stat6250): Some informats include fixed and variable-width character values, standard numerical data and numerical data with commas, dollar signs, percent signs, dashes, parentheses, binary data, hexadecimal data, etc.
- Question (yzhu12-stat6250): What's the difference between standard numeric data and nonstandard numeric data?
- Answer (yzhu12-stat6250): Standard numeric data values are values that contain only numbers, date/time, scientific notation, decimal points, and plus and minus signs. When numeric data contains characters such as commas or dollar signs, the data is considered to be nonstandard. 
- Question (aoneill2−stat6250): What happens if you specify a character informat to read in a numerical value?
- Answer (aoneill2−stat6250): The numerical value will be treated as a character.



[Course Textbook Chapter 16, Problem 7]
* *Question (aalshehry−stat6250):* In INPUT statement, what do “+” and “@” do? 
* *Answer (aalshehry−stat6250):* The + moves the pointer forward ,however, @ moves the pointer back
- Question (dlee117−stat6250): Are there any informats that do not contain a period?
- Answer (dlee117-stat6250): No, each informat always contains a period because it is a required delimiter.
- Question (akumar30−stat6250): Does auto cast applies if we specified the format of numeric data as character in input statement?
- Answer (aoneill2−stat6250): Yes, if a character informat is used on numeric input, it is auto-cast as a character value.
- Question (rluo-stat6250): What is standard numeric data?
- Answer (mcardoso3-stat6250):  Standard numeric data are values that can only contain numbers, decimal points, scientific notation, and plus and minus signs.
- Question (yyan11−stat6250): Which one could be used to read numeric values?
- Answer (yyan11−stat6250): The COMMAw.d informat is used to read numeric values and to remove embedded blanks, commas, dashes, dollar signs, percent signs, right parentheses, left parentheses, which are interpreted as minus signs.
- Question (aoneill2−stat6250): If the default for the input argument is column 1, then isn't it the same to read a piece of data that starts in column 7 either with input @7 or input +6?
- Answer (aoneill2−stat6250): Yes, that's true. In the possible answers, there is a missing period at the end of the informat for Item in answer (d).
- Question (mcardoso3-stat6250):  What do + and @ indicate when reading column variables?
- Answer (aoneill2−stat6250): Input +d moves the pointer to column 1+d to begin reading, whereas @d moves the pointer to column d to begin reading in data.
- Question (yzhu12-stat6250): What are the two most common types of record formats?
- Answer (yzhu12-stat6250): Fixed-length records and variable length records. 
- Question (aoneill2−stat6250): Where is the position of the pointer if input +8 format is used to read in a piece of data?
- Answer (aoneill2−stat6250): Since the default position of the pointer is column 1, input +8 starts reading beginning with column 9.



[Course Textbook Chapter 16, Problem 8] 
* *Question (aalshehry−stat6250):* What does COMMAw.d informat used for?
- Answer (mcardoso3-stat6250):  The COMMAw.d informat is used for reading numeric values and to remove embedded blanks, commas, hyphens, dollar signs, percent signs, close parentheses, and open parentheses.
- Question (dlee117−stat6250): What is the difference between @n column pointer control and +n pointer control?
- Answer (mcardoso3-stat6250):  An @n column pointer control moves a pointer forward or backward when reading a record, while a +n pointer control moves the input pointer forward to a column number that is relative to the current position.
- Question (akumar30−stat6250): What is the advantage of COMMAw.d informat?
- Answer (akumar30−stat6250): It is used to read numeric values and to remove embedded blanks, commas, dashes, dollar signs, percent signs and right parentheses.
- Question (rluo-stat6250): What does nonstandard numeric dat include?
- Answer (rluo-stat6250): values that contain special characters, date and time values, and data in fraction, binary and hexadecimal.
- Question (yyan11−stat6250): What are three parts of the COMMAw.d informat?
- Answer (yyan11−stat6250): 1. the informat name COMMA; 2. a value that specifies the width of the field to be read (including dollar signs, decimal w. places, or other special characters), followed by a period; 3. an optional value that specifies the number of implied decimal places for a value (not d necessary if the value already contains decimal places).
- Question (aoneill2−stat6250): Do you have to count everything including $ signs, commas, and decimals in determining the informant for reading in dollar and cents values?
- Answer (aoneill2−stat6250): Yes, everything counts towards the number preceding the period marking the separation between the overall character count and the number of decimal places.
- Question (aoneill2−stat6250): Does a decimal number informant include a second period at the end to end the informant itself?
- Answer (aoneill2−stat6250): No, not for a decimal number. It does not apply for this informant.
- Question (mcardoso3-stat6250):  What does comma7 or comma9 supposed to mean?
- Answer (mcardoso3-stat6250):  The COMMAw.d informat is used to read numeric values and to remove embedded characters.
- Question (yzhu12-stat6250): When reading variable-length records that contain fixed-field data, you can avoid problems by using which statement in the INFILE statement?
- Answer (yzhu12-stat6250): You can use the PAD option.



[Course Textbook Chapter 16, Problem 9] 
* *Question (aalshehry−stat6250):* What does “w” and “d” represent in COMMAw.d informat?
- Question (aoneill2−stat6250): "w" stands for the width of the number including the comma, a possible decimal point, any dollar sign preceding the number, and up to "d" decimal places following the decimal.
- Question (dlee117−stat6250): If the first field is located in column 1, do you need to use column pointer control to read this field?
- Answer (mcardoso3-stat6250):  Depending on your current position, you may need to use a @n column pointer to move backwards if you are looking at a column far past the range of column 1.
- Question (akumar30−stat6250): How to write an input statement if we don’t know the length of each base column in raw data?
- Question (aoneill2−stat6250): In variable-length data input, a delimiter must be used - usually a space, tab, or comma or else a pointer to indicate the beginning of the next field. A $ sign must be used to indicate a character variable, but the default is otherwise numeric input, and the default length of a numeric field is 8 digits. If reading in a character variable of variable length, the default is also a length of 8 characters or until a delimiter or end of file mark is encountered.
- Question (rluo-stat6250): What styles can we choose when encountering raw data that is organized into fixed fields?
- Question (aoneill2−stat6250): In terms of styles of input formats, with fixed fields we can use column input with the most convenience and versatility.
- Question (yyan11−stat6250): How to use the @n column pointer control?
- Answer (yyan11−stat6250): The @n is an absolute pointer control that moves the input pointer to a specific column number. The @ moves the pointer to column n, which is the first column of the field that is being read.
- Question (aoneill2−stat6250): If you read in blank spaces preceding a number, is it still stored in the same manner?
- Answer (aoneill2−stat6250): Yes, because the number's formatting is determined by its informant, and not by blank spaces.
- Question (aoneill2−stat6250): Should you use the comma informant to read in dollar values with commas in them?
- Answer (aoneill2−stat6250): No, because the comma and the $ sign are included as characters in the first part of the informant before the period that separates it from the number of decimal places, and the comma-informant actually strips the field value that is read of the dollar sign, along with any other embedded symbols, which is a good solution if you want the value to be stored only as a number.
- Question (mcardoso3-stat6250):  What happens if the variable-length of each record changes when formatting your column variables?
- Question (yzhu12-stat6250): What is the function of @n?
- Answer (yzhu12-stat6250): The @n is an absolute pointer control that moves the input pointer to a specific column number. You can read columns in any order with the @n column pointer control. 



[Course Textbook Chapter 17, Problem 1] 
* *Question (aalshehry−stat6250):* How is a free-format different from a formatted input?
- Answer (aoneill2−stat6250): Free-format does not have to specify field width and relies upon delimiters and end of file markers to tell SAS that it can stop reading in a field value and go on to the next.
- Question (dlee117−stat6250): What is the definition and purpose of a delimiter?
- Answer (aoneill2−stat6250): A delimiter is used to tell SAS that an end of record has been reached in reading input data. It is also used in telling the SAS system when to stop reading an informat formatting specification.
- Question (akumar30−stat6250):  What is free-format raw data in SAS?
- Answer (akumar30−stat6250): Data that is not arranged in columns or do not begin and end in the same columns is classified as free-format raw data.
- Question (rluo-stat6250): What is free-format data?
- Answer (aoneill2−stat6250): Free-format data is data that does not come in fixed-width fields and can begin and end in any column different from the previous row of data or set of records.
- Question (yyan11−stat6250): What is Free-format?
- Answer (yyan11−stat6250): Free-format is not arranged in fixed fields, the fields are often separated by blanks or by some other delimiter. In this case, column input and formatted input that you might have used before to read standard and nonstandard data in fixed fields will not enable you to read all of the values in the raw data file.
- Question (aoneill2−stat6250): What happens if you read in free-form data that is also variable in length for some field?
- Answer (aoneill2−stat6250): It can generate an error and leave the value blank if the system attempts to read more characters than are available before an end-of-record marker is reached.
- Question (mcardoso3-stat6250):  What is the difference between raw data files that are free-format, mixed-format, arragned in fixed fields, and arranged in columns?
- Answer (aoneill2−stat6250): Free-format data can start in any column and fields must be separated by delimiters with end of row data specified by end of record or and end of file. Mixed-format data can include free-form and column data. Fixed-fields are fields of set length, separated by delimiters or beginning in a given column and arrived at using a pointer. Column data begins and ends in given ranges of columns, but may include embedded spaces or spaces at the front or the end of the field.
- Question (yzhu12-stat6250): When can you specify a range of variables in the INPUT statement? 
- Answer (yzhu12-stat6250): You can also specify a range of variables in the INPUT statement when the variable values in the raw data file are sequential and are separated by blanks (or by some other delimiter).



[Course Textbook Chapter 17, Problem 2] 
* *Question (aalshehry−stat6250):* Do we have to use the dollar sign before a character variable?
- Answer (aoneill2−stat6250): Yes, you must use a dollar sign to read in a character variable, or it is assumed to be numeric data. If so, it generates an error and is treated as a missing value.
- Question (dlee117−stat6250): What is the definition and purpose of a delimiter?
- Answer (aoneill2−stat6250): A delimiter is used to indidiate end of a record field or to tell the SAS system that an informat is finished being read and can be interpreted.
- Question (akumar30−stat6250):  Can we use list input to convert free-format raw data to columns row data?
- Answer (mcardoso3-stat6250):  Yes, since list input can read both standard and nonstandard free-format data, it is easy for it to convert the free-format raw data.
- Question (rluo-stat6250): Can list input read both standard and nonstandard free-format data?
- Answer (rluo-stat6250): Yes, it can read both.
- Question (yyan11−stat6250): What is the list input?
- Answer (yyan11−stat6250): List input is a powerful tool for reading both standard and nonstandard free-format data.
- Question (aoneill2−stat6250): When listing variables in an input statement, why is it merely sufficient to use a $ sign to read in a character field without specifying a minimum-width or maximum-width field?
- Answer (aoneill2−stat6250): The SAS system reads a default of 8 characters for a given field. The rest of the field before the delimiter is ignored and truncated.
- Question (mcardoso3-stat6250):  What is the use for the list input style?
- Answer (mcardoso3-stat6250):  The List input is used to read both standard and nonstandard free-format data.
- Question (yzhu12-stat6250): What can you do if your data contains missing values at the end of a record to prevent SAS from reading the next record to find the missing values?
- Answer (yzhu12-stat6250): You can use the INFILE statement with the MISSOVER option.



[Course Textbook Chapter 17, Problem 4] 
* *Question (aalshehry−stat6250):* Can list INPUT skip or re-read fields?
- Answer (mcardoso3-stat6250):  No, you cannont skip or re-read fields under list input because it does not specify column locations.
- Question (dlee117−stat6250): When using List Input, do you have to read all of the data or can you use it to only read certain columns? 
- Answer (aoneill2−stat6250): No, all fields must be read in order until the end of record marker is reached, indicating the beginning of the next record group.
- Question (akumar30−stat6250): Can we change the order of columns in free-format raw data using input statement?
- Answer (aoneill2−stat6250): No, all fields must be read in order because there is no way to anticipate where the next record begins, so column references such as pointers cannot be used.
- Question (rluo-stat6250): What is the rule of using list input?
- Answer (aoneill2−stat6250): List input must be read in order and relies upon delimiters. Also, it must not contain embedded spaces.
- Question (yyan11−stat6250): How to output with missing data records?
- Answer (yyan11−stat6250): You can use the Delimiter Sensitive Data (DSD) option in the INFILE statement to correctly read the raw data. The DSD option changes how SAS treats delimiters when list input is used.
- Question (aoneill2−stat6250): Are variable field values read into the data vector incorrectly if column values are specified but it is in free form?
- Answer (aoneill2−stat6250): Yes, it is parsed strictly according the specified columns.
- Question (mcardoso3-stat6250):  Is inputting the length of the variable name always necessary to include?
- Question (yzhu12-stat6250): What's the main differences between DSD option and DLM= option in the INFILE statement?
- Answer (mcardoso3-stat6250):  Though DSD and DLM=option can read fields that are delimited by blanks, you can also use DSD to read raw data.



[Course Textbook Chapter 17, Problem 5] 
* *Question (aalshehry−stat6250):* When to use DLM= option in the INFILE statement?
- Answer (aoneill2−stat6250): A DLM= (delimiter) option is necessary when any delimiter other than a blank space is used, and is also useful when encountering missing data, as a missing value is recorded when no record is found between two delimiters.
- Question (dlee117−stat6250): When trying to specify a delimiter, what happens when that delimiter is also a character that occurs in a data value?
- Answer (aoneill2−stat6250): It is still treated as a delimiter, even within quoted strings.
- Question (akumar30−stat6250): Can we processed one raw data using input statement which are separated by different delimiters?
- Answer (aoneill2−stat6250): Yes, you would use the DLM= option along with the DSD optoin in the INFILE statement.
- Question (rluo-stat6250): What is the limitations of list input?
- Answer (mcardoso3-stat6250):   Aside from not being able to skip or re-read fields, all fields in a list input must be separated by at least one blank or other delimeter and fields must be read in order from left to right.
- Question (yyan11−stat6250): How to output using sequential variable names?
- Answer (yyan11−stat6250): You can also specify a range of variables using formatted input. If you specify a range of variables using formatted input, both the variable list and the informat must be enclosed in parentheses, regardless of the variable's type.
- Question (aoneill2−stat6250): Can the delimiter be declared merely in single quotes as an option?
- Question (aoneill2−stat6250): No, it needs to be enclosed in single quotes after dlm= or delimiter=.
- Question (mcardoso3-stat6250):  Are there any options other than a delimeter option used for an INFILE statement?
- Question (yzhu12-stat6250): Under what condition does the DSD option be used to read raw data when there is a missing value at the beginning of a record?
- Answer (yzhu12-stat6250): As long as a delimiter precedes the first value in the record. 



[Course Textbook Chapter 17, Problem 7] 
* *Question (aalshehry−stat6250):* Does the order of the variables matter when using the LENGTH statement?
- Answer (aoneill2−stat6250): No, the LENGTH statement is just a variable declaration, not part of the input statement itself. It must appear before the INPUT statement so that it is the first time the data step encounters the variable.
- Question (dlee117−stat6250): When do you need to enclose your variable list and $ symbol in parentheses when specifying a range of variables?
- Answer (aoneill2−stat6250): I think you need to enclose your variable list in parentheses when referring to an array or as arguments for a macro.
- Question (akumar30−stat6250):  What is the default length of character variable in input sttatemnet?
- Answer (akumar30−stat6250): Character Variable has default length of 8.
- Question (rluo-stat6250): What is the function of the MISSOVER option?
- Answer (aoneill2−stat6250): The MISSOVER option allows the list data to be read in with missing values, but only those that occur at the end of a record.
- Question (yyan11−stat6250): How to use the LENGTH statement with the INPUT statement?
- Answer (yyan11−stat6250): The LENGTH statement extends the length of the character variable. The LENGTH statement should precede the INPUT statement so that the correct length is defined.
- Question (aoneill2−stat6250): Can input data that is in free form be read out of order?
- Answer (aoneill2−stat6250): No. This is what makes free form data less flexible than column data. This is because the next field begins following wherever the delimiter is, and it could be anywhere before the end of record.
- Question (mcardoso3-stat6250):  Where would be the proper place to type the length variable in a SAS statement?
- Question (yzhu12-stat6250): How does the informats work differently in modified list input compared to that they do in formatted input?
- Answer (mcardoso3-stat6250):  Unlike in modified list input, with formatted input, the informat determines both the length of character variables and the number of columns that are read.



[Course Textbook Chapter 17, Problem 8] 
* *Question (aalshehry−stat6250):* What does modified list input used for?
- Answer (aoneill2−stat6250): Modified list input takes advantage of known record characteristics, such as whether given fields start in a specified column or appear in a given range of columns, and otherwise takes advantage of the free form for other data fields of  unspecified or unknown length.
- Question (dlee117−stat6250): What should you do if there are missing values that occur at the end of a record?
- Answer (aoneill2−stat6250): Use the MISSOVER option.
- Question (akumar30−stat6250): Can we change the default value of dsd from comma ‘,’ to semicolon ‘;’?
- Answer (akumar30−stat6250): Yes, using dlm=option, we can change the default value to any acceptable delimiter.
- Question (rluo-stat6250): What is the function of the LENGTH statement?
- Answer (aoneill2−stat6250): The length statement circumvents truncation of variables to the default 8 characters or numberical digits.
- Question (yyan11−stat6250): How to use modify list input?
- Answer (yyan11−stat6250): There are two modifiers that can be used with list input.The ampersand (&) modifier is used to read character values that contain embedded blanks. The colon (:) modifier is used to read nonstandard data values and character values that are longer than eight characters, but which contain no embedded blanks.
- Question (aoneill2−stat6250): When you specify the length of a character variable, when do you have to repeat the use of the $ sign in declaring the variable in the input statement and when do you not need to?
- Answer (aoneill2−stat6250): You do not need to repeat the character type specification in the input statement because the length statement functions in lieu of the declaration in the input statement.
- Question (mcardoso3-stat6250):  Is there a best type of input to use to read a raw data file, or does it depend on the data set?
- Question (yzhu12-stat6250): How to create a delimited raw data file?
- Answer (yzhu12-stat6250): You can use the DLM= option with a FILE statement to create a delimited raw data file.



[Course Textbook Chapter 17, Problem 10] 
* *Question (aalshehry−stat6250):* when do we use mixed input style?
- Answer (aoneill2−stat6250): We used mixed input style when we know the variable types so they can be specified. This is especially useful when mixing standard and nonstandard values in fixed fields.
- Question (dlee117−stat6250): What does the & symbol do when reading raw data values?
- Answer (aoneill2−stat6250): The & directs SAS to ignore one embedded blank in reading a field. It appears after the variable name and before the informat.
- Question (akumar30−stat6250): Can we use dynamic length based on max length of each variable in raw data file?
- Answer (aoneill2−stat6250): Yes. If you do not want to let it default to the 8 character or numerical digit maximum, then you must specify the length in a length statement prior to the input statement in the data step.
- Question (rluo-stat6250): How to create a free-format dataset?
- Answer (aoneill2−stat6250): You can use the put statement. The default is to leave a space after printing each variable's value.
- Question (yyan11−stat6250): Can the modified list input be used to read values that contain embedded blank and nonstandard values?
- Answer (yyan11−stat6250): Yes, modified list input can be used to read values that contain embedded blanks and nonstandard values.
- Question (aoneill2−stat6250): Does the length of a variable field have to be declared in a separate length statement when the & sign is used to indicate embedded blank spaces in the input statement?
- Question (mcardoso3-stat6250):  Is there more than one way to correctly input a SAS statement to include the same output (i.e. without @ + & signs)?
- Question (yzhu12- stat6250): When do you need to specify the variable type again when you use the LENGTH statement?



[basic_recipe_to_load_remote_delimited_file (from Week 10 Overview)]
* *Question (aalshehry−stat6250):* Is there another effieciant way to determine the longest width for each variable rather than set the width to 100 for all columns?
- Answer (aoneill2−stat6250): Yes, you can use the guessingcolumns= option, and set it to the number of rows of data you'd like it to check before it determines the maximum field size.
- Question (dlee117−stat6250): Are there other file types besides .csv that use delimiters besides commas?
- Answer (aoneill2−stat6250): Actually .csv IS a comma-delimited file.
- Question (akumar30−stat6250): How proc import identifies the variable name and its data type from external file?
- Answer (akumar30−stat6250): When PROC IMPORT used to read a CSV, tab, or other character-delimited file, the procedure does the following to identifies variable name and its data type
   - scans the first 20 records
   - collects the variable names from the first row
   - scans the remaining 19 rows and determines the variable types
   - assigns an informat and a format to each variable
   - creates an INPUT statement
   - submits all of the code to the DATA step compiler, which, in turn, executes the code
- Question (rluo-stat6250): How can we import delimited text file?
- Answer (aoneill2−stat6250): You can declare the delimiter in a dlm= option.
- Question (yyan11−stat6250): Why the errors will occur, if the first few values in a column are numeric and a numerie informat is assumed?
- Question (aoneill2−stat6250): When specifying the dbms engine, is the delimiter implied, or is an error generated if the delimiter option left out?
- Answer (aoneill2−stat6250): The dbms engine infers a default delimiter, but to be clear the delimiter can be specified.
- Question (aoneill2−stat6250): Since the getnames option in the import statement seems to detect and create informants for individual variables, and in conjunction with the guessingrows option, can truncation be avoided of character fields longer than 8 characters?
- Question (mcardoso3-stat6250):  When would PROC IMPORT not be enough to import simple, small files into SAS?
- Question (yzhu12-stat6250): The proc import can be hit or miss with delimited text files, then how can we prove the programming performance?
- Answer (mcardoso3-stat6250):  The programming performance can be proved either by the delimited text files being imported in Excel and saved as an excel data file, or to have a custom data step written to import them.



[adv_recipe_to_load_remote_delimited_file (from Week 10 Overview)]
* *Question (aalshehry−stat6250):* Who to deal with TAB as delimitor in INFILE statement?
- Answer (aoneill2−stat6250): On an ASCII platform, you can use the dlm='09'x option for the hexadecimal representation for tab.
- Question (dlee117−stat6250): What is the purpose of using the firstobs option and is it necessary?
- Answer (aoneill2−stat6250): Firstobs tells SAS where to start listing your specified number of observations. The default is firstobs=1.
- Question (akumar30−stat6250): What is the maximum file size limit of tempfile in SAS to load data directly from webpage?
- Question (rluo-stat6250): What is the function of the INFORMAT statement?
- Answer (aoneill2−stat6250): The INFORMAT statement is important to deal with nonstandard character and numeric data. Otherwise the default of as numerical field of 8 digits is assumed.
- Question (yyan11−stat6250): Why the informat statement seta each column type to character-values vith width 100?
- Answer (yyan11−stat6250): It' a common convention to use when using disk space usage is less inportant than the time it could take to carefully determine an optimal maximum length or value type for each column.
- Question (aoneill2−stat6250): If lrecl option is to specify the maximum possible line length, what its default value?
- Answer (mcardoso3-stat6250):  The default value of the maximum possible line length is 256.
- Question (mcardoso3-stat6250):  What is the most essential command to enter for an INILE statement? 
- Question (yzhu12-stat6250): We can convert columns to numeric using recipe of drop and swap, what recipe can we use if we want to convert columns to category?



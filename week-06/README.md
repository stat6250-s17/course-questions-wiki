## Week 6 Quiz Questions and Answers

In order to prepare your Week 6 Quiz submission, please edit ***this*** document to provide substantive questions for each Quiz Problem and SAS Recipe listed below, as well as answers to at least three questions raised.

All edits should conform to GitHub Markdown specifications (https://guides.github.com/features/mastering-markdown/) and should be committed to a branch named "week-6" in your fork of this repo. Then, after all edits have been made/committed, your Week 6 Quiz should be submitted by initiating a pull request using

- the master branch of the stat6250/course_questions_wiki repo as the base fork and

- the week-6 branch of your version of the repo as the head fork.

The instructor will then review the pull request and make comments should further revision be needed. Then, after the contents of the pull request have been finalized without any merge conflicts, the instructor will merge the pull request.

********************************************************************************



[Course Textbook Chapter 12, Problem 1]
- Question (cyuan10-stat6250): Can you merge together two table sets with different number of records? 
- Answer (cyuan10-stat6250): Yes, in one-to-one merging for example will simply take the first observation from one table and merge with the first observation from the second table and so on - they do not have to be of equal number of observations.
* *Question (aalshehry−stat6250):* What is the right way to concatenate two datasets in a new one?
* *Answer (aalshehry−stat6250):* By using the following syntax: 
```SAS
DATA SAS-data-set;
       SET SAS-data-set1 SAS-data-set2 ...;
RUN;
```
- Question (akumar30−stat6250): Is the order of the smallest dataset significance in one-to-one merge SET data statement? 
- Question (yzhu12-stat6250): Why there is no end-of-file condition when you use direct access?
- Question (meisenbach-stat6250): When would you use this one-to-one merging?
- Answer (meisenbach-stat6250): When the observations in both datasets are in the same order and the columns are different.
- Question (lzhao4-stat6250): How does SAS reading values when same named variables occur?
- Question (kveng-stat6250): What are the methods of combining data set?
- Answer (kveng-stat6250): There are one-to-one reading (statement: SET), concatenating (statement: SET), interleaving (statement: SET, BY), and match-merging (statement: MERGE, BY)
- *Question* (lwang30-stat6250): What would the new dataset be if the variable "VarZ" in the second dataset changes to "VarY" ?
- *Answer* (lwang30-stat6250): SAS would recognize a common variable "VarY" between two datasets and overwrites the observation from the first dataset by the values from the second dataset, so only two columns would be present in the new dataset. 
- Question (mcardoso3-stat6250):  How often is match-merging used in SAS?
* Question (aalamri−stat6250): Which statement can help us combine two or more datasets into one dataset?
* Answer(aalamri−stat6250):  We can do that by using the “SET” statement and follow it with each dataset.
- Question (dlee117−stat6250): What are the five methods of combining observations from two or more data sets into a new data set?
- Answer (dlee117-stat6250): They are one-to-one reading, concatenating, appending, interleaving, and match-merging.
- Question (nly13-stat6250): If the 2 data sets have unequal number of rows, what will happen during the merge?
- Answer (nly13-stat6250): In the last row of observations, the SET statement will read in the observation in the first set, but will stop when there is nothing to read in from the second set. This observation will not be in the output.
- Question (rluo-stat6250): Is there any requirements for the datasets to perform One-to-One merging?
- Question (aoneill2-stat6250): For a one-to-one match, how many set statements are needed?
- Answer (aoneill2-stat6250): A one-to-one match requires two set statements to input the two files.
- Question (yyan11−stat6250): How One-to-One Merging Selects Data?
- Answer (yyan11−stat6250): When you perform one-to-one merging, the new data set contains all the variables from all the input data sets. If the data sets contain variables that have the same names, the values that are read from the last data set overwrite the values that were read from earlier data sets.




[Course Textbook Chapter 12, Problem 2]
- Question (cyuan10-stat6250): Can you move two tables based on an unique identifier vs. based on order of observation?
- Answer (cyuan10-stat6250): Yes, you can still do this with one-to-one merging. You can sort both variables based on the single unique identifier and then merge the two.
* *Question (aalshehry−stat6250):* What is the main difference between using SET and Merge statements in DATA step?
- Question (akumar30−stat6250): How to append two dataset, when common variable has different type of data?
- Answer (akumar30−stat6250):  If the type of a variable in the DATA= data set is different than in the BASE= data set, SAS replaces all values for the variable in the DATA= data set with missing values and keeps the variable type of the variable specified in the BASE= data set
- Question (yzhu12-stat6250): What steps you must take to prevent continuous looping while using direct access to read data?
- Answer (yzhu12-stat6250): You either add a STOP statement to the DATA step, or use programming logic that checks for an invalid value of the POINT= variable.
- Question (meisenbach-stat6250): What is the benefit of using interleaving?
- Answer (meisenbach-stat6250): The output dataset is sorted by the BY variable.
- Question (lzhao4−stat6250): How to use BY statement and SET statement when interleave data sets?
- Question (kveng-stat6250): Can we use interleaving without changing the order?
- Answer (kveng-stat6250):  If we don't want to change the order, then we need to use concatenating method. It'll just concate multiple tables without sorting.
- *Question* (lwang30-stat6250): How many observations would be in the new dataset if the code from answer "D" is used ?
- Question (mcardoso3-stat6250):  Can data sets be merged into more than one combined data set?
* Question (aalamri−stat6250):  How does SAS deal with interleaving datasets in order to combine them? 
* Answer(aalamri−stat6250): SAS makes a list of dataset names in the “SET” statement and one or more “BY” variables in the “BY” statement.
- Question (dlee117−stat6250): What is the difference between the interleaving and match-merging methods?
- Question (nly13-stat6250): How does the BY statement affect a one to one merge?
– Answer (nly13-stat6250): The BY statement will sort the order of the merged data set by the specified variable.
- Question (rluo-stat6250): What data will be selected when performing concatenating?
- Answer (rluo-stat6250): All of the observations from the first data and all of the observations from the second data will be selected.
- Question (aoneill2-stat6250): How many set statements are used to append one file with another?
- Answer (aoneill2-stat6250): Only one set statement is required, followed by the two file names.
- Question (yyan11−stat6250): How Interleaving Selects Data?
- Answer (yyan11−stat6250): When SAS interleaves data sets, observations in each BY group in each data set in the SET statement are read sequentially, in the order in which the data sets and BY variables are listed, until all observations have been processed. The new data set includes all the variables from all the input data sets, and it contains the total number of observations from all input data sets.




[Course Textbook Chapter 12, Problem 3]
- Question (cyuan10-stat6250): What does concatenate do and how is it different from one-to-one merging?
- Answer (cyuan10-stat6250): Concatenate is another way of merging data tables. However, records of the 2nd table is appended or added on to the first table. So if you have 6 records in the 1st and 6 in the 2nd, you will end up with 12 total records in the concatenate table.
* *Question (aalshehry−stat6250):* What is the default oreder of the output obsevations when SET statement is used to combine two datasets?
- Question (akumar30−stat6250): What happen when if the type of common variable differ in the datasets to be concatenated?
- Answer (akumar30−stat6250):  SAS will stops process the DATA step and issues an error message stating that the variables are incompatible.
- Question (yzhu12-stat6250): How do we determine when the last observation in an input data set has been read?
- Answer (yzhu12-stat6250): We use the END= option in the SET statement.
- Question (meisenbach-stat6250): With concatenate, what happens when rows have the same values for a particular variable (e.g. ID)?
- Answer (meisenbach-stat6250): Nothing, both rows are in the output.
- Question (lzhao4−stat6250): How will the output data set display when concatenate one date set to another?
- Question (kveng-stat6250): Which method does this problem invoke?
- Answer (kveng-stat6250): This problem invokes the concatenating method.
- *Question* (lwang30-stat6250): Can we use a "merge" statement for these two datasets directly ?
- *Answer* (lwang30-stat6250): No, we can't, as the "merge" statement requires the two datasets to have at least one common variable. Rename of one of the variables should be done prior to using the "merge" statement for these two datasets.
- Question (mcardoso3-stat6250):  What happens if the two data sets being merged don't have any columns in common?
- Answer (mcardoso3-stat6250):  The datasets would be merged with any unspecified values marked as missing.  Though the values aren't necessarily merged together, there will be one merged dataset.
* Question (aalamri−stat6250): What is the “END” option use for?
- Question (dlee117−stat6250): What is the difference in the coding between one-to-one matching and concatenating?
- Answer (dlee117-stat6250): With one-to-one matching, you use individual SET statements per data set while with concatenating, you have multiple data sets in one SET statement separated by commas.
- Question (nly13-stat6250): During concatenate, what will happen if the variable names are not the same?
- Answer (nly13-stat6250): If the variable names are not the same, it will generate a new column for each dataset.
- Question (rluo-stat6250): What is the difference between appending and the concatenating?
- Answer (rluo-stat6250): Concatenating will create a completely new dataset while appending just simply add one to another.
- Question (aoneill2-stat6250): If two files each have different variables, can they be appended?
- Answer (aoneill2-stat6250): Yes. The resulting output file will contain columns that reflect the variables in both input files.
- Question (yyan11−stat6250): How Concatenating Selects Data?
- Answer (yyan11−stat6250): When a program concatenates data sets, all of the observations are read from the first data set listed in the SET statement. Then all of the observations are read from the second data set listed, and so on, until all of the listed data sets have been read. The new data set contains all of the variables and observations from all of the input data sets.




[Course Textbook Chapter 12, Problem 4]
- Question (cyuan10-stat6250): What is the benefit of using interleaving data step and when do you gain an advantage when using it?
* *Question (aalshehry−stat6250):* Before concatenate datasets, what should we pay attention to?
* *Answer (aalshehry−stat6250):*  It is important to know the structure and contents of the input datasets by checking the describtive part and the data as well.
- Question (akumar30−stat6250):  Can we concatenate more than two data set in SAS using single SAS concatenate procedure?
- Question (yzhu12-stat6250): How do you select the variables that you want to drop or keep?
- Answer (yzhu12-stat6250): You can use the DROP= and KEEP= data set options in parentheses after a SAS data set name.
- Question (meisenbach-stat6250): When should you use concatenate?
- Answer (meisenbach-stat6250): When both datasets essentially have the same columns and the missing columns are non-essential.
- Question (lzhao4−stat6250): What’s the difference between concatenate multiple data sets and merge multiple data sets?
- Question (kveng-stat6250): Is concatenating the best method to use in this case?
- *Question* (lwang30-stat6250): What is the difference between an interleaving case and a concatenating case ?
- *Answer* (lwang30-stat6250): In an interleaving case, the observations are read sequentially in each BY group. In a concatenating case, the observations are read sequentially according to their orders in the SET statement.
- Question (mcardoso3-stat6250):  What is the difference between concatenating, appending, and interleaving?
- Answer (mcardoso3-stat6250):  Concatenating appends the observations from one data set to another, while appending adds the observations in thesecond data set, and interleaving intersperses observations from two or more data sets.
* Question (aalamri−stat6250):  When inputting datasets in SAS, how important is the order of these datasets when combining them?
* Answer (aalamri−stat6250):   very important because SAS reads datasets based on the closest ones to the “SET” statement so it may affect the outcome.
- Question (dlee117−stat6250): When can you not concatenate multiple data sets?
- Answer (dlee117-stat6250): Any common variable must have the same type attribute.
- Question (nly13-stat6250): If merging datasets with unequal observations, is there a benefit to not having the missing observations?
- Question (rluo-stat6250): What statement is used to perform interleaving?
- Answer (rluo-stat6250): The BY statement is used when performing interleaving.
- Question (aoneill2-stat6250): How does a variable end up "missing" in concatenating files?
- Question (yyan11−stat6250): How to read the concatenated data sets?
- Answer (yyan11−stat6250):  The concatenated data sets are read sequentially, in the order in which they are listed in the SET statement. 




[Course Textbook Chapter 12, Problem 5]
- Question (cyuan10-stat6250): What is the difference with Match-merging vs. using one-to-one merge with sort? And how is missing values dealt with?
* *Question (aalshehry−stat6250):* What is the best way to combine multiple datasets which have a primar-key variable?
- Question (akumar30−stat6250): Can we merge the two datasets with multiple common variables in single SAS Procedure by specifying multiple variable names in BY statement?
- Question (yzhu12-stat6250): When we read a single data set, which command do we use to specify the data set to be read?
- Answer (yzhu12-stat6250): We use SET statement.
- Question (meisenbach-stat6250): When two datasets have the same variable, how is the length of the variable determined?
- Answer (meisenbach-stat6250): The length is determined by the first dataset.
- Question (lzhao4−stat6250): How will the output data set display when couple variables with the same name are in more than one input data set?
- Answer (lzhao4-stat6250): Values of the same-named variable in the first data set in which it appears are overwritten by values of the same-named variable in subsequent data sets.
- Question (kveng-stat6250): When merging two tables with the same column label, can we specify which table to overwrite?
- *Question* (lwang30-stat6250): In a "merge" statement, what is the effect on the output dataset if the same-named variable from two datasets have different types ?
- Question (mcardoso3-stat6250):  Why must the overlapping variable values be set to missing when they are merged?
- Answer (mcardoso3-stat6250):  If the values in the same column variable over two data sets are different, there is no way in telling which the proper values are.  Therefore, the values are set to missing.
* Question (aalamri−stat6250): How does SAS deal with datasets that have the same variable names?
- Question (dlee117−stat6250): If you want to merge more than one variable in descending order, how do you code this?
- Question (nly13-stat6250): Is it recommended to always use the RENAME statement in order to prevent overwriting a variable? 
- Question (rluo-stat6250): What statement will be used to perform Match-Merging?
- Question (aoneill2-stat6250): When two files are merged with different values of a variable by the same name in each, which value gets overwritten, the first input file or the second?
- Answer (aoneill2-stat6250): The first input file's variable value is overwritten by the second.
- Question (yyan11−stat6250): What happen if have the same name variables in more than one input data set?
- Answer (yyan11−stat6250): If you have variables with the same name in more than one input data set, values of the same-named variable in the first data set in which it appears are overwritten by values of the same-named variable in subsequent data sets. 



[Course Textbook Chapter 12, Problem 7]
- Question (cyuan10-stat6250): Can you use match-merging on two different variables for matching? For example, if variable 1 matches, check variable 2 before merging?
* *Question (aalshehry−stat6250):* In MERGE statement, what the possible values for IN option? and how it can be utilized?
* *Answer (aalshehry−stat6250):*  The IN= variables have two possible values: 0 and 1 which indicates whether a data set contributed information to the observation: MERGE SAS-data-set1 <(IN=variable)>...
- Question (akumar30−stat6250): How do you prevent the values of the common variable Blue from being overwritten when you merge the two data sets?
- Answer (akumar30−stat6250):  Using RENAME procedure, we can change the name of common variables to sustain its original value from both dataset and prevent overwriting,
- Question (yzhu12-stat6250): What's the other programming features for manipulation data sets that the DATA step can provide?
- Answer (yzhu12-stat6250): We can use IF-THEN/ELSE logic with DO groups and DO loops to control processing that is based on one or more conditions, specify additional data set options, process variables in arrays and use SAS functions.
- Question (meisenbach-stat6250): When two datasets have the same variable, how do you keep just the values from the first dataset?
- Question (lzhao4−stat6250): How to prevent overwriting when merging variables which have same names. 
- Answer (lzhao4−stat6250): Can use RENAME= option to rename data set. 
- Question (kveng-stat6250): Can we change the column name with concatening and interleaving and match-merging method?
- *Question* (lwang30-stat6250): In what cases do you want to rename a variable so that the two datasets would have a common variable to be combined ? 
- Question (mcardoso3-stat6250):  Would there be another reason to rename a variable other than to avoid overwriting the values?
* Question (aalamri−stat6250): How can you prevent SAS form overwriting variables? 
- Question (dlee117−stat6250): If you merge two data sets and two values for a variable are the same, the DATA step overwrites the values of the like-named variable in the first data set; is this overwrite permanent?
- Question (nly13-stat6250): In what order to do rename statement activate in different parts of the data step?
- Question (rluo-stat6250): What statement can be used to prevent overwriting?
- Question (aoneill2-stat6250): How do you prevent a variable value from being overwritten in a merge, when merging two files with different values of the same variable keyed to the same unique identifier?
- Answer (aoneill2-stat6250): Use the RENAME option in renaming the variables in one or both files to distinguish them. Differences in variable values may reflect different situational meaning, and the RENAME feature could add further detail as well as prevent overwriting the value.
- Question (yyan11−stat6250): How to prevent the values from being overwritten when you merge the two data sets?
- Answer (yyan11−stat6250): To prevent overwriting, you can rename variables by using the RENAME= data set option in the MERGE statement.



[Course Textbook Chapter 12, Problem 9]
- Question (cyuan10-stat6250): How are duplicative records handled? Is this something that will be called out in any way during the table merge step or compilation step?



[basic_recipe_for_combining_data_horizontally (from Week 6 Overview)]
- Question (cyuan10-stat6250): What are some of the best practices when it comes to renaming columns in newly merged datasets? Does it help to add a specific identifier to these columns so that we know which ones are merged?
* *Question (aalshehry−stat6250):* What will happen if two datasets were combined with the same variable name but with different type?
- Question (akumar30−stat6250): Can I get the result of one-to-one merge using PROC SQL command?
- Question (yzhu12-stat6250): What's the BY statement in SAS for?
- Question (meisenbach-stat6250): In a match-merge, how do you exclude records with missing values?
- Answer (meisenbach-stat6250): use the IN= data set option and an IF statement.
- Question (lzhao4−stat6250): How will the output data set display when merging multiple data sets without make any change of BY variable value retain the same? 
- Answer (lzhao4-stat6250): The value will retain from the previous observation to new data set. 
- Question (kveng-stat6250): Can we merge two columns together like first name and last name instead of merging the tables?
- *Question* (lwang30-stat6250): How do you let SAS not output the observations that contain missing values ?
- Question (mcardoso3-stat6250):  Is there a limit to how many rows or columns a combined data set would have?
* Question (aalamri−stat6250): When combining multiple datasets, how does the "MERGE" statement work? 
- Question (dlee117−stat6250): When using a BY statement, can you specify any of the variables/more than one variable?
- Question (nly13-stat6250): Is it more efficient to use PROC SQL or DATA step to merge?
- Question (rluo-stat6250): What will happen to the observations when their corresponding variables are dropped?
- Question (aoneill2-stat6250): If one file has 5 records matched to a "by" variable as a unique identifier, and a second file has 3 records, with 2 "by" variables matching the first file's records and 1 different, how many records are in the match-merged file?
- Answer (aoneill2-stat6250): There will be 6 records altogether, containing the available values from the other variable or variables from each of the files.
- Question (yyan11−stat6250): How Match-Merging Selects Data?
- Answer (yyan11−stat6250): Generally speaking, during match-merging, SAS sequentially checks each observation of each data set to see whether the BY values match, and then writes the combined observation to the new data set.



[basic_recipe_for_combining_data_horizontally (from Week 6 Overview)]
* *Question (aalshehry−stat6250):* Using Program Data Vector (PDV) has many advantages, but what are its disadvantages?
- Question (akumar30−stat6250):  Does rename option in merge statement modify the name of actual dataset or only valid for merge statement?
- Question (yzhu12-stat6250): For example, if we have a data set containing missing variables, how does the SAS combine the data sets horizontally and correctly, which means that the corresponding variables are sorted  and then combined horizontally?
- Question (meisenbach-stat6250): Why does the column name not also change when we use rename? Why does renaming the column name to a space result in the desired column name?
- Question (lzhao4−stat6250): When labels are assigned in the data set, are they available for all procedures use in that data set?
- Question (kveng-stat6250): Can we just merge without including retain and keep and label statements? 
- *Question* (lwang30-stat6250): Is it necessary to put the "retain" and "keep" statament in the beginning or they could be anywhere in the data step ? 
- Question (mcardoso3-stat6250):  How many different SAS statements can be used for combining datasets?
* Question (aalamri−stat6250): Does SAS allow combining two datasets horizontally when one variable is missing its correspondent value from the other dataset? 
- Question (dlee117−stat6250): What is the goal of using a RETAIN statement when merging data sets?
- Question (nly13-stat6250): Besides not being limited my size, are there any other advantages to using merge instead of sql?
- Question (rluo-stat6250): If there are some observations that are completely the same, how do combining treat those two data? Will the combining just keep one of them or keep all of them?
- Question (aoneill2-stat6250): How do you prevent a variable value from being overwritten in a merge, when merging two files with different values of the same variable keyed to the same unique identifier?
- Answer (aoneill2-stat6250): Use the RENAME option in renaming the variables in one or both files to distinguish them. Differences in variable values may reflect different situational meaning, and the RENAME feature could add further detail as well as prevent overwriting the value.
- Question (aoneill2-stat6250): Does one have to use the label statement or is it optional?
- Question (yyan11−stat6250): What happen if two datasets have the same name column?



[optional: adv_recipe_for_combining_data_horizontally (from Week 6 Overview)]
- Question (akumar30−stat6250): Wwhich statement will have faster performance combine four dataset, using merge statement or proc sql statement?
- Question (yzhu12-stat6250): What kind of error will occur if the order of these AS statements are converted improperly?
- Question (kveng-stat6250): What is coalesce? What does it do?
- *Question* (lwang30-stat6250): What are the proc steps that experienced SAS users frequently apply sql to perform the task ? 
- Question (mcardoso3-stat6250):  Can a STAT programmer combine SAS datasets without PROC SQL?
- Answer (mcardoso3-stat6250): Though it requires less code and is useful in other ways, combining datasets can be used in alternative ways.
* Question (aalamri−stat6250): What can you use the "AS" statement for?


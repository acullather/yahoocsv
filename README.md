# yahoocsv
# CS 2410
## Yahoo Finance CSV Project
Due before: Wednesday, April 17th – 11:30 p.m.

## Instructions:

Write a C++ program that will input data from a Comma-separated values (.csv) file and output some information about it.  The program will work with .csv files that were downloaded from Yahoo Finance. Comma-separated values files are one file type that can be opened by Microsoft Excel.

This program must compile and run successfully on either Visual Studio 2015 or 2017.   Any C++ program that does not compile and run successfully on either version will receive a grade of 0.  This is because the computers in the classroom use these versions.  The program must be written in C or C++.  For every day a project is turned in late, 25 points will be deducted. 5 points are deducted for each resubmission.  If you submit multiple solutions, the only solution that will be graded is the last one.  The grade will include a late penalty if the last one was submitted past the due date but the first one wasn’t.
For this project, you can work in groups of up to 2 people (total).  All people in a group must be registered in this section of CS 2410.  Comment out the name(s) of everyone who worked on this project at the top of your main .cpp file. Everyone in the group will receive the same grade. Because of this, each group member will need to turn in the exact same files.  Everyone will need to turn in all files in order to receive credit.

Your program must fulfill the following requirements:

*	Store the contents of a .csv, Comma-separated Values file in a data structure(s)
https://en.wikipedia.org/wiki/Comma-separated_values	
The .csv file will be stored in the same folder as your main .cpp file.
*	Output the name of the ticker to the console screen (without the “.csv”)
*	Output the start date and end date that was found in the file
*	Output how many trading day(s) existed in the file
*	Prompt the use to input a number of records
*	Input the number of records from the console screen
*	Output the following heading to the console screen:
Date            Open    A.Close Percent Change
*	Output the top x records for that ticker within the provided date range.  Here x is the number of records that the user inputted previously.  The top record is the record (row) that had the greatest percent change when comparing the open price to the adjusted close price (from the same day).  The top records are the set of records that had the greatest percent changes amongst all records.  The percent change is defined as follows:
(adjusted close price – open price) / open price * 100
These records need to be displayed from highest percent change to lowest percent change.  The program only needs to display the following information from that row: date, open price, adjusted close prices, and the percent change (for that 1 day).
*	The program needs to run as it does in the executable (.exe) file that was uploaded to Blackboard.
*	The program needs to run correctly with any ticker and with any number of records.  
*	The program will let the user know if they entered a number of records that is too large.  It will continue to ask the user to input a number of records until they enter a number that is less than or equal to the number of trading day(s).

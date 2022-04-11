# Data-Science-I-Exer.-02-
Introduction to Data Science I (Exer. 02) Regex + Pandas Intro
1. Open the file "ca_sample_data_a.csv" in "read mode"
(Download the file from your omnivox account )
We need to read all the data from the file (file is in csv format and contains a header)
• We need to verify that the phone column is in the following format :
ddd-ddd-dddd (where d is a digit) (i.e. 514-321-0909)
• We need to verify that the email column is in the following format :
xxxxxxx@xxxxx.xxx (where x is an alphanumeric character)
Use REGEX (Regular expressions to check the records 
• All records found with a phone that does not follow the given format should be 
written to a file : bad_phone_recs.csv
• All records found with an email that does not follow the given format should be 
written to a file : bad_email_recs.csv
NOTE: Either a bad phone or bad email, not both. (that is how the data is 
prepared)
• All good records should be written to a file : good_recs.csv
 
2. Open the good_recs.csv file and load it into a Pandas DataFrame (let the index by default)
2.1 Show the first 5 records using .head()
2.2 Show the last 10 records using .tail()
2.3 Print the column names using a for loop and the .columns collection
2.4 Slice the DF and show records 1 to 5 (inclusive)
2.5 Show the record with index (5) (use .loc)
2.6 Using .loc, show first_name and last_name for record with index 1
2.7 Using .loc show first_name and last_name for records with index 1 and 5
2.8 Using .loc show the last_name for record with index 3
2.9 Try the method .describe with the dataframe and obtain stats on the exams
2.10 Using a boolean mask, show the students with an exam_1 mark of 75 or mor

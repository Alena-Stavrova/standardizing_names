# standardizing_names
This is my attempt to create a practical problem in SQL and a solution to it. I am using MySQL.

We have a simple table of student names and surnames. However, students registered themselves, and they entered their names randomly: some of them spelled it with all lowercase letters, others with all capitals, etc. We want to return the list of names and surnames where the first letter of each name and surname is capital while others are lowercase. 

Note: I am using a SELECT statement to return new columns. You can also tweak the code a bit to update the table, but for this update to work, you may need to disable the safe mode (e.g. in MySQL Workbench)

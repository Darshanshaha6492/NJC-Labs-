# NJC-Labs-


# Below is the Code from Command Prompt

Microsoft Windows [Version 10.0.19043.1288]

(c) Microsoft Corporation. All rights reserved.

C:\Users\eZee>sqlite3 darshan.db                  # Creating new Database
SQLite version 3.36.0 2021-06-18 18:36:39
Enter ".help" for usage hints.


sqlite> .databases                                # Checking for databases
main: C:\Users\eZee\darshan.db r/w


sqlite> CREATE TABLE Movies (                     #Creating Movies Table
   ...> MovieID int primary key,
   ...> MovieName varchar(50),
   ...> LeadActor varchar(50),
   ...> Actress varchar(50),
   ...> YearOfRelease date,
   ...> DirectorName varchar(50)
   ...> );
   
   
sqlite> insert into Movies values                                                                     #Inserting Values to Movies Table
   ...> (1, "Bhaagi3","Tiger Shroff","Disha Patani", 2020, "Ahmed Khan"),
   ...> (2, "War", "Hrithik Roshan", "Vaani Kapoor", 2019, "Siddharth Anand"),
   ...> (3, "Tanhaji", "Ajay Devgn", "Kajol", 2020, "Om Raut"),
   ...> (4, "Kabir Singh", "Shahid Kapoor", "Kiara Advani", 2019, "Sandeep Reddy Vanga"),
   ...> (5, "Chhichhore", "Sushant Singh Rajput", "Shraddha Kapoor", 2019, "Nitesh Tiwari");
   
   
sqlite> select * from movies;                                                 #Retriving Inserted Data
1|Bhaagi3|Tiger Shroff|Disha Patani|2020|Ahmed Khan
2|War|Hrithik Roshan|Vaani Kapoor|2019|Siddharth Anand
3|Tanhaji|Ajay Devgn|Kajol|2020|Om Raut
4|Kabir Singh|Shahid Kapoor|Kiara Advani|2019|Sandeep Reddy Vanga
5|Chhichhore|Sushant Singh Rajput|Shraddha Kapoor|2019|Nitesh Tiwari

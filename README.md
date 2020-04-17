## 17 april,2020
- Created a database using database module in moodle.The database activity module enables users to create, maintain and search a collection of entries (i.e. records).
- Added fields in database including field name,field type and its description.
- Collected information of students (e.g name,contact no.,email id,CRN,URN) in the form of google spreadsheets.
- Converted the .xsls file to .csv file.
- Imported the .csv file into database.

-----------------------------------------------------------------------------------------------------------------------------

## 16 april,2020
- Checking database of moodle in phpmyadmin.
- Trying to access database from moodle to fetch required information.

-----------------------------------------------------------------------------------------------------------------------------

## 14 april,2020
- I tried changing password of phpmyadmin and my moodle stopped working.
- I got this error "Error: Database connection failed It is possible that the database is overloaded or otherwise not running properly. The site administrator should also check that the database details have been correctly specified in config.php"
- I created new user and granted all priviliges to that user and then made changes in config.php file using command
  "sudo nano/var/www/html/moodle3/moodle/config.php".
    
----------------------------------------------------------------------------------------------------------------------------- 

## 23 march,2020
- Exploring modules which can provide form facilities- Application form,Dataform and Database activity modules.

----------------------------------------------------------------------------------------------------------------------------
## 20 march,2020
- Created Attendence activity in courses.
- Created session and marked attendance of enrolled students .

----------------------------------------------------------------------------------------------------------------------------
## 19 march,2020
- Created a quiz using plugin mod_quiz.This plugin enables a teacher to create quizzes comprising questions         including multiple choice, matching, short-answer and numerical.
- The teacher can allow the quiz to be attempted multiple times, with the questions shuffled or randomly selected from the     question bank. A time limit may be set.
- Enrolled students.

----------------------------------------------------------------------------------------------------------------------------

## 17 march,2020
- Created Cohorts, i.e categories of users in moodle.
- Created users and assigned them cohorts.
- Created courses in moodle.

----------------------------------------------------------------------------------------------------------------------------

## 4 march,2020
- After importing database,performed operations using functionalities provided in phpmyadmin.
- There is no inbuilt functionality for union operation ,so query will be used to perform union.

----------------------------------------------------------------------------------------------------------------------------

## 3 march,2020
- Using phpmyadmin.
- Importing and accessing sqlite database(survey.db) into phpmyadmin.
- Before importing survey.db file it will be converted to .sql file which is then coverted into a zip file.
- There are two ways of coverting survey.db file: 
  - Online using this link- https://www.rebasedata.com/convert-sqlite-to-mysql-online
  - on command line using command curl- Replace file with the path to the *.DB file to be converted.
   curl -F files[]=@file 'https://www.rebasedata.com/api/v1/convert?outputFormat=mysql&errorResponse=zip' -o output.zip

-----------------------------------------------------------------------------------------------------------------------------

## 2 march,2020
- Submitted the synopsis of project **Report Generation from Moodle**

- Created this github page with the help of this link
[https://guides.github.com/features/pages/]
 
-----------------------------------------------------------------------------------------------------------------------------

## 28 feb,2020
- SoftwareCarpentrySQL
- Accessing sqlite database using queries.

-----------------------------------------------------------------------------------------------------------------------------

## 27 feb,2020
- Prepared synopsis for project **Report generation from Moodle**
- Key points of the project are:
- INTRODUCTION
    - Moodle is designed to support both teaching and learning as it delivers a powerful set of learner- centric tools and collaborative learning environments that empowers both functionalities. 
    - It is an open-source platform, it can be customised in any way and tailored to individual needs. 
    - Its modular set up and interoperable design allows developers to create plugins and integrate external applications to achieve specific functionalities.
    
 - OBJECTIVES
   - To reduce admin work by integrating the details of the students of all the different departments into a single database. 
   - To save the time as manual work will be less and eliminate duplicate data entries.
    - To keep the parents informed about the student’s performance via Emails,alerts and generated reports.
    
  - Tools to be used
   
    - Moodle
    - Mysql

  - Technologies to be used

     - Javascript
    - HTML
    - PHP
    - CSS
    


-----------------------------------------------------------------------------------------------------------------------------


-----------------------------------------------------------------------------------------------------------------------------

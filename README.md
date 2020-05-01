## 27 april,2020
- Generating User's report.
- Creating SQL reports.
- Generating SQL queries to be used in SQL reports.

----------------------------------------------------------------------------------------------------------------------------

## 24 april,2020
-Roadmap of moodle[https://docs.moodle.org/dev/Roadmap]

----------------------------------------------------------------------------------------------------------------------------

## 22 april,2020
- Installed block plugin following these steps:
  -  Download the Configurable Reports installation file and unzip it to the \blocks directory in your Moodle folder.
  -  Be sure that the final name of the directory is: configurable_reports, the full path in your Moodle installation will        be blocks/configurable_reports
  -  Login to Moodle as Administrator and click Notifications under Site Administration.

----------------------------------------------------------------------------------------------------------------------------

## 20 april,2020
- Explored following links.
  - https://docs.moodle.org/38/en/Custom_SQL_queries_report.
  - https://docs.moodle.org/38/en/ad-hoc_contributed_reports.
  - https://moodle.org/mod/forum/discuss.php?d=153059.
  - https://docs.moodle.org/38/en/Configurable_reports.


----------------------------------------------------------------------------------------------------------------------------

## 18 april,2020
- RDBMS Concepts.
- Data Definition Language.
- Data Manipulation Language.
- Attempted Quizzes,Query exercises.

----------------------------------------------------------------------------------------------------------------------------

## 17 april,2020
- Created a database using database module in moodle.The database activity module enables users to create, maintain and search a collection of entries (i.e. records).
- Added fields in database including field name,field type and its description.
- Collected information of students (e.g name,contact no.,email id,CRN,URN) in the form of google spreadsheets.
- Converted the .xsls file to .csv file.
- Imported the .csv file into database.

----------------------------------------------------------------------------------------------------------------------------

## 16 april,2020
- Checking database of moodle in phpmyadmin.
- Trying to access database from moodle to fetch required information.

----------------------------------------------------------------------------------------------------------------------------

## 14 april,2020
- I tried changing password of phpmyadmin and my moodle stopped working.
- I got this error "Error: Database connection failed It is possible that the database is overloaded or otherwise not running properly. The site administrator should also check that the database details have been correctly specified in config.php"
- I created new user and granted all priviliges to that user and then made changes in config.php file using command
  "sudo nano/var/www/html/moodle3/moodle/config.php".
  
---------------------------------------------------------------------------------------------------------------------------- 

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
  - Online using this link- [https://www.rebasedata.com/convert-sqlite-to-mysql-online]
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

----------------------------------------------------------------------------------------------------------------------------

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
    


----------------------------------------------------------------------------------------------------------------------------

## 19 feb,2020

- Attendance plugin installation
- Installing manually at the server:
  - Go to the Moodle plugins directory; select your current Moodle version, then choose a plugin with a Download button and       download the ZIP file.
  - Upload or copy it to your Moodle server.
  - Unzip it in the right place for the plugin type.
  - In your Moodle site (as admin) go to Site administration > Notifications (for most plugin types, admin will recieve a       message saying the plugin is installed).

----------------------------------------------------------------------------------------------------------------------------

## 12 feb,2020
Installation of moodle
- Step 1: Install Ubuntu sudo apt-get install vim
- Step 2: Install Apache/MySQL/PHP sudo apt install apache2 mysql-client mysql-server php libapache2-mod-php
- Step 3: Install Additional Software sudo apt install graphviz aspell ghostscript clamav php7.2-pspell php7.2-curl php7.2-   gd php7.2-intl php7.2-mysql php7.2-xml php7.2-xmlrpc php7.2-ldap php7.2-zip php7.2-soap php7.2-mbstring
- sudo service apache2 restart
- sudo apt install git
- Step 4: Download Moodle cd /opt sudo git clone git://git.moodle.org/moodle.git cd moodle sudo git branch -a sudo git         branch –track MOODLE_38_STABLE origin/MOODLE_38_STABLE sudo git checkout MOODLE_38_STABLE
- Step 5: Copy local repository to /var/www/html/ sudo cp -R /opt/moodle /var/www/html/ sudo mkdir /var/moodledata sudo       chown -R www-data /var/moodledata sudo chmod -R 777 /var/moodledata sudo chmod -R 0755 /var/www/html/moodle
- Step 6: Setup MySQL Server sudo vi /etc/mysql/mysql.conf.d/mysqld.cnf sudo service mysql restart sudo mysql -u root -p

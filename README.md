# Sari-Sari-Store-Twist

This is System that has two main sub-system combined but separeted would be indepedent to each other.
This sub-systems are an inventory sub-system and a pos sub-system.
Additional sub-system are a login sub-system.

The files are created using PHP and a main index.html for the login sub-system.

In this repository is the sql file needed to have the start up of the database.

Additional items in the repository are the images files and css needed for the system.

#~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~#


This system was created by me and my partner jacob-cruz.

This is our Final Project for our subject System Integration, where we individually created the main sub-system 
and integrate the systems to one main system.

To run the System Download the Final Project Folder.

1) Run XAMPP Control Panel
2) Run Apache and MySQL
3) Make the "file_upload = On" in 'php.ini' of 'Apache' by clicking config
4) Import the included testdb.sql in the MySQL
5) Finally, search and run the localhost:xxxx/Final-Project/index.html


#~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~#

To add in more Account Members Just Insert it using the localhost/myphpadmin

Test Account
Enter Employee ID: test
Enter Password: test

To add more categories in the inventory you must add more options in the select input at the new_item and edit_save PHP

#~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~#

LOGIC BOMB is at authenticate.php, INV_Function.php and POS_Functions.php and will trigger on specific input by the user on index.html

This project is the same with added Bombs in it. It is obvious where as the bomb is input-based on PHP. 

This project is done by me (adding the bombs) but the project was done together with me and jacob-cruz a long time ago. This is dedicated for a Project Exam
in regards to Logic Bombs in functioning web application. This is my take on in this task.

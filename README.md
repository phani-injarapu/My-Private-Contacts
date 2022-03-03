# My-Private-Contacts
Android Java Application for save and view Personal Contact Informations

Instructions to run the application in android devices

1.Download All files In Zip format in Git
2.Extract The Zip File
3.Save the File
4.Download Android Studio Latest Version (Android Studio Bumblebee | 2021.1.1 Patch 2 )
5.open the file in android studio

6.Now open Settings in your mobile then click Developer options
7.Enable USB DEBUGGING and INSTALL VIA USB
8.Now connect your phone with PC
9.Then Android Studio Displays your device in Available Devices then (click Run app button)
10.App will install in your Mobile

About Project

1. It contains 6 Java files and 5 Xml files
2. Starting In activity_main.xml containing sign-up layout having 3 EditText fields (Email,Password,SecretCode) and a button called signup
3. Each EditText fields having ID those id's are passes to MainActivity.java 
4. MainActivity.java gets the data and passes through DBHelper
5. DBHelper is a database file here we storing the data with the help of SQLite 
6. DBHelper contains database name Userdata.db, contains 2 tables Userdetails and UserContactdetails
7. Userdetails for storing the registered users data
8. UserContactdetails for storing the Contacts data which are saved by users
9. After Registration activity_login.xml layout will appears it a Sign in layout.
10. Then Sign in With the Registered Credentials These Data will passes to LoginActivity.java and it Checks the Userdetails are valid or not with the Help of DBHelper
11. After user enters valid information, activity_contact.xml layout opens it shows UserContactdetails in cards format
12. By Clicking Add button activity_add_conatct.xml will opens and it contains 3 EditText fields (Name,Phone no,Email) and button called Save
13. By Saving it Stored in UserContactdetails Table.
14. With the help of MyAdapter.java file the UserContactdetails Table will takes the each row in array format and passes to contacts_list.xml it appears each row in cards Format.

JavaFiles
->MainActivity
->LoginActivity
->DBHelper
->ContactActivity
->AddContact
->MyAdapter

Layouts
->activity_main
->activity_login
->activity_contact
->contacts_lists
->activity_add_contact


# REALTIME DATABASE

Step 1: Go to https://console.firebase.google.com Login with your g-mail id. 

Step 2: Click on Create a New Project. 

Step 3: Enter the name of your project. Accept terms and continue.

 Step 4: Deny Google Analytics use. 

Step 5: Visit the Database section of the dashboard and click on Create Database. 

Step 6: Create the database in test mode for now. 

 DATABASE - We can sync using DATABASE. Database lets you store and sync data between your users in realtime.

database is the connectivity word.

calling database -

database = firebase.databse();

 .ref() is used to refer to the location of the database value we care about. 

.on() creates a listener which keeps listening to the changes in the database.

 Every time a change in the database values of position (reference) occurred, the readPosition function was called. 

If there was any error in reading the values in the database, the showError function was called.
# login_and_resoursec_for_each_user
Servlet that shows different resources to different users
---------
TASK
---------
Write a simple web application which allows the users to display the resources whichare available to them.
The application should keep info on users in a database table „Users”.
One entry in thetable contains: technical (so called surrogate) identifier, login, first name, last nameand the password.
The resources are stored in „Resources” database table. 
Each entry contains: surrogate identifier, name and content — a 2048-byte long string.
Any resource may be accessible to multiple users, and each user may access multiple resources,
which implies that in the relational model there should be a junction tablebetween the two tables mentioned.
Your web application should allow the user to establish a session after successfulauthentication.
Within a session, the user can browse the resources he/she has accessto.
This means that your application should provide three different user screens:
1. entry login screen for user authentication;
2. a screen listing resources available to the user (just their names);
the resourcedetails page (see below) is displayed when the user presses a „Details” buttonbeside the name of the resource;
3. a screen presenting details of a particular resource displaying both the nameand the content.
NOTE: Screens (2) and (3) should contain a „logout” button which invalidates thesession.  
Screen (3) should have a button/link to navigate back to the list of theavailable resources.
NOTE: Your solution should utilizeDataSourcemechanism which supports databaseconnection pooling.

week4-lab
=========

Lab for Week 4 that goes over models, db migrations, rails console, and CRUD


For this lab you will be adding additional features to the current application included.

Instructions:
------------
2. Run 'rake db:migrate' 
3. Run 'rails s'
4. go to the url /users

You should be able to do this fine. If you run into any issues, please see a TA for help.

Warmup:
-------
1. Go to your rails console, and add 3 users
  -Make sure that you can see these 3 users at /users
2. Use the form or the console to edit the names of these users
  -See the changes appear at /users
  
  
Questions:
----------
1. Add a new field to the user called "phone"
  -Add phone numbers to all the previous users using the edit form, not the console
2. Delete the age field from the user
3. Make the index page only show the latest added User.

Bonus:
------
1. Add a create form so you can go to /users/new to create a user successfully.
Hint: Try to take parts of the update/edit logic you see in the form/controller and copy that over


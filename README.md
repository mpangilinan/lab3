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
    1. Make sure that you can see these 3 users at /users
2. Use the form or the console to edit the names of these users
    1. See the changes appear at /users
  
  
Questions:
----------
1. Delete the age field from the user
     1. Running 'User' on rails console should not show the age field 
2. Add it back, but this time call it "yearsold" (Update the edit form and the controller as well)
     1. Running 'User' on rails console should now show the yearsold field.
     2. Go ahead and update all the users again to have years because right now they are null, using the edit form.
3. Show only users that are > 50 yearsold on the index
3. Add a new field to the user called "phone"
    1. Add phone numbers to all the previous users using the edit form, not the console

Bonus:
------
1. Add a create form so you can go to /users/new to create a user successfully.


Hint: Try to take parts of the update/edit logic you see in the form/controller and copy that over


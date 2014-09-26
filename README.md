week4-lab
=========

Lab for Week 4 that goes over models, db migrations, rails console, and CRUD

For this lab you will be adding additional features to the current application included.

Instructions:
------------
1. cd into week4 rails app.
2. Run 'rake db:migrate' 
3. Run 'rails s'
4. go to the url /users

You should be able to do this fine. If you run into any issues, please see a TA for help.
If you see no users, it means you need to create some first

Warmup:
-------
1. Go to your rails console, and add 3 users
    1. Make sure that you can see these 3 users at /users
2. Use the console to edit the names of these users
    1. See the changes appear at /users
  
  
Questions:
----------
1. Delete the age field from the user
     1. Running 'User' on rails console should not show the age field 
2. Add it back, but this time call it "yearsold" (Update the edit form and the controller as well)
     1. Running 'User' on rails console should now show the yearsold field.
     2. Go ahead and update all the users again using the console, since their yearsold will be blank now
3. Show only users that are > 50 yearsold on the index

Bonus (Hard):
------
1. Add a create form so you can go to /users/new to create a user successfully.


Lab located at▫
https://github.com/rails-decal/week4-lab

########################################
Hints for lab warmup:
########################################
In console:

$ User.all # This will show all users
$ wonjun = User.new
$ wonjun.age = 99
$ wonjun.name = "wonjun"
$ wonjun.save

$ User.all # You can now see wonjun

Find a user in the console by using User.find(<id>)
Remember to create a variable with them and then save it to the database to actually edit!

########################################
Hints for lab questions:
########################################
1. migrations (also help you delete :D)
$ rails generate migration RemoveFieldNameFromTableName field_name:datatype
$ rake db:migrate
# If you can't remember a command or need to know, google is your friend!
2. migrations
3. Checkout the index function

Bonus:
Hint: You need to use a form, and work with both the new/create functions in the controller
Check out https://www.railstutorial.org/book to learn more about how you could do this


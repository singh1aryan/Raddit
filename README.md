# My Notes for This

## My first Ruby w Rails Application

Web dev w ruby on rails

Template
mnt/c/Users/Aryan Singh/ruby_on_rails/reddit
$ rails generate scaffold link title:string url:string

Migrating
 bin/rails db:migrate RAILS_ENV=development

Template 
 rails generate scaffold link title:string url:string

Devise:
We have to configure the devise thing to set up the users, with some copy paste of code
Made the sign up, sign in and user page for us, added it to our database as well

Rails c - console for the database and we can use that for the db
User.count - counts, capital U for user
Cntrl k to exit it

Rails db:migrate instead of rake

Undefined method build for current user

User auth, so only selected people do stuff
Built in functions - links_controller
before_filter = authenticate_user!, except: [:index, :show]

@link = link.find
@link.user = User.first -- setting the user
@link.save - saving the thing

link = Link.first
link.user = User.first
link.save

Index is the page for this






# Reddit Clone, Mackenzie Child

https://www.youtube.com/watch?v=7-1HCWbu7iU&list=PL23ZvcdS3XPLNdRYB_QyomQsShx59tpc-&index=1 <br>
Sign In/Sign Up, Log In, Post, Comment, Upvote/Downvote, Change Settings - Created using Ruby with Rails

## Basic Overview 

Controllers, Helpers, Jobs, Mailers, Models, Views - The UI which we see <br>
Template - rails generate scaffold link title:string url:string<br>
Gems - Add to Gemfile, bundle install, read documentation for use<br>
Bootstrap - A kind of Gem, install, use in built classes like "btn btn-group" or "form-group"<br>
Migration - Migrate tables to DB using rake db:install or rake db:install<br>
Console - Database console, type "rails c" in bash<br>
Server - "rails s" -- http://localhost:3000 - Your server<br>

## New Changes for Ruby > 5

Rails db:migrate works for me<br>
before_filter -- before_action, Eg: before_filter = authenticate_user!, except: [:index, :show] <br>
redirect_to :back -- redirect_back fallback_location: root_path <br>
Application controller - devise_parameter_sanitizer.permit(:account_update, keys: [:name]) <br>

## Linking User and Links(Posts)

@link = link.find<br>
@link.user = User.first -- setting the user<br>
@link.save - saving the thing<br>

link = Link.first<br>
link.user = User.first<br>
link.save<br>

## Some Ruby and Rails Knowledge
Coming soon

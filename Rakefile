

# This pulls in rake commands in from activerecord
# When you run this in the command line: 
# $ rake db:create_migration NAME=create_posts

# Then if you look at your project structure. You’ll see a new folder 
# called “db” and within that folder another folder called “migrate.” You 
# should then see a Ruby script with a timestamp. This is a migration file
# The timestamp tells ActiveRecord the order in which to apply the 
# migrations in case there is more than one file.

require './app'
require 'sinatra/activerecord/rake' 

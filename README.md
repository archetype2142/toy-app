== README

View the toy-app in action <a href ="http://ritwick-microposts-app.herokuapp.com/">here</a>
<hr>

This application uses rails v 4.2.0 alond with other dependencies stated in the gemfile. 
sqlite3, byebug and spring gems are only for development and testing purposes, for production postgress is being used which can be switched with any other database

You need to migrate the database before using the program using rake 
<code>bundle exec rake db:migrate</code>
If using heroku, you can use
<code>heroku run rake db:migrate</code>

To run the local server navigate to the installation directory and use
<code>rails server</code>

The databse(mysqlite3) can be accessed by 
<code>rails console</code>

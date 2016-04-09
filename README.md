#Toy App

View the toy-app in action [here]('http://ritwick-microposts-app.herokuapp.com/')
<hr>

This application uses rails v 4.2.0 alond with other dependencies stated in the gemfile. 
sqlite3, byebug and spring gems are only for development and testing purposes, for production postgress is being used which can be switched with any other database

You need to migrate the database before using the program using rake 
    bundle exec rake db:migrate
If using heroku, you can use
    heroku run rake db:migrate
    
To run the local server navigate to the installation directory and use
    rails server

The databse(mysqlite3) can be accessed by 
    rails console

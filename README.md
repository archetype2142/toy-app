#Toy App

View the toy-app in action [here](http://ritwick-microposts-app.herokuapp.com/)
The application opens in the users view, navigate to /microposts for the [microposts](http://ritwick-microposts-app.herokuapp.com/microposts)
<hr>

This application uses rails <b>v 4.2.0</b> along with other dependencies mentionened in the [gemfile](https://github.com/archetype2142/toy-app/blob/master/Gemfile).
sqlite3, byebug and spring gems are only for development and testing purposes, for production postgress is being used which can be switched with any other database

You need to migrate the database before using the program using rake<br>
`bundle exec rake db:migrate`


If using heroku, you can use<br>
`heroku run rake db:migrate`
    

To run the local server navigate to the installation directory and use<br>
`rails server`


The database(mysqlite3) can be accessed from the rails console using<br>
`rails console`

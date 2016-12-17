CherryTomato
---

http://cherrytomato.herokuapp.com/

A time organizer based on the Pomodoro technique.

[![Build Status](https://travis-ci.org/aaooki/CherryTomato.svg?branch=master)](https://travis-ci.org/aaooki/CherryTomato)

## Installation
- You need Ruby 2.3+, and bower.

- Install the needed gems and bower componenets by running `bundle install` and `bower install`.

- Create a file named `settings.rb` and add your env variables there.
  An example is provided in `settings.example.rb`.

- For the first time, you want to setup the database, run
  `./run_migrations` to create the database and the tables needed.
  A PostgreSQL server must be running.

- Run the server using `rackup -p 7777` or provide another port number.

## License
See [LICENSE](https://github.com/aaooki/CherryTomato/blob/master/LICENSE).

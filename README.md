# README

This README would normally document whatever steps are necessary to get the
application up and running.

Things you may want to cover:

* Ruby version
  * 3.2.0

* System dependencies
  * mysql
    * `sudo apt install mysql-server`
    * `sudo mysql_secure_installation`
    * `sudo apt install libmysqlclient-dev`

* Configuration
  * `touch .env`
    * Add DATABASE_USERNAME, DATABASE_PASSWORD, DATABASE_HOST

* Database creation
  * `CREATE USER 'mysql'@'%' IDENTIFIED BY '123';`
  * `CREATE DATABASE bto_development;`
  * `GRANT ALL PRIVILEGES ON bto_development.* TO 'mysql'@'%';`
  * `FLUSH PRIVILEGES;`
  * `EXIT;`

* Database initialization
  * `rake db:migrate`

* App initialization
  * `bundle install`

* Running the app
  * `rails s`

* How to run the test suite

* Services (job queues, cache servers, search engines, etc.)

* Deployment instructions

* ...




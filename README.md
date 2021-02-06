# E-Library

This repository contains the code base for the e-library application created for 41094 Software Engineering Studio 1B in 2020 Spring Semester.

## Pre-requisites
1. Pull repo `git clone https://github.com/pharapeti/e-library.git`
2. Install [rvm](https://rvm.io/)
3. Using rvm or any other ruby manager, install Ruby. Ensure you install the same version as the one specified in the **Gemfile**
4. In command prompt, run `gem install bundler`
4. Navigate to cloned directory and run `bundle install`. This will install the gem dependencies of the project
5. In the same directory, run `yarn`. If the yarn command is not found, you will need to install it
6. Run `rake db:drop db:create db:migrate db:seed` to create the database and run the migrations.
7. Run `rake db:fixtures:load` to insert the fixtures into your database.
8. Run `rails server -p 9090` in command prompt to start server on port 9090 (you can alias this to `rs` if you wish)
9. Open a web browser and navigate to `localhost:9090` to see the homepage

## Contributors also known as Group 7:
- Patrice Harapeti
- Davit Gevorgyan
- Ahmed Khursheed
- Helena Tran
- Jun Kok
- Patrick Mouawad

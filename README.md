# Ruby on Rails Tutorial sample application

This is the sample application for
[*Ruby on Rails Tutorial:
Learn Web Development with Rails (4th Edition, online version)*](http://www.railstutorial.org/)
by [Michael Hartl](http://www.michaelhartl.com/).

## License
All source code in the [Ruby on Rails Tutorial](http://railstutorial.org/)
is available jointly under the MIT License and the Beerware License. See
[LICENSE.md](LICENSE.md) for details.

## Deployment
This project is hosted by Heroku on (https://warm-ravine-91766.herokuapp.com/). As of time of writing, the production version is completed for chapter 13. The chapter 11 and 12 are skipped, so the email server is disabled.

## New Getting started 2.0
Clone the app to your folder and change the Github remote push and pull addresses
```
$ cd ~
$ git clone https://github.com/jimmy2046/sample_app_heroku_2 your_new_folder
$ git remote show origin
$ git remote set-url origin https://github.com/your_Github_name/your_new_folder.git
$ git remote show origin
$ git remote -v
$ git push -u origin master
```
<br />Run bundle install, migrate and seed the database
```
$ bundle install
$ rails db:migrate
$ rails db:seed

```
<br />Run a test, and start the server
```
$ rails test
$ rails s -b 0.0.0.0 -p 3000
```

<br />In Firefox, type http://localhost:3000/
```
http://localhost:3000/
```

## Getting started

To get started with the app, clone the repo and then install the needed gems:

```
$ bundle install --without production
```

Next, migrate the database:

```
$ rails db:migrate
```

Finally, run the test suite to verify that everything is working correctly:

```
$ rails test
```

If the test suite passes, you'll be ready to run the app in a local server:

```
$ rails server
```

For more information, see the
[*Ruby on Rails Tutorial* book](http://www.railstutorial.org/book).
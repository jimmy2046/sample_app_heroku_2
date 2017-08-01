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
[https://warm-ravine-91766.herokuapp.com/](https://warm-ravine-91766.herokuapp.com/) (live production, no mail server)<br />
This project is hosted by Heroku. All 14 chapters were completed on July 31, 2017. The chapter 11 and 12 are skipped, so the email server is disabled.

## Getting started 2.0
If you are using Ubuntu Linux with Ruby on Rails installed, you can clone the app to your folder and change the Github remote push and pull addresses
```
$ cd ~
$ git clone https://github.com/jimmy2046/sample_app_heroku_2 your_new_folder
$ git remote show origin
$ git remote set-url origin https://github.com/your_Github_name/your_new_folder.git
$ git remote show origin
$ git remote -v
$ git push -u origin master
```
Run bundle install, migrate and seed the database
```
$ bundle install
$ rails db:migrate
$ rails db:seed

```
Run a test, and start the server
```
$ rails test
$ rails s -b 0.0.0.0 -p 3000
```

In Firefox, type http://localhost:3000/
```
http://localhost:3000/
```

For more information, see the
[*Ruby on Rails Tutorial* book](http://www.railstutorial.org/book).
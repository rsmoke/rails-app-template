# README

This README would normally document whatever steps are necessary to get the
application up and running.

Things you may want to cover:

* Ruby version

* System dependencies

* Configuration

* Database creation

* Database initialization

* How to run the test suite

* Services (job queues, cache servers, search engines, etc.)

* Deployment instructions

* ...

- ```git clone <repo>```
- ```cd <app directory>```
- ```docker-compose run --rm web bundle```
- ```docker-compose run --rm web rails db:create```
- ```docker-compose run --rm web rails db:migrate```
- ```docker-compose run --rm web yarn```
- ```docker-compose up```

#### If you add anything to the app you will need to run ??????
```
docker-compose up --build
````
### If your app is ugly run
```docker-compose run --rm web yarn```
- then call Rita B for help

#Rocket-Template
This is a REST API project template that uses [Rocket](https://github.com/SergioBenitez/Rocket) framework with [Diesel](https://github.com/diesel-rs/diesel) ORM backed up with Postgresql database. You can generate project skeleton using  porteurbars.

- In order to create project you need to install [porteurbars](https://github.com/softprops/porteurbars) first.
- Run 
 ```porteurbars orhanbalci/rocket-template your_project_directory```
- You need nightly version of Rust for [Rocket](https://github.com/SergioBenitez/Rocket).
 ```rustup default nightly```
- Install diesel_cli.
- ```apt get install libsqlite3-dev
     apt get install libmysqlclient-dev
     apt get install libpq-dev
     cargo install diesel_cli```
- Run database migration from your project directory. First make sure you have a working database url in your .env file.
    ```disel migration run```
- Run your rest api server
    ```cargo run```
- Skeleton code is taken from [mgattozi](https://github.com/mgattozzi/mgattozzi)


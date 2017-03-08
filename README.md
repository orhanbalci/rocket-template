#Rocket-Template
This is a REST API project template that uses Rocket framework. You can generate project skeleton using  porteurbars.

- In order to create project you need to download [porteurbars](https://github.com/softprops/porteurbars) first.
- Run 
- ```porteurbars orhanbalci/rocket-template your_project_directory```
- You need nightly version of Rust for [Rocket](https://github.com/SergioBenitez/Roscket).
- ```rustup default nightly```
- Install diesel_cli.
- ```apt get install libsqlite3-dev
     apt get install libmysqlclient-dev
     apt get install libpq-dev
     cargo install diesel_cli```
- Run database migration from your project directory
    ```disel migration run```
- Run your rest api server
    ```cargo run```


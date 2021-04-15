# docker-compose files
>Repository with a list of docker-compose files.

files:\
:white_check_mark: Wordpress + mysql\
:white_check_mark: MongoDB


## Installation

Open a terminal and `cd` to the folder in which `docker-compose.yml` is saved and run:

```
docker-compose up
```

### Removing containers

To stop and remove all the containers use the`down` command:

```
docker-compose down
```
Use `-v` if you need to remove the database volume which is used to persist the database


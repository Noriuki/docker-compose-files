# docker-wordpress
Docker compose file for Wordpress + mysql environment


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


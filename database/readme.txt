- build image
    docker build -t my-postgres ./
- run image
    docker run -d --name my-postgresdb -p 5432:5432 my-postgres
- test on psql
    docker exec -it my-postgresdb psql -U postgres
    set search_path to <database>,public;
    **remember don't forget semicolon**

***don't forget to create database 'cuase didn't write valumes or you just write it whatsever***
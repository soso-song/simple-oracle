following https://www.youtube.com/watch?v=jJOjyDpg1aA&t=1071s



Add `/Library/PostgreSQL/15/data` and directory of `chainlink-volume` to docker

- Resources -> File sharing



run

`docker pull smartcontract/chainlink`

`docker pull postgres`

in run-node, run

`docker-compose up`



Find container `pg_chainlink-1` open in terminal/CLI

`psql -U postgres -h localhost`

`CREATE DATABASE chainlink;`

`\list`

`docker-compose up`



Access `http://localhost:6688/signin`

Enter password from apicredentials.txt
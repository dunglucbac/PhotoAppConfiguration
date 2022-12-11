# PhotoAppConfiguration

**Run Rabbit MQ**

`docker run -it --rm --name rabbitmq -p 5672:5672 -p 15672:15672 rabbitmq:3.11-management`

**Run MySQL in Docker**

`docker run --name=mysql1 -p 3306:3306 -v mysql-volume:/var/lib/mysql -e MYSQL_ROOT_PASSWORD=123456 -d mysql/mysql-server:8.0`

`docker exec -it mysql1 mysql -u root -p`

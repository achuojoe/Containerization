docker run -p 3306:3306 -d --name mysql mysql/mysql-server:latest

docker ps

docker start
docker run
docker status

[Entrypoint] GENERATED ROOT PASSWORD: 4G1P385A4@D&Ll_^D&0x6FioVsCX?@:E
docker logs
docker exec -it mysql bash

mysql -uroot -p

ALTER USER 'root'@'localhost' IDENTIFIED BY 'newpassword';

ALTER USER 'root'@'localhost' IDENTIFIED BY 'admin';

create database weekly_product_sales;

create database company_payroll;

docker commit 3f3946d5572f 

docker tag 6543bda6ac1e mysql/mysql-server/added-two-databases:v2  

docker run -p 3307:3306 -d --name mysql-v2 mysql/mysql-server/added-two-databases:v2

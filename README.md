# docker-oracle-xe-10g

====================

Oracle Express Edition 10g Release 2 (10.2.0.1) 32-bit on Debian 7.0 Wheezy.


### Installation
```
docker pull abc0012544/oracle-xe-10g
```

Run with 22, 1521 and 5500 ports opened:
```
docker run -d -it --name orcldb10gcao -p 30022:22 -p 1521:1521 -p 5500:5500 abc0012544/oracle-xe-10g
```

Connect database with following setting:
```
hostname: localhost
port: 1521
sid: xe
username: system
password: oracle
```

Password for SYS & SYSTEM
```
oracle
```

Login by SSH
```
ssh root@localhost -p 30022
password: admin
```

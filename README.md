# Docker templates

Some baisc docker based development environements
- php-mysql
- php-mongo

## php-mysql
Contains estandar php + mysql environment
- apache 7.4
- mysql 5.7

Configure servers within .env file

Enter docker-php-mysql folder and type:
```
# This will launch both servers in background.
sudo docker-compose up -d
```

## php-mongo
Contains php + mongo environment
- apache 7.4
- mongo 6.0.3

Configure servers within .env file

Enter docker-php-mongo folder and type:
```
# This will launch both servers in background.
sudo docker-compose up -d
```

Enter workspace for code install an configs:
```
sudo docker-compose exec workspace bash
```

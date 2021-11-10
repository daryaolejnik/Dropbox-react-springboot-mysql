# Dropbox-React-SpringBoot-MySQL

A Dropbox like web application using React.js | Java Spring Boot | Spring Data | Hibernate | MySQL


## Requirments

maven >3.6.1
jdk >8
npm >12.7
MariaDB 10.6

## Run application

### Database configuration
Run mysql script
```
mysql> source database_dump.sql
```

### Run backend
Unit tests don't work
```
cd springboot-backend
java package -DskipTests-true
```

### Run frontend
```
cd react-frontend
npm install
npm start
```
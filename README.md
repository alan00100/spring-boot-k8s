# new-springboot

 vi /etc/mysql/mysql.conf.d/mysqld.cnf   _-------> open this file in mysql database server and add bind address as a 
 
 bind-address            = 0.0.0.0
mysqlx-bind-address     = 127.0.0.1


and in vi src/main/resources/application.properties FILE 

 jdbc:mysql://13.214.203.153:3306/notes_app?useSSL=false&serverTimezone=UTC&useLegacyDatetimeCode=false&allowPublicKeyRetrieval=true&useSSL=false  
 
 add like this
 
 
 

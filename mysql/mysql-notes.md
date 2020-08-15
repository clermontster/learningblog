# Install Mysql

On a mac:
* use homebrew

On Windows:
* uses mysql installer


## Run MySql for the first time

*Start MySql*
```
mysql -u root
```

*Add an existing database:*
1. start mysql
2. create database <database name>
3. stop mysql
4. Map newly created database to actual database file
```
mysql -u root <database name> < <databaseFileName>.sql
```

*Errors:*

If you get the following error:
```
ERROR 1045 (28000): Access denied for user 'root'@'localhost' (using pas
sword: NO)
```

Follow these steps
```
$ brew services stop mysql
$ pkill mysqld
$ rm -rf /usr/local/var/mysql/ # NOTE: this will delete your existing database!!!
$ brew postinstall mysql
$ brew services restart mysql
```





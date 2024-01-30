# DbUp MySql support using MySqlConnector
DbUp is a .NET library that helps you to deploy changes to SQL Server databases. It tracks which SQL scripts have been run already, and runs the change scripts that are needed to get your database up to date.

This package is a branch of [dbup-mysql](https://github.com/DbUp/dbup-mysql) which uses [MySqlConnector](https://github.com/mysql-net/MySqlConnector) instead of MySql.Data.

One of the primary reasons for this was to work around compatibility issues with MariaDb and MySql.Data:

* [Problem using mariadb 10.10+](https://github.com/DbUp/DbUp/issues/762)
* [MySQL Connector fails to connect to MariaDB 10.10.2](https://bugs.mysql.com/bug.php?id=109331)
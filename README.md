[![GitHub Workflow Status (branch)](https://img.shields.io/github/actions/workflow/status/n-vision/dbup-mysql-mysqlconnector/main.yml?branch=main)](https://github.com/n-vision/dbup-mysql-mysqlconnector/actions/workflows/main.yml?query=branch%3Amain)
[![NuGet](https://img.shields.io/nuget/dt/dbup-mysql-mysqlconnector.svg)](https://www.nuget.org/packages/dbup-mysql-mysqlconnector)
[![NuGet](https://img.shields.io/nuget/v/dbup-mysql-mysqlconnector.svg)](https://www.nuget.org/packages/dbup-mysql-mysqlconnector)
[![Prerelease](https://img.shields.io/nuget/vpre/dbup-mysql-mysqlconnector?color=orange&label=prerelease)](https://www.nuget.org/packages/dbup-mysql-mysqlconnector)

# DbUp MySql support using MySqlConnector
DbUp is a .NET library that helps you to deploy changes to SQL Server databases. It tracks which SQL scripts have been run already, and runs the change scripts that are needed to get your database up to date.

This package is a branch of [dbup-mysql](https://github.com/DbUp/dbup-mysql) which uses [MySqlConnector](https://github.com/mysql-net/MySqlConnector) instead of MySql.Data.

One of the primary reasons for this was to work around compatibility issues with MariaDb and MySql.Data:

* [Problem using mariadb 10.10+](https://github.com/DbUp/DbUp/issues/762)
* [MySQL Connector fails to connect to MariaDB 10.10.2](https://bugs.mysql.com/bug.php?id=109331)

## Getting Help
To learn more about DbUp check out the [documentation](https://dbup.readthedocs.io/en/latest/).

Please only log issue related to MySql support in this repo. For cross cutting issues, please use the DbUp [main issue list](https://github.com/DbUp/DbUp/issues).

# Contributing

See the [readme in our main repo](https://github.com/DbUp/DbUp/blob/master/README.md) for how to get started and contribute.
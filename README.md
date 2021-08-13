# MONCoin® Blockchain Data Collection Agent
> Collects MONCoin® blockchain data into a SQL backend that serving and using the data a breeze.

## Prerequisites

- MONCoin® >= 0.12.0
- node >=6
- MariaDB/MySQL with InnoDB support

## Hardware Requirements

For the best performance when using this package (as of July 31, 2021), your Database server must have a minimum of the following:

* 4GB RAM
  * 4GB dedicated to MariaDB/MySQL
* 2 CPU Cores (4 Recommended)
* SSD Storage

***Warning***: Running the DB on system(s) with less than the minimum hardware requirements above will cause performance issues. If you are experiencing issues please verify that the system you are using meets the minimum requirements above. We cannot assist with performance issues with implementations that do not meet the above minimum requirements.

## Recommended Reading

The help tune your selected DBMS, we recommend that you read the following documents, at a minimum, to tune your DBMS installation for the dataset this package manages.

This list is by no means comprehensive nor do we guarantee the information or suggestions provided in the articles below are accurate. These links are provided solely as a jumping off point to get you started.

* [MySQL 5.7 Performance Tuning After Installation](https://www.percona.com/blog/2016/10/12/mysql-5-7-performance-tuning-immediately-after-installation/)
* [InnoDB Performance Optimization Basics](https://www.percona.com/blog/2013/09/20/innodb-performance-optimization-basics-updated/)
* [Optimizing InnoDB Disk I/O](https://dev.mysql.com/doc/refman/8.0/en/optimizing-innodb-diskio.html)
* [Optimizing InnoDB Configuration Variables](https://dev.mysql.com/doc/refman/8.0/en/optimizing-innodb-configuration-variables.html)
* [15 Useful MySQL/MariaDB Performance Tuning and Optimization Tips](https://www.tecmint.com/mysql-mariadb-performance-tuning-and-optimization/)
* [InnoDB Performance Optimisation](https://www.slideshare.net/MyDBOPS/innodb-performance-optimisation)

## Install

```sh
npm install
```

## Usage

1) Set your environment variables and start the service up

```sh
export MYSQL_HOST=127.0.0.1
export MYSQL_PORT=3306
export MYSQL_USERNAME=yourdbusername
export MYSQL_PASSWORD=yourdbpassword
export MYSQL_DATABASE=yourdbname
export NODE_HOST=127.0.0.1
export NODE_PORT=12898
npm start
```

## Run tests

```sh
npm test
```

## 🤝 Contributing

Contributions, issues and feature requests are welcome!

Feel free to check [issues page](https://github.com/Kulteam/Blockchain-data-collection-agent/issues).

## Show your support

Give a ⭐️ if this project helped you!


## 📝 License

This project is [AGPL-3.0](https://github.com/Kulteam/Blockchain-data-collection-agent/blob/master/LICENSE) licensed.

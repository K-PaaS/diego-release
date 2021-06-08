## 01. Check the commit contents
> [enable cce](https://github.com/PaaS-TA/diego-release/commit/75d788763c8147256d26220564d4cb77c9d4d7be)

## 02. Submodule modify : go-sql-driver/mysql (src/github.com/go-sql-driver/mysql)
> pull v1.4.1 go-sql-driver/mysql
``` 
$ rm -rf src/github.com/go-sql-driver/mysql
$ mkdir -p src/github.com/go-sql-driver/mysql
$ git clone https://github.com/go-sql-driver/mysql.git -b v1.4.1 src/github.com/go-sql-driver/mysql
```
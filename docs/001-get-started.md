# get-started


## installation
> 从 MongoDB 3.0 版本开始只支持 OS X 10.7 (Lion) 版本及更新版本的系统。

### mac
```shell
brew tap mongodb/brew
brew install mongodb-community@4.2
```

### basic config
- the configuration file (/usr/local/etc/mongod.conf)
- the log directory path (/usr/local/var/log/mongodb)
- the data directory path (/usr/local/var/mongodb)

## operations
- brew services start mongodb/brew/mongodb-community
- brew services stop mongodb/brew/mongodb-community
- mongod --config /usr/local/etc/mongod.conf --fork
- ps aux | grep -v grep | grep mongod

## repl
```shell
cd /usr/local/opt/mongodb-community/bin
./mogo
```

## resources
- https://www.runoob.com/mongodb/mongodb-osx-install.html
- https://docs.mongodb.com/manual/tutorial/install-mongodb-on-os-x/
- https://github.com/mongodb/homebrew-brew

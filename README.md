常用库:
    web框架:
            gin: go get -u -v github.com/gin-gonic/gin
    数据库:
            mysql 驱动: go get -u -v github.com/go-sql-driver/mysql
            redis : go get -u -v github.com/gomodule/redigo/redis
            orm : go get -u -v github.com/jinzhu/gorm

环境搭建:
    设置git代理端口:  git config --global http.proxy socks5://127.0.0.1:xxxx
                    git config --global --unset http.proxy
    go get 代理端口: https_proxy=socks5://127.0.0.1:xxxx  http_proxy=socks5://127.0.0.1:xxxx
# docker-compose

主要放置一些自己在学习过程中使用docker-compose启动的内容

## docker-compose启动服务

* 启动所有服务
`docker-compose up -d`

* 启动某个服务
`docker-compose up -d redis` (启动Redis服务)

* 查看启动的服务
`docker-compose ps`

* 停止某个服务
`docker-compose stop nacos`(停止nacos服务)

* 删除某个已经停止的服务
`docker-compose rm nacos`(删除停止的nacos服务，需要确认是否删除)
`docker-compose rm -f nacos`(删除停止的nacos服务，不需要确认直接删除)

* 停止某个服务并直接删除
`docker-compose rm -sf nacos`(停止nacos服务并将其删除)

* 停止并删除所有服务
`docker-compose down`

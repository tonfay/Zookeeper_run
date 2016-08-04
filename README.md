# Zookeeper_run
zookeeper运行
最新的版本可以通过官网 http://hadoop.apache.org/zookeeper/来获取

Zookeeper 的启动脚本在 bin 目录下，Windows 下的启动脚本是 zkServer.cmd。

将 zoo_sample.cfg 改名为 zoo.cfg,因为 Zookeeper 在启动时会找这个文件作为默认配置文件

tickTime：这个时间是作为 Zookeeper 服务器之间或客户端与服务器之间维持心跳的时间间隔，也就是每个 tickTime 时间就会发送一个心跳。

dataDir：顾名思义就是 Zookeeper 保存数据的目录，默认情况下，Zookeeper 将写数据的日志文件也保存在这个目录里。

dataLogDir：顾名思义就是 Zookeeper 保存日志文件的目录

clientPort：这个端口就是客户端连接 Zookeeper 服务器的端口，Zookeeper 会监听这个端口，接受客户端的访问请求。

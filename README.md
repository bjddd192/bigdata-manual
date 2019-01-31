# 简介

## 从零开始

[一个大数据小白到架构的经历](https://www.jianshu.com/p/cd2d3256cc52)

上面这篇文章对我很有启示作用，目前我也是一个小白，需要有明确的目标，去快速熟悉大数据体系并作出成绩。

## Impala

[Download Impala JDBC Connector 2.6.4](https://www.cloudera.com/downloads/connectors/impala/jdbc/2-6-4.html)

[Download Impala JDBC Connector 2.5.41](https://www.cloudera.com/downloads/connectors/impala/jdbc/2-5-41.html)

[Download Impala ODBC Connector 2.5.44](https://www.cloudera.com/downloads/connectors/impala/odbc/2-5-44.html)

[impala jdbc url格式](https://blog.csdn.net/gyxinguan/article/details/79526429)

### impala jdbc url格式

示例：

```shell
jdbc:impala://node1.example.com:21050/database;AuthMech=3;UID=cloudera;PWD=cloudera;
```

参数说明：

```shell
# AuthMech 参数
0 for No Authentication
1 for Kerberos
2 for User Name
3 for User Name and Password

# SSL 参数
0, not connect to SSL-enabled sockets.
1, through an SSL-enabled socket.
```

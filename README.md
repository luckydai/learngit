## 发版说明
1.将war包放进tomcat-808X，进入conf目录修改server.xml,修改相应端口为x808X：

2.把属性文件“cdp.properties” 放到目录 /apps/conf/cdp_docker；

3.编辑cdp.properties文件

3.1redis配置
cdp.docker.session.cluster.node.ip.1=****
cdp.docker.session.cluster.node.port.1=6379
cdp.docker.session.cluster.node.password.1=****




3.2数据库连接
jdbc.url=****
jdbc.username=***8
jdbc.password=****


3.3zookeeper配置
dubbo.application.name=cdp-docker
dubbo.registry.address=
dubbo.protocol.dubbo.port=9002

3.4c4a
cdp.docker.auth.c4a.url=
cdp.docker.auth.tob.login.c4a.url=
cdp.docker.auth.tob.intercept.oauth.seed=

3.5kafka
cdp.docker.common.consumer.bootstrap.servers=****
cdp.docker.common.provider.bootstrap.servers=****


```yaml
spring:
  datasource:
    url: jdbc:mysql://127.0.0.1:3306/nmdl?useUnicode=true&serverTimezone=Asia/Shanghai&characterEncoding=utf-8&zeroDateTimeBehavior=convertToNull&autoReconnect=true&allowMultiQueries=true&useSSL=true
    username: nmdl
    password: nmdl@2022
    filters: wall,mergeStat
    type: com.alibaba.druid.pool.DruidDataSource

domain:
    url: impc.com.cn
    ip: 218.202.141.125
    port: 80
```


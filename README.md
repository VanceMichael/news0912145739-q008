# 赛事消息清洗

Java/Spring Boot 消息处理工程起点，运行时从环境变量读取 RabbitMQ、Redis 和 PostgreSQL 地址。这里仅提供可启动的后端外壳，消息消费、版本检查和失败记录由业务模块完成。

## 运行

```bash
docker compose up --build
mvn test
```

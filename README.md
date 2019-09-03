# graphQL-java-demo
#### 文档
https://www.graphql-java.com/tutorials/getting-started-with-spring-boot/
#### 测试方式：
1. 启动服务
2. curl调试（curl命令生成地方：https://www.graphqlbin.com/v2/6RQ6TM）
```
curl 'http://localhost:8080/graphql' -H 'Accept-Encoding: gzip, deflate, br' -H 'Content-Type: application/json' -H 'Accept: application/json' -H 'Connection: keep-alive' -H 'DNT: 1' -H 'Origin: https://www.graphqlbin.com' --data-binary '{"query":"{\n  bookById(id: \"book-1\"){\n    id\n    name\n    pageCount\n    author {\n      firstName\n      lastName\n    }\n  }\n}"}' --compressed
```

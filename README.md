## 部署更新
1. 同步代码后，worker会自动更新
2. 绑定的数据库会掉，需要绑定d1,kv（变量名是db,kv）数据库
3. 执行 https://worker自定义域/api/init/你的jwt_secret 更新数据库 (只会更新不会覆盖已有数据)

- [部署文档](https://doc.skymail.ink)<br>





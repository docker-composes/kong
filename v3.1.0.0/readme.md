# Kong 

## 首次启动

```
# 创建网络
./create_net.sh

# 启动数据库
./run_kong_database.sh

# 迁移数据库
./migrate_kong_database.sh

# 启动网关
./run_kong_gateway.sh

```

## 后续启动

```
# 启动数据库
./run_kong_database.sh

# 启动网关
./run_kong_gateway.sh
```
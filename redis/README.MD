# Redis 配置

## 持久化文件

1. volume  
/docker/host/dir:/data  
config/redis.conf:/etc/redis/redis.conf  
2. CMD  
command [ "redis-server", "/etc/redis/redis.conf"]
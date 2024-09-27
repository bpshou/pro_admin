## Pro Admin 后台管理系统

### 项目介绍
Pro Admin 后台管理系统，使用 ant-design 设计，前端使用 React 开发框架

### DockerCompose 容器开发环境
启动环境
```
docker compose up -d
```
关闭环境
```
docker compose down
```


### Docker 容器开发环境
在项目目录执行如下命令
```
docker run -itd \
    --name pro \
    -p 8787:8080 \
    -v $(pwd):/app \
    -w /app \
    node:latest
```

### 手动创建 Ant-design 项目
```
1. 安装ant-design
npm i @ant-design/pro-cli -g

2. 创建app
pro create app_admin

3. 安装依赖
cd app_admin && npm install --legacy-peer-deps
```

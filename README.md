# 2023-2024-mashibing-web-project
2023-2024-1 web 开发课设

### 开发指南

#### 开发环境
- https://www.phpenv.cn/

#### 前端
- 安装 nvm
- 下载 node 10：`nvm install 10`
- 切换到 node 10：`nvm use 10`
- 进入目录 `projects/front-end`
- 安装依赖 `npm ci`
- 启动前端 `npm run dev`

#### 数据库
- 启动 MySQL 8.0
- 建立数据库 `second_hand_trading`
- 导入数据库 `database/second_hand_trading.sql`

#### 后端
- 使用 jdk 1.8
- 修改 MySQL 账号密码 `projects/back-end/src/main/resources/application.properties`
- 在 idea 中运行 `projects/back-end/src/main/java/com/second/hand/trading/server/ServerApplication.java`

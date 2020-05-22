

### 项目结构图
```
├── package-lock.json
├── package.json
├── postcss.config.js
├── server // 后端代码
│   ├── init // 初始化mysql数据库的脚本
│   ├── package-lock.json
│   ├── package.json
│   ├── src
│     ├── app
│     ├── context
|     ├── controllers
|     ├── index.ts
|     ├── middlewares
|     ├── routes // 后端路由，跟登录注册模块有关
|     ├── server.ts
|     ├── services
|     ├── socket // 除了登录注册，其他都用socket 来通信
|     └── utils  // 工具函数模块
|     ├── configs
|       ├── configs.common.ts // webpack 通用配置
|       ├── configs.dev.ts // webpack 开发配置
|       └── configs.prod.ts // webpack 生产配置
    └── main.ts
│   ├── tsconfig.json
│   ├── tslint.json
│   └── webpack.config.js
├── src // 前端代码
│   ├── App.js
│   ├── app.scss
│   ├── assets
│   ├── components  // 组件
│   ├── containers  // 页面
│   ├── index.html
│   ├── index.js
│   ├── manifest.json
│   ├── modules
│   ├── redux
│   ├── router  // 前端路由
│   ├── service-worker.js
│   └── utils  // 工具函数
├── webpack.common.config.js  // 通用webpack设置
├── webpack.prod.config.js //生产相关的webpack配置
└── webpack.dev.config.js //开发相关的webpack配置
```

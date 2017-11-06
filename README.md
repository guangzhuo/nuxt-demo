开发人员

$ yarn 下载依赖包
$ yarn run dev 启动开发环境服务
$ yarn run build 项目构建
$ yarn run start 启动基于构建后代码的服务
运维人员

构建代码

$ yarn 下载所有依赖包
$ yarn run build:prod 项目构建 build:test,build:pre,build:prod
部署代码至对应服务器
Copy .nuxt/dist 至 静态资源服务
Copy .nuxt/,build/,static/,package.json，ecosystem.config.js 至 Node.js server
启动/重载Node.js服务
$ yarn install --production 安装生产环境依赖包
$ yarn run deploy:prod启动/重载服务 deploy:test,deploy:pre,deploy:prod

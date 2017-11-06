开发人员

$ yarn 下载依赖包<br/>
$ yarn run dev 启动开发环境服务<br/>
$ yarn run build 项目构建<br/>
$ yarn run start 启动基于构建后代码的服务<br/>

运维人员

1.构建代码<br/>
 $ yarn 下载所有依赖包<br/>
 $ yarn run build:prod 项目构建 build:test,build:pre,build:prod<br/>
2.部署代码至对应服务器<br/>
 Copy .nuxt/dist 至 静态资源服务<br/>
 Copy .nuxt/,build/,static/,package.json，ecosystem.config.js 至 Node.js server<br/>
3.启动/重载Node.js服务<br/>
 $ yarn install --production 安装生产环境依赖包<br/>
 $ yarn run deploy:prod启动/重载服务 deploy:test,deploy:pre,deploy:prod

# yarn 常用指令

*以安装 vue 及 vue-cli 为例*

- `yarn init -y`：初始化项目，生成 package.json 文件，相当于 `npm init -y`
- `yarn`：安装 package.json 里的全部包，相当于 `npm i`
- `yarn add vue`：添加 vue ，会记录在 package.json 的 dependencies （运行依赖）下
- `yarn add vue --offline`：可以离线添加之前已经缓存过的包
- `yarn global add vue-cli`：全局安装，且参数 global 必须接在 yarn 的后面 ！！！
- `yarn gloal list`：查看全局安装的包
- `yarn add vue@2.3.0`：指定版本号安装
- `yarn add bable -D`：添加模块到开发环境 **package.json** 的 devDependencies（开发依赖） 下
- `yarn remove vue`：移除 vue
- `yarn upgrade vue`：升级 vue
- `yarn cache dir`：会打印出当前的 yarn 全局缓存在什么目录
- `yarn cache clean`：清除缓存
- `yarn dev`，`yarn start`，`yarn build`：运行 **package.json** 里的 JavaScript 脚本，可省略 run 
- `yarn autoclean -I`：通过从依赖文件中移除不需要的文件和文件夹来释放空间，减少 <font color="red">node_modules</font> 的体积



# npm常用命令